# Networking Components

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/c41c9a97-72d0-4405-8b94-0b13eb063189" />

## Amazon Virtual Private Cloud (Amazon VPC)

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/3979101f-bc42-4bcd-9c8f-27dbbf54ec97" />

An Amazon VPC lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.

## Subnet

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/45b48033-089f-4d49-8842-0fca9ea99ff6" />

Subnets are used to organize your resources and can be made publicly or privately accessible. A private subnet is commonly used to contain resources like a database storing customer or transactional information. A public subnet is commonly used for resources like a customer-facing website.

## Networking components: Understanding connections through diagrams
If you are new to IT or cloud computing, you might now have worked with architectural diagrams before. A diagram is simply a schematic or map of your network in the AWS Cloud. It can provide a visual of how users or applications access services, resources or data. A picture is worth a thousand words. With a quick glance, you can see if the network was built for redundancy, security and even scalability. It can also serve as a blueprint so you don't forget important connections when building your solutions.

## AWS Cloud, Regions, Amazon VPC and AZs

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/361db661-9fc7-416d-9019-fb0c7816611c" />

The AWS Cloud is the outermost box in most diagrams.
Region is the next box. AWS Regions are separate Geographic areas. you choose your reason based on your user's geographic location for lower latency, compliance and data residency requirements, available services, and cost.
Amazon VPC Is a solid box and it represents your isolated logically segmented network within AWS. A VPC helps you to control your network resources and security.
Availability zones are shown as separate boxes across a region. AZs consist of one or more discrete data Centers, each with redundant power, networking, and connectivity, and housed in a separate facilities. Using multiple AZs can protect your applications from the failure of a single location in the region.

## Private subnets

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/0d7e778c-b653-4104-b8dc-0fb609e601a6" />

Subnets are essentially segments of your VPC, allowing you to divide your VPC into smaller, manageable sections. A subnet is a range of IP addresses in your VPC.

Private subnets are designed to isolate resources that should not be directly exposed to the public internet. In diagrams, they are illustrated with solid boxes.

## Public subnets

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/31bf5e19-b8da-470b-859b-dffdb43bf2f6" />

Public subnets are designed to provide direct internet access to resources placed inside them. To allow access, they are connected with an internet gateway. You will learn about internet gateways in a later lesson. In diagrams, public subnets are drawn with dashed boxes.
