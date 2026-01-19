# Organizing resources in the AWS Cloud

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/076a1417-5d41-4d9a-97b7-6aba02f102f2" />

Imagine the millions of customers who use AWS services. Also imagine the millions of resources that these customers have created, such as Amazon EC2 instances. Without boundaries around all these resources, network traffic can flow between them unrestricted. In the following section you will learn about two components of the AWS Cloud.
* Amazon Virtual Private Cloud (VPC)
* Gateways to connect your resources

## Establishing boundaries around AWS resources
When organizing your resources in the AWS Cloud, you need to be able to group certain functions together and isolate them from the public, or make them available to the public. You've been introduced to what Amazon VPCs do. Next, you will review the benefits.

## Amazon VPC

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/2d176240-8b83-4489-abb0-4b0d364a984c" />

With Amazon VPC, you can provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define. It provides three main benefits. It helps increase security because you can secure and monitor connections, screen traffic, and restrict instance access. Amazon VPC gives you full control over your resource placement, connectivity, and security. The convenience of using Amazon VPC means you will spend less time setting up, managing, and validating your virtual network when compared to on-premises network management.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/0eeb5216-5f4d-4cce-b7be-c60ccfbd05c0" />

## Subnets
Within an Amazon VPC, you can organize your resources into subsections or subnets. A subnet is a section of an Amazon VPC that can contain resources, such as Amazon EC2 instances. You will learn more about subnets in the next lesson.

## Connecting your resources with an internet gateway
To allow public traffic from the internet to access your VPC, you attach an internet gateway to the VPC. An internet gateway is a connection between a VPC and the internet. You can think of an internet gateway as being similar to a doorway that customers use to enter the coffee shop. Without an internet gateway, no one can access the resources within your VPC.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/0a70ae16-90a9-4822-aa03-846afc161ff7" />

## Virtual private gateways
What if you have a VPC that includes only private resources? The following example shows how a virtual private gateway works. You can think of the internet as the road between your home and the coffee shop. It is open and accessible to anyone. You want a way to protect the traffic you send on the internet from the public, internet service providers, and others who might be trying to track or intercept it. This is where a virtual private network (VPN) connection comes in.
VPN creates a connection that is more like a secure tunnel through the internet. Using encryption, it hides and protects everything you send and receive from outside eyes. A virtual private gateway is the component in the AWS Cloud that makes it possible for you to connect this protected traffic to enter the VPC. With a VPN connection, your data travels privately and safely, hidden from others using the same route.
With a virtual private gateway, you can establish a VPN connection between your VPC and a private network, such as an on-premises data center or internal corporate network. A virtual private gateway allows traffic into the VPC only if it is coming from an approved network.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/49541037-2eef-44b3-8ae3-8fd37c707466" />


Several of the preceding networking components have similar abbreviations and are often confused. These components are core building blocks that you'll use in many AWS Cloud solutions. To learn the differences between these acronyms, choose each of the following flashcards.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/d9ebeac2-a5da-4d3e-b217-a65c303e0731" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/ca92034d-9e78-4bd3-b9b4-96d518493814" />
