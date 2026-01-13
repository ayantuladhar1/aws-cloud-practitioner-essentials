# Designing highly available architectures
## Deploying multi-Region and multi-AZ resources
You have learned how deploying your cloud resources to multiple Regions can achieve high availability. In addition to deploying to multiple Regions you also want to deploy resources to multiple Availability Zones. By building redundant architectures or replicating your resources across multiple levels of AWS infrastructure, you can improve application replicability so that your user have access to your consent when they need it.
In addition to high availability, the AWS Global Infrastructure also helps you achieve agility and elasticity for your business. 
Let's discuss the difference between these advantages:
* High availability: It refers to the capability of a system to operate continuously without failing. In the context of AWS Infrastructure, it means that your applications can handle the failure of individual components without significant downtime.
* Agility: Agility refers to the ability to quickly adapt to changing requirements or market conditions. With AWS Infrastructure in place you can modify and deploy service rapidly. 
* Elasticity: Elasticity refers to the ability of a system to scale resources up or down automatically in response to changes in demand. AWS Infrastructure is set up for you to scale resources up or down on demand.
		
## Edge Locations

<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/326a41ee-7176-4119-b79d-6d7b1b2b1e9c" />

In Addition to AWS Regions that contain Availability Zones. AWS has a global edge network that provides quicker content access to users outside of standard Regions. These edge locations are strategically placed in areas like Atlanta, Georgia, USA or Shanghai, China to provide low-latency access to AWS services and content delivery. Edge locations offer multiple services to run closer to end user, including AWS networking services like Amazon CloudFront. CloudFront is a content delivery network (CDN) and caching system that you learn more about later in this training
	
## Key Elements of AWS Global Infrastructure

<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/84d61c71-4d38-442a-b2f3-3f18b5b84b9c" />

* AWS Regions
  * Regions are geographical areas around the world that are made up of multiple data centers. These data centers provide scalable and redundant infrastructure for hosting cloud services. Each Region consists of multiple, isolated locations known as Availability Zones, Each Region has three or more Availability Zones.	
* Availability Zones
  * Availability Zones are distinct locations within a Region, each designed as an independent zone with its own power, networking, and connectivity. Availability Zones maintain high availability and fault tolerance for applications. Each Availability Zones consists of one or more data centers.
* Edge locations
  * Edge locations are strategically placed sites around the world that cache content to deliver data, video and applications with lower latency and higher transfer speeds. Edge locations are considered a vital part of the AWS content delivery network (CDN) and use services like CloudFront to efficiently distribute data to end users.
