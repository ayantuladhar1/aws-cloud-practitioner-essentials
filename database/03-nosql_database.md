# NoSQL Database Services
NoSQL databases use flexible data schemas for storing and retrieving many different types of information. In this lesson, you will explore the benefits and use cases of the NoSQL database service Amazon DynamoDB.

## NoSQL databases
NoSQL databases are sometimes referred to as non-relational databases because their structures are different than relational databases like Amazon RDS. Instead of row and column relationships, NoSQL databases build a structure for the data that they contain using key-value pairs instead. With key-value pairs, data is organized into items identified by unique keys.
Each key has one or more associated attributes, or values, that represent various characteristics of the data. You can think of a key as a word entry in a dictionary, and the value as its associated definition. Not every item in the table has to have the same attributes, and you can add or remove attributes at any time.
The following table shows an example of how key-value paired data is stored in NoSQL databases.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/438621f8-3e06-414b-a960-1678a34ec8a2" />

## Amazon DynamoDB

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/83fafbc1-bade-4839-8e22-9dcc08510004" />

DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance for both document and key-value data structures. It's a powerful and incredibly fast database option for use cases that require a flexible schema, and is ideal for applications that require high performance and seamless scaling.
DynamoDB seamlessly scales alongside your data without impacting performance, which means that you only pay for the resources that you use. It also includes built-in security features for enhanced protection, and automatically spreads your data across multiple servers to handle your workload.

## Use cases
Some examples of practical use cases for DynamoDB are gaming platforms, financial service applications, and mobile applications with global user bases.

## Benefits
**Scalability with provisioned capacity**  
DynamoDB automatically scales throughput up or down based on actual usage, which ensures consistent performance without manual intervention. You can specify target utilization levels, and DynamoDB automatically provisions capacity to maintain those targets. With no practical limits on table size or the amount of data stored, DynamoDB can seamlessly accommodate growing applications.
	
**Consistent high performance**  
DynamoDB delivers single-digit millisecond response times at any scale, which makes it ideal for high-performance applications. It maintains consistent performance by automatically distributing data across multiple servers and SSDs.
	
**High availability and durability**
DynamoDB delivers 99.999% data availability by replicating data across three distinct facilities within each AWS Region. It also maintains multiple copies in separate AWS Regions, to provide built-in fault tolerance and data durability. This ensures continuous operation and protection against data loss even if individual facilities fail.
	
**Data encryption**
DynamoDB offers comprehensive encryption capabilities to protect information both at rest and in transit. All data is automatically encrypted behind the scenes before being written to the storage layer. DynamoDB includes the flexibility to choose between different kinds of encryption keys for customized security control.
