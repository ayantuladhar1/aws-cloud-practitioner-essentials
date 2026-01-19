# Amazon Elastic File System (EFS)

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/0679f936-93b7-4240-8090-29604180ae96" />

Amazon EFS is a fully managed, scalable file storage service for use with AWS cloud services and on-premises resources. It operates using the Linux Network File System (NFS) protocol, and automatically scales to petabytes as you add or remove files without disrupting applications. EFS is designed to support a wide variety of workloads and can be accessed by multiple EC2 instances simultaneously.

## Amazon EFS benefits
**Multi-AZ redundancy**  
Amazon EFS automatically replicates data across multiple Availability Zones in a region for high availability. This built-in redundancy protects against AZ failures and provides continuous access to your file systems.

**Shared access**  
Amazon EFS supports thousands of concurrent NFS connections, so multiple EC2 instances can access the same file system simultaneously. This shared access model makes EFS ideal for collaborative workloads and distributed applications.

**Elastic storage**  
Amazon EFS automatically grows and shrinks as you add and remove files, with no need to provision or manage storage capacity. And since you only pay for the storage you use, it's cost-effective for varying workload demands.

## Amazon EFS storage classes
With Amazon EFS, you can create and configure file systems quickly without any minimum fee or setup cost. You pay only for the storage used and you can choose from a range of storage classes designed to fit your use case.
To learn more about the Amazon EFS storage classes, choose each of the following three tabs.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/4d0b940b-822c-44c8-a8eb-0333e5dd2117" />  
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/60c3e6ef-0e07-441f-be65-8c8003a80dd2" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/06e3ffc1-ae5d-4ceb-94b9-381c3b55cad1" />


## Amazon EFS data lifecycle
You can further optimize Amazon EFS storage costs by automatically moving data between storage classes based on usage patterns. You can create lifecycle policies that determine when and how files transition between different storage tiers. These automated policies help ensure your data resides in the most cost-effective storage class without manual intervention.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/3eafb552-406e-4b0b-acfc-d182465e9271" />  
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/29fe1694-1273-4bcb-95b7-8a4b48151602" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/dd608ef5-ab97-47b7-bb3f-54cc6faa9211" />
