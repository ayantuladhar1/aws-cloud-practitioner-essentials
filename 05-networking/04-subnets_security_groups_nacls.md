# Subnets
A section of a VPC for grouping resources based on security or operational needs

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/d17fae7b-bacc-4330-b145-22285d49cb91" />

A subnet is a section of a VPC in which you can group resources based on security or operational needs. Subnets can be public or private.
Public subnets contain resources that need to be accessible by the public, such as an online store’s website.
Private subnets contain resources that should be accessible only through your private network, such as a database that contains customers’ personal information and order histories.
In a VPC, you can define rules to allow resources in different subnets to communicate with each other. For example, you might have an application that uses Amazon EC2 instances in a public subnet communicating with databases that are located in a private subnet.

## Network traffic in a VPC
## The movement of data packets traveling across a network##
When a customer requests data from an application hosted in the AWS Cloud, this request is sent as a packet. A packet is a unit of data sent over the internet or a network.
It enters into a VPC through an internet gateway. Before a packet can enter into a subnet or exit from a subnet, it will run into several checks for permissions, one being a network ACL associated with the subnet the packet is being routed to. The permissions defined by the network ACLs indicate what is allowed or denied. It is based on who sent the packet and how the packet is trying to communicate with the resources in a subnet.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/1db40c16-3d5d-429a-8bec-ae3e166822de" />

The VPC component that checks packet permissions for subnets is a network ACL.

# Network ACLs
## Virtual firewall controlling traffic
A network ACL is a virtual firewall that controls inbound and outbound traffic at the subnet level.
For example, imagine that you are at the airport. Travelers are trying to enter into a different country. You can think of the travelers as packets and the passport control officer as a network ACL. The passport control officer checks travelers’ credentials when they are both entering and exiting the country. This is similar to how a network ACL checks permissions every time a packet travels across a subnet boundary.
Each AWS account includes a default network ACL. When configuring your VPC, you can use your account’s default network ACL or create custom network ACLs. By default, your account’s default network ACL allows all inbound and outbound traffic, but you can modify it by adding your own rules.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/815b02ef-b099-44f2-bb0b-4f0d7cf2eecd" />

For custom network ACLs, all inbound and outbound traffic is denied until you add rules to specify which traffic to allow. Additionally, all network ACLs have an explicit deny rule. This rule makes sure that if a packet doesn’t match any of the other rules on the list, the packet is denied.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/59ecfc83-b845-4893-8308-68b8904e3bb5" />

## Stateless packet filtering
Network ACLs perform stateless packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound.
Recall the previous example of a traveler who wants to enter into a different country. This is similar to sending a request out from an Amazon EC2 instance and to the internet.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/afa48fa5-1872-4eec-9636-9a358ac1a463" />

When a packet response for that request comes back to the subnet, the network ACL does not remember your previous request. The network ACL checks the packet response against its list of rules to determine whether to allow or deny.

# Security groups
## Control inbound and outbound traffic at the resource level
After a packet has entered a subnet, it must have its permissions evaluated for resources within the subnet, such as Amazon EC2 instances. A security group is the VPC component that checks packet permissions for an Amazon EC2 instance. It is a virtual firewall that controls inbound and outbound traffic for specific AWS resources, like Amazon EC2 instances.
By default, a security group denies all inbound traffic and allows all outbound traffic. For this example, suppose that you are at an apartment building with a door attendant who greets guests at the door. You can think of the guests as packets and the door attendant as a security group. With the default settings, the security groups won't let anyone in and allows all outbound traffic out.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/99b3e6c0-31ab-4bf4-a283-ea519d08a608" />

With security groups, you can add custom rules to configure which traffic should be allowed. Any other traffic would then be denied. For example, custom rules can be given separately for inbound and outbound traffic. As guests arrive, the door attendant checks a list to makes sure they can enter the building. However, the door attendant does not check the list again when guests are exiting the building.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/4851e0e1-87a3-4bac-af5b-41a5153362a2" />

**Note:** If you have multiple Amazon EC2 instances within the same VPC, you can associate them with the same security group or use different security groups for each instance.

## Stateful packet filtering
Security groups perform stateful packet filtering. They remember previous decisions made for incoming packets.
Consider the same example of sending a request out from an Amazon EC2 instance to the internet. When a packet response for that request returns to the instance, the security group remembers your previous request. The security group allows the response to proceed, regardless of inbound security group rules.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/67030db8-1283-4b1c-8201-d8b73fc280ad" />


With both network ACLs and security groups, you can configure custom rules for the traffic in your VPC. As you continue to learn more about AWS security and networking, it is important to understand the differences between them. The following table will help you understand which to use.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/de942ce2-b760-4434-8963-70f9f2233056" />

Remember the AWS Shared Responsibility Model? When it comes to securing the subnets and resources in your VPC with network ACLs and security groups, that is your responsibility. These components make up networking traffic protection and are critical defenses in protecting your applications IN the cloud.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/769faad9-acc8-472d-a589-fcf5e15dbee8" />
