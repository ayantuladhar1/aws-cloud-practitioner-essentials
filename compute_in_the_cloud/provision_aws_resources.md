# AWS Resource Provision
In AWS, tasks such as launching an EC2 instance, stopping an instance, or modifying instance settings are done through API requests.
API provide predefined methods to interact with manage and configure AWS resources efficiently.
Three main ways to call AWS APIs


# Interacting with AWS services:
All interactions with services are provided by APIs. You can access these API's through three primary methods:

<img width="771" height="286" alt="image" src="https://github.com/user-attachments/assets/4537d241-ee2d-4749-8b5f-abeede31974d" />
	
## AWS Management Console
The AWS Management Console is a web interface for managing AWS Services, offering quick access to services, search functionality, and simplified workflows. With the mobile app, you monitor resources, view alarms, and check billing, supporting multiple logged-in identities at once.
Good for: Users who prefer a visual, easy-to-use interface for managing and configuring AWS services
  
## AWS CLI
With the AWS CLI, you manage multiple AWS services directly from the command line across Windows, macOS, and Linux. You can automate tasks through scripts, such as launching EC2 instances.
Good for: Advanced users and developers who need to automate tasks, script actions, and manage AWS resources efficiently from the command line.
  
## AWS SDK
The AWS SDK simplifies integrating AWS services into your applications by providing APIs for various programming languages. AWS offers documentation and sample code for languages like C++, Java and .NET to help you get started.
Good for: Developers looking to integrate AWS services into their applications using language specific APIs

# Compute and shared Responsibility

<img width="1640" height="1433" alt="image" src="https://github.com/user-attachments/assets/0f35fb79-92d2-497e-a8c6-d7e0be78083a" />

The AWS Shared Responsibility Model outlines the division of duties between the customer and AWS. AWS handles the security of the cloud (hardware and infrastructure), whereas the customer is responsible for security in the cloud (applications, data, and access control).
An unmanaged service like Amazon EC2 requires you to perform all of the necessary security configuration and management tasks. When you deploy an EC2 instance, you are responsible for configuring security, managing the guest operating system (OS), applying updates, and setting up firewalls (security groups). 
