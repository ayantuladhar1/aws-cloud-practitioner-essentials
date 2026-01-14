# Amazon Elastic Block Store (EBS) Data Lifecycle

## EBS Snapshots
EBS snapshots are point-in-time backups of EBS volume. They can be used for disaster recovery, data migration, volume resizing, and for creating consistent backups of production workloads. EBS snapshots are incremental, so they only save the blocks on the volume that have changed after your most recent snapshot.
EBS snapshots can be used to create multiple new volumes, and new volumes created from a snapshot are an exact copy of the original volume at the time the snapshot was taken. Snapshots of EBS volumes are stored redundantly in multiple Availability Zones using Amazon S3.  

## Working with EBS snapshots
In keeping with the AWS shared responsibility model, as the customer, you are responsible for scheduling and managing regular EBS snapshots as part of your backup strategy. This includes monitoring snapshot costs and deleting unnecessary snapshots to avoid excessive charges. You also need to make sure sensitive data within snapshots is encrypted, verify snapshot integrity, and test restoration procedures regularly.
The following illustration shows how EBS snapshots are created from an EBS volume over time. To learn more about how EBS snapshots interact with EBS volumes, choose each of the following three markers.

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/5c3a11e1-3475-49d5-b734-6c58eb2fdf00" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/a5bdbee7-7d8f-4fef-adf7-d50559f2efc0" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/071cfdf1-9283-4865-9804-25ca44c9bdea" />
<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/502f1657-fa72-456b-a31b-4ce0660740f1" />

## Benefits
Review the main benefits of EBS Snapshots and how it improves your data protection strategy in Amazon EBS.
**Data protection and recovery** 
Snapshots enable fast data recovery from corruption, accidental deletion, or system failures using point-in-time backups.
	
**Operational flexibility**  
Snapshots enable operations like cross-Region data migration, volume resizing, volume cloning, and sharing data across AWS accounts.
	
**Cost effective**  
Snapshots use incremental backup technology, storing only changed blocks after the initial backup, reducing storage costs and backup time.

## Amazon Data Lifecycle Manager
You can automate the creation, retention, and deletion of EBS snapshots using Amazon Data Lifecycle Manager. Amazon Data Lifecycle Manager can schedule snapshots during off-peak hours to minimize performance impact and automatically delete outdated backups to control storage costs. It's particularly valuable for large-scale deployments where manual snapshot management would be time-consuming and error-prone.
To learn how you can use Data Lifecycle Manager to create custom EBS Snapshots policies, choose the arrow buttons to display each of the following five steps.

<img width="670" height="550" alt="image" src="https://github.com/user-attachments/assets/a97b34ef-9f0c-47e4-a5c7-d75df996890b" />
<img width="818" height="361" alt="image" src="https://github.com/user-attachments/assets/219a441c-56bd-48b1-84f8-bfdddf0a4677" />
<img width="807" height="324" alt="image" src="https://github.com/user-attachments/assets/3a5121cb-ff12-4458-91d6-dcc742a8bb91" />
<img width="800" height="323" alt="image" src="https://github.com/user-attachments/assets/6886535d-c47a-4e7d-bf11-f2537b39d537" />
<img width="785" height="328" alt="image" src="https://github.com/user-attachments/assets/5ce4178d-213e-48cf-8014-48603ae6c752" />
<img width="808" height="394" alt="image" src="https://github.com/user-attachments/assets/89645737-b22f-4e2a-a296-8a6b3e31000d" />
