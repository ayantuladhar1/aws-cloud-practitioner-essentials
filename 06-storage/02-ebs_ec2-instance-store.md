# EC2 Instance Store and Amazon Elastic Block Store (EBS)

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/d48ca837-2536-4dec-b0ac-b016c44aca56" />

## Amazon EC2 instance store
Amazon EC2 instance store isn't a stand-alone AWS block storage service. Rather, it refers to the block-level storage that is physically attached to the EC2 instance host computer. Depending on the type of instance, EC2 instance store might come attached as the default storage. Since its data is lost when an instance is stopped or terminated, EC2 instance store is best for temporary memory-based storage needs like buffers, caches, and scratch data. It is not recommended for applications that require data retention.

## Key takeaway: no data persistence
An Amazon EC2 instance store provides temporary block-level storage for an Amazon EC2 instance. This means that if you stop or terminate an Amazon EC2 instance, all the data written to the attached instance store is deleted.
To learn how Amazon EC2 instance store manages data when an EC2 instance is stopped, choose each of the following three numbered markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/0a5925ee-e896-4d01-b9ba-3eea21473ac8" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/0f605f44-6d32-40fd-8f8a-7f1a1409d7f1" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/2034b8c2-c314-4444-b506-a89a6dda3057" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/27152e4d-bf01-4301-9a65-5765186e48d4" />

## Benefits
**Automatically available storage**  
Instance store volumes come automatically attached to many EC2 instance types, providing temporary block-level storage at no additional cost. It's physically connected to the host computer, offering high I/O performance for data that disappears when the instance stops.

**Cost effective**  
Because EC2 instance store is included in the EC2 instance price, you don't have to pay any additional fees for storage. It's ideal for temporary storage needs like buffers, caches, or scratch data, potentially reducing expenses for applications that don't require persistent storage.

**High performance**  
EC2 instance store offers extremely low-latency storage directly attached to the host server of your EC2 instance. This proximity means exceptionally high I/O performance, making it ideal for temporary storage of data requiring fast processing.

## Amazon Elastic Block Store (EBS)

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/bc1f260e-5368-4912-a608-7a14c380967a" />

Amazon EBS provides persistent block-level storage volumes for use with Amazon EC2 instances. EBS volumes act like external hard drives, offering consistent and low-latency performance for workloads like databases and file systems.

EBS volumes can be conveniently backed up, resized, and attached to different EC2 instances. To create an EBS volume, you define the configuration for things like volume size and type. After the volume has been created, it can be attached to an Amazon EC2 instance. Because EBS volumes are for data that needs to persist, it’s important to back up the data. It's recommended that you take incremental backups of EBS volumes by creating Amazon EBS snapshots.

## Key takeaway: data persistence
Amazon EBS provides block-level storage volumes that you can use with Amazon EC2 instances. If you stop or terminate an Amazon EC2 instance, all the data on the attached EBS volume remains available.
To learn how Amazon EBS manages data when an EC2 instance is stopped, choose each of the following three numbered markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/d1ea89ce-77fa-4ed2-83cb-0f074e78a996" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/9e034bf0-0130-4783-af5a-fb65bcb43a75" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/3bfb0292-3245-45d0-bde6-758ad0d8b5a2" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/cabaed92-a82d-4406-9154-03393644137d" />

## Use cases
Some practical use cases of Amazon EBS include database hosting, backup storage for applications, and rapid deployment of development environments using volume snapshots.

## Benefits
EBS volumes support data portability through their ability to detach and reattach to instances as needed. There are many practical reasons you might choose to do this.
**Data migration**  
EBS volumes can be easily migrated between Availability Zones using snapshots. The snapshots provide a simple way to move data across regions or create copies.

**Instance type changes**  
Since EBS volumes remain independent of EC2 instances, it's not complicated to attach them to different instance types. This flexibility lets you upgrade or downgrade instances without losing data.

**Disaster recovery**  
EBS snapshots provide reliable backup solutions that can be restored in different regions during emergencies. Regular automated snapshots ensure your data remains protected and quickly recoverable.
	
**Cost optimization**  
EBS volumes can be modified to different types and sizes to match actual usage patterns. You can switch between storage types or adjust capacity without downtime.
	
**Performance tuning**  
Amazon EBS offers various volume types to match different workload requirements and IOPS needs. You can adjust volume performance characteristics on the fly to meet changing application demands.
