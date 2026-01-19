# AWS Storage Gateway

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/bcb7fc30-ba76-4cea-8211-bcde3795ec97" />

Storage Gateway is a hybrid cloud storage service that makes it possible to seamlessly integrate on-premises environments with AWS Cloud storage. You can use it to extend your local storage to the cloud while maintaining low-latency access to frequently used data.
You can use Storage Gateway to streamline storage management and reduce costs for practical hybrid cloud storage use cases. These include moving backups to the cloud, using on-premises file shares backed by cloud storage, and providing low-latency access to data in AWS for on-premises applications.

## Benefits
**Seamless integration**  
Storage Gateway enables smooth connectivity between on-premises applications and AWS Cloud storage, preserving existing workflows and minimizing disruption.
	
**Improved data management**  
Storage Gateway provides centralized management of hybrid storage environments, enhancing accessibility, security, and compliance.
	
**Local caching**  
Storage Gateway locally keeps frequently accessed data for quick access while managing less-used data in the cloud.
	
**Cost optimization**  
Storage Gateway reduces on-premises storage costs by using cloud storage for data archiving, backup, and disaster recovery purposes.
	
## Gateway types
Storage Gateway offers three distinct types of gateways to meet different hybrid storage needs. Each gateway type is designed to address specific use cases and workload requirements.

## Amazon S3 File Gateway

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/d9f90db6-7576-4ffd-9b1d-ff2752b10618" />

Amazon S3 File Gateway bridges your local environment with Amazon S3. It provides on-premises applications with access to virtually unlimited cloud storage through familiar file protocols. S3 File Gateway makes it possible to store and retrieve cloud objects using familiar file operations.
When you deploy an S3 File Gateway, it appears to your local systems as a standard file server. Files written to this server are automatically uploaded to Amazon S3 while maintaining local access to recently used data through intelligent caching. This means your applications can continue working with files as they always have while the actual data is securely stored in the AWS Cloud.

## Volume Gateway

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/c190d65e-8064-47b5-8954-afd658b25427" />

With Volume Gateway, you create virtual storage volumes while maintaining local access to your data. It essentially functions as a bridge between your on-premises infrastructure and AWS Cloud storage by presenting your cloud data as iSCSI volumes that can be mounted by your existing applications.
Volume Gateway operates in two main configurations:
* Cached volume mode stores primary data in the cloud while frequently accessed data is cached locally for low-latency access.
* Stored volume mode locally keeps your complete dataset while asynchronously backing it up to the cloud as EBS snapshots.

## Tape Gateway

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/0355d138-badd-4b63-a869-fd9fd55a46b0" />

Tape Gateway makes it possible to replace physical tape infrastructure with virtual tape capabilities while benefitting from the durability and scalability of AWS Cloud storage. Tape Gateway provides an interface that works with existing tape backup software, making the transition from physical tapes to cloud storage seamless.
When you deploy a Tape Gateway, it presents itself to your backup applications as standard tape hardware. Your backup software writes data to these virtual tapes just as it would to physical tapes and stored in Amazon S3. You can also configure Tape Gateway to automatically transition less frequently accessed data to a more cost-effective storage class for long-term retention.
