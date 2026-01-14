# Amazon S3 storage classes and use cases
Amazon S3 offers various storage classes to suit a variety of workloads with specific performance, access, resiliency, and cost requirements. They're also designed to address data residency requirements, unpredictable access patterns, archival storage needs, and offer the most cost-effective options for different access patterns.
To learn about each storage class and when it's practical to use them, choose the arrow buttons to display each of the following nine slides.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/a32bb293-7783-4acd-90aa-c5ff6fccf143" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/7a44b0c0-3dc8-4b73-91bd-30a874d08e1d" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/2b1f2ed2-a319-4472-864e-831c43b4d76a" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/d70832c9-948c-457a-b624-2b35518aba29" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/20167193-96db-4e78-ada9-f784d3278316" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/9f5323bf-e7a9-4af4-9661-d46730692c85" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/248489f9-6825-4e9a-9406-ac6246341ca3" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/a847b2ca-39eb-406b-ae1d-f326676a6605" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/f9fa69b4-7355-4a9b-9d03-70c0f5f62c84" />


## S3 Lifecycle
To avoid manually managing your object storage tier configurations, you can use S3 Lifecycle configurations to automate the process. When you define a lifecycle configuration for an object or group of objects, you can choose to automate between two types of actions, as follows:
* Transition actions: define when objects should transition to another storage class.
* Expiration actions: define when objects expire and should be permanently deleted.
For example, you might transition objects to S3 Standard-IA storage class 30 days after you create them. Or you might archive objects to the S3 Glacier Deep Archive storage class 1 year after creating them.
To learn more about an example S3 Lifecycle configuration, choose each of the three numbered markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/2eed4c93-6bfa-4a01-9818-6a77e6633a49" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/88e96e5f-ba4a-4a31-91d6-9f9b66d141d9" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/f96ac19e-0a23-4fa1-b551-d4d6ff713a95" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/5caa2f89-14f6-4026-b8fb-b505da50ccf3" />

## Use cases
The following situations are candidates for the use of S3 lifecycle configuration rules:
* Periodic logs: If you upload periodic logs to a bucket, your application might need them for a week or a month. After that, you might want to delete them.
* Data that changes in access frequency: Some documents are frequently accessed for a limited period of time. After that, they are infrequently accessed. At some point, you might not need real-time access to them. However, your organization or regulations might require you to archive them for a specific period. After that, you can delete them.
