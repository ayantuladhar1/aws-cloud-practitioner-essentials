# Connecting to the AWS Cloud

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/b7d82c20-a906-41a8-9e40-5d1080fccde9" />

With so many different types of networks, on-premises datacenters, and remote workers, companies need a wide range of ways to connect to the AWS Cloud. In the following section, you will learn four ways to connect to the AWS Cloud:
* AWS Client VPN
* AWS Site-to-Site VPN
* AWS PrivateLink
* AWS Direct Connect

## Securely connect a remote workforce to AWS Cloud resources
Imagine a company with a recent acquisition needing to securely connect their new remote workforce to their AWS Cloud resources. Even the largest companies with worldwide remote workers can quickly scale up and connect to the AWS Cloud. That's where AWS Client VPN can help.

## AWS Client VPN

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/a95c8425-3a6a-4559-a5a8-c7d679fb06e1" />

AWS Client VPN is a networking service you can use to connect your remote workers and on-premises networks to the cloud. It is a fully managed, elastic VPN service that automatically scales up or down based on user demand. Because it is a cloud VPN solution, you don’t need to install and manage hardware or try to estimate how many remote users to support at one time.
**Benefits:** AWS Client VPN provides advanced authentication, remote access. It is elastic and fully managed.
**Use case:** It can be used to quickly scale remote-worker access.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/44911151-d4ab-4ed8-b250-ee851045f91e" />

Client VPN, a managed VPN service, provides secure access to AWS resources and on-premises networks from anywhere. It uses an OpenVPN-based client, and it works with global Regions by using the AWS global network.

## Securely connect sites to other sites
Some companies might want to establish secure, encrypted connections between their on-premises networks like data centers or branch offices and their resources in their Amazon VPC. That's where Site-to-Site VPN can help.

## AWS Site-to-Site VPN

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/52086ff1-9a3e-43b1-8a3a-3da514b3a0ee" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/a4440c89-5310-4647-aa95-a4e9399a85ec" />

Site-to-Site VPN creates a secure connection between your data center or branch offices and your AWS Cloud resources.
**Benefits:** Site-to-Site VPN provides high availability, secure and private sessions, and accelerates applications.
**Use cases:** It can be used for application migration and secure communication between remote locations.

## Securely connect resources, even in other VPCs
Other companies sometimes need the flexibility to privately connect to resources in other cloud providers as though they were in their own VPC. They need a way to communicate with these resources and don't want the hassle of setting up gateways or site-to-site VPNs. That's where AWS PrivateLink can help.

## AWS PrivateLink

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/4b8b9943-ae98-42af-b435-636e97888b2a" />

AWS PrivateLink is a highly available, scalable technology that you can use to privately connect your VPC to services and resources as if they were in your VPC. You do not need to use an internet gateway, NAT device, public IP address, Direct Connect connection, or AWS Site-to-Site VPN connection to allow communication with AWS services or resources from your private subnets. Instead, you control the specific API endpoints, sites, services, and resources that are reachable from your VPC.
**Benefits:** AWS PrivateLink helps you secure your traffic and connect with simplified management rules.
**Use case:** It is used for connecting your clients in your VPC to resources, other VPCs, and endpoints.
Even though the preceding connections are highly available and scalable, traffic jams are possible because you’re using the same connection as other clients. That's why for some use cases, you might need a dedicated private connection with a lot of bandwidth.

## Dedicated private connections for increased bandwidth
## AWS Direct Connect

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/31c8b572-72cc-4a1a-831e-f9f378c8ca60" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/4e4ce4a5-93c9-4529-92d1-7605f0aff7cc" />

Direct Connect is a service that makes it possible for you to establish a dedicated private connection between your network and VPC in the AWS Cloud.
**Benefits:** AWS Direct Connect reduces network costs and increases amount of bandwidth.

## To learn more about Direct Connect, expand each of the following three categories.
* Latency-sensitive applications
  * Direct Connect bypasses the internet and provides a consistent, low-latency network experience. This makes it ideal for applications like video streaming and other real-time applications that require high performance.
* Large-scale data migration or transfer
  * Direct Connect helps ensure smooth and reliable data transfers at massive scale for real-time analysis, rapid data backup, or broadcast media processing.
* Hybrid cloud architectures
	* You can use Direct Connect to link your AWS and on-premises networks to build applications that span environments without compromising performance.
	
## Additional gateway services
There are several different types of gateways you can use to connect your AWS resources. Depending on your needs, you might want to learn more about what they are used for and where to go to learn more. To learn more about these additional gateway types, expand each of the following three categories.

## AWS Transit Gateway
AWS Transit Gateway is used to connect your Amazon VPCs and on-premises networks through a central hub. As your cloud infrastructure expands globally, inter-Region peering connects transit gateways together using the AWS Global Infrastructure. 

## Network Address Translation (NAT) Gateway
A NAT gateway is a NAT service. You can use a NAT gateway so that instances in a private subnet can connect to services outside your VPC but external services can't initiate a connection with those instances. 

## Amazon API Gateway
You learned about Application Programming Interface (API)s earlier. Quick refresher, an API defines how different software systems can interact and communicate with each other. The Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing APIs at any scale.
In this lesson, you identified services that help you connect your AWS Cloud to your clients, datacenters, and sites. To review the four types of connectivity options, choose each of the following flashcards.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/6a86dce1-862c-4b8f-964c-398b088c19d2" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/a2344b79-ed44-46ae-bc60-37edb43d800e" />
