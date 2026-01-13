# AWS Regions and Availability Zones
AWS Global Infrastructure consist of physical locations around the world that contains group of data centers.

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/341ec955-0b7e-40bb-8bde-4ccd1f1bc129" />

	
## AWS Regions
AWS Regions are physical locations around the world that contain group of data centers. These group of data centers are called Availability Zones. Each AWS Region consists of a minimum of three physically separate Availability Zones within a geographic area.
	
## Availability Zones
An Availability Zones consists of one or more data centers with redundant power, networking, and connectivity. Regions and Availability Zones are designed to provide low-latency, fault-tolerant access to service for users within a given area.
		
# Achieving high availability with AWS Global Infrastructure
AWS infrastructure is designed with high availability and fault tolerance in mind. Availability Zones(AZs) are configured as isolated resources, and they are each equipped with independent power, networking, and connectivity. 
It's recommended to distribute your resources across multiple AZs. That way, if one AZ encounters an outage, your business applications will continue to operate without interruption. With this approach of redundancy and resource isolation, AWS customers can achieve the benefits of high availability and fault tolerance.
