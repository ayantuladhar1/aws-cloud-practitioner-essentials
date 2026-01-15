# Relational Database Services
Relational databases use a rigid schema that organizes collections of data into tables with rows and columns, where relationships exist between different tables. In this lesson, you will explore the benefits and use cases for AWS relational database services, including Amazon RDS and Amazon Aurora.

# # Relational databases
Relational databases store data in a way that relates it to other pieces of data, and they use structured query language, or SQL, to manage and query data. This approach stores data in an easily understandable, consistent, and scalable way that works great for applications requiring structured data management.
AWS offers fully managed relational database solutions that remove the burden of database administration while maintaining high availability and security. AWS relational databases support popular database engines like MySQL, PostgreSQL, and Oracle, making it easier to migrate existing databases to AWS.
An example of a relational database would be an inventory management system for a restaurant. Each record in the database includes data for a single item, such as product name, size, price, and so on. The following table shows how this type of data is configured in a relational database.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/c7f13c2a-e405-4747-886a-09e8990231bb" />


## Amazon Relational Database Service (Amazon RDS)

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/11b6079c-8b4a-4f7f-92b8-81e080b1c1c2" />

Amazon RDS is a managed relational database service that handles routine database tasks such as backups, patching, and hardware provisioning. Amazon RDS supports multiple database instance class types that optimize for memory, performance, or input/output (I/O).
To improve data resilience, Amazon RDS offers Multi-AZ deployment and automated backups, but you can also manually create backups using DB snapshots. These are full backups of your entire database instance, which can be useful for specific point-in-time recovery or long-term data archiving purposes. Amazon RDS offers security features including network isolation, encryption in transit, and encryption at rest. You can readily scale database resources vertically or horizontally as needed.

## Supported database engines
Amazon RDS supports different database engines, including Amazon Aurora, MySQL, PostgreSQL, Microsoft SQL Server, MariaDB, and Oracle Database.

## Use cases
Some examples of practical use cases for Amazon RDS are web applications, enterprise workloads, and product inventories for e-commerce platforms.

## Benefits
**Cost optimization**  
Amazon RDS eliminates the high upfront costs of purchasing and maintaining database hardware infrastructure. You only pay for the compute and storage resources that you consume through a flexible pay-as-you-go model. As a managed service, it also reduces operational expenses by automating time-consuming administrative tasks like backups, patching, and monitoring.
	
**Multi-AZ deployment**  
Amazon RDS improves database reliability through Multi-AZ deployments. It automatically replicates data to a standby instance in a different Availability Zone. During system failures, maintenance, or zone disruptions, Amazon RDS automatically fails over to the standby instance without manual intervention. This ensures continuous database operations with minimal downtime.
	
**Performance optimization**  
Amazon RDS enhances database performance through automated management of resource allocation, monitoring, and optimization tasks. It includes features like automated backups and read replicas that can help offload read traffic from the primary instance. Amazon RDS performance insights provide real-time monitoring and analysis of database load, to help you identify and resolve performance bottlenecks quickly.
	
**Security controls**  
Amazon RDS enhances database security through multiple layers of protection, including VPC isolation as well as encryption at rest and in transit. It leverages automated backups and offers Multi-AZ deployments to provide resiliency against potential system failures.
	
## Amazon Aurora

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/cd255aa5-bdbc-4b49-bd40-91dde4b14fc7" />

Aurora is a managed relational database designed to help reduce unnecessary I/O operations. It's compatible with MySQL and PostgreSQL, provides high performance and availability, and automatically scales alongside your workloads. Aurora replicates data across multiple Availability Zones for enhanced durability and fault tolerance, and features automated backups, encryption at rest, and continuous monitoring.

## Use cases
Some examples of practical use cases for Aurora are gaming applications, media and content management, and real-time analytics.
	
## Benefits
**High performance and availability**  
Aurora delivers up to five times the throughput of standard MySQL and three times the throughput of PostgreSQL. It uses a distributed storage system across multiple nodes to provide high performance and availability.
		
**Automated storage and backup management**  
Aurora automatically grows storage from 10 GB to 128 TB based on your actual data usage, which eliminates guesswork in capacity planning. It also continuously backs up your database to Amazon Simple Storage Service (Amazon S3) to provide point-in-time recovery.

**Advanced replication and fault tolerance**  
Aurora replicates data across three Availability Zones with six copies of data, and provides 99.99% availability. It automatically detects database failures and redirects traffic to healthy replicas without data loss.
