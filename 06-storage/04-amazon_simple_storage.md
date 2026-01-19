
# Amazon Simple Storage Service (S3)

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/998a70c0-f265-4957-98e9-d603eaffd670" />

Amazon S3 is a fully managed, highly-available object storage service for storing and retrieving any amount of data as objects. It offers 99.999999999 percent durability, meaning your data is highly protected against loss, and offers features like versioning, lifecycle management, and various storage classes to optimize costs.
Amazon S3 stores files as objects in containers known as buckets, and each object can range in size from a few bytes to several terabytes. It integrates seamlessly with other AWS services and supports a wide range of use cases, from basic backups to complex data lakes.

## Elements
## S3 objects

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/15536ba5-2cfc-43a6-ae36-06ffdb9c07a1" />

An object in Amazon S3 is the fundamental unit of data storage. When you upload a file to Amazon S3, it becomes an object and is stored durably across multiple facilities within your chosen Region.
Each object typically includes the data itself, metadata, and a unique identifier, or key. Objects can be of any file type, such as images, videos, documents, or application data, and can range in size from a few bytes to several terabytes.
Each Amazon S3 object is uniquely identified within a bucket by its key, which is essentially its file name. Objects also have properties like version ID, access control information, and user-defined metadata.

## S3 buckets

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/21aabcd7-2b93-4b85-a6ff-8d8040c26a8b" />

An S3 bucket is a container for storing objects in Amazon S3. Buckets have a globally unique name across all of AWS, which helps to identify and organize your stored data.
Buckets serve as the basic unit for access control and can hold a virtually unlimited number of objects. They play a crucial role in data management by making it possible to group related objects and apply policies at the bucket level.
When creating a bucket, you specify its name and the Region where it will reside. Buckets can be configured with various settings, including versioning, logging, and access permissions.

## Benefits
**Virtually unlimited storage**  
Amazon S3 has no fixed storage limit, scaling automatically to accommodate any amount of data you need to store. Since you only pay for the storage you use, it's a cost-effective solution for growing data needs.
	
**Object lifecycle management**
Amazon S3 lifecycle policies automatically move objects between storage classes based on your defined rules, optimizing costs over time. You can set up automatic transitions and expirations to manage data throughout its entire lifecycle.
	
**Broad range of use cases**
Amazon S3 supports a wide range of use cases for both cloud-based applications and traditional on-premises workloads. Amazon S3 is commonly used for content distribution, hosting static websites, and delivering media files. It's also a popular choice for things like application data storage, archiving, data lakes, and compliance-driven data retention.

## Security and privacy management
Everything you store in Amazon S3 is private by default. You must explicitly grant permissions to access these resources. If you want your Amazon S3 data to be available to everyone on the internet, you can choose to make your buckets and objects public. To more granularly define who can do what with your Amazon S3 resources, Amazon S3 provides several security management features.
To learn more about Amazon S3 security management features, choose each of the following three tabs.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/4532ed75-e553-4ae7-9c41-9b01ffec3078" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/0f6bb6e0-0225-4cc9-98bd-1465f187d590" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/028d71a7-856f-43fd-81c2-5a7385029417" />
