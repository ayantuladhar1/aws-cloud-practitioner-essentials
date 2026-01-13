# Cloud Formation

<img width="256" height="237" alt="image" src="https://github.com/user-attachments/assets/a14546f7-e99f-4bd1-9878-f2eef52ba21d" />

Cloud Formation is a service that helps you model and set up your AWS resources so that you can spend less time managing those resources ad more time focusing on your application that run in AWS. With CloudFormation, you can define your infrastructure as code. You create a template that describes all the AWS resources that you want (like Amazon Elastic Compute Cloud(Amazon EC2) instances), and CloudFormation takes care of provisioning and configure those resources for you.

## Interacting with AWS resources

<img width="1200" height="600" alt="image" src="https://github.com/user-attachments/assets/0249cc98-1f00-4380-8fe1-278a232c58d3" />

* Programmatic access
Programmatic access includes options like AWS CLI and AWS SDKs. These options are best suited for developers and those familiar with coding languages.
With the AWS CLI, you manage multiple AWS services directly from the command line. You can automate tasks through scripts.
AWS SDKs can help integrate AWS services into your applications by providing APIs for various programming languages. AWS provides documentation and sample code to help you get started using SDKs.
* Use cases for AWS CLI actions and SDKs include the following:
  * AWS CLI: Automate routine tasks. For example, you might write a script to provide routine backups for a service such as Amazon Elastic Block Store (Amazon EBS).
  * SDKs: Invoke APIs for one part of an application process. For example, you might use an SDK to store user data in an AWS storage service such as Amazon Simple Storage Service (Amazon S3)
## AWS Management Console
The AWS Management Console is a web interface that you use for managing AWS services, offering quick access to services, search functionality and simplified workflows. The console is a great option for those new to the cloud or users with minimal or no development experience.
* Use cases for using the console include the following:
  * Billing and cost optimization dashboards and visualizations
  * Services focused on graphical representations like Amazon Quick Sight and Amazon Neptune
## Infrastructure as Code
With IaC tools such as CloudFormation, you can automate resource management across your organization with AWS service integrations offering efficient and repeatable resource creation and management.
* Use cases for CloudFormation include the following:
  * Managing infrastructure with DevOps such as continuous integration and delivery (CI/CD) pipelines
  * Scaling resources such as Amazon EC2 instances to multi-Region applicant in a consistent, repeatable way.
