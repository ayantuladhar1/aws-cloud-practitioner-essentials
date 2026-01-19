# Intro to Storage

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/802009e2-d2d9-4dcf-9ea9-faa6c67e1bba" />

## Block storage

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/5996f002-71c2-4eda-8313-43ebc7ef8312" />

Block storage provides persistent, low-latency block-level storage volumes that attach to EC2 instances like physical hard drives. Block storage volumes can be encrypted, backed up via snapshots, and modified while in use without disrupting the instance. AWS offers two primary block storage services:
* Amazon EC2 instance store
An unmanaged non-persistent, high-performance block storage directly attached to EC2 instances for temporary data.
* Amazon Elastic Block Store (EBS)
A managed service that provides persistent block storage volumes for EC2 instances, offering various types for different workloads

## Object storage

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/44315084-6937-4c41-ab0c-6ae850d766b7" />

Object storage is a data storage architecture that manages data as objects in a flat address space. It offers unlimited scalability so you can store vast amounts of unstructured data without worrying about capacity constraints. Object storage provides enhanced metadata capabilities to provide more efficient data management, search, and analytics across massive datasets.
The following is the primary AWS object storage service:
* Amazon Simple Storage Service (S3)
A fully managed scalable object storage service for storing and retrieving any amount of data from anywhere.

## File storage

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/381467de-9616-4801-8d0a-e5f8602d157d" />


AWS file storage services provide shared file systems accessible over networks, so multiple users and applications can access the same data simultaneously. They offer scalability and flexibility so you can expand storage capacity as needs grow without managing physical infrastructure. AWS offers two primary file storage services:
* Amazon Elastic File System (EFS)
A fully managed, scalable NFS file system for use with AWS Cloud services and on-premises resources.
* Amazon FSx
A fully managed file storage services for popular file systems like Windows, Lustre, and NetApp ONTAP.

## Additional storage services

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/5288ad76-8da4-4931-b573-cae366402819" />

These services don't fit cleanly into the categories we've defined so far, but they're important AWS storage offerings that you should be familiar with.
* AWS Storage Gateway
A fully managed, hybrid-cloud storage service that provides on-premises access to virtually unlimited cloud storage.
* AWS Elastic Disaster Recovery
A fully managed service that streamlines the recovery of your physical, virtual, and cloud-based servers into AWS.

# AWS shared responsibility
## AWS storage services
The AWS shared responsibility model groups services into three categories based on the ownership of administrative tasks. These categories are fully managed, managed, and unmanaged.
To learn more about how these categories relate to storage services, expand the following three categories.

## Fully managed services
For fully managed storage services, AWS is responsible for everything from the hardware and infrastructure up through the entire storage stack. This includes data durability, availability, encryption at rest, and replication. Customers are only responsible for data management, access controls, and proper service configuration.

## Managed services
For managed storage services, AWS manages the underlying storage infrastructure, hardware redundancy, and volume replication. Customers are responsible for data backup strategies, encryption configuration, volume performance optimization, and capacity planning.
Unmanaged services
For unmanaged storage services, customers takes full responsibility for data management, backup/recovery, encryption, performance optimization, and durability. AWS only maintains the underlying physical hardware and network infrastructure.
