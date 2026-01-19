# Preventing Unauthorized Access

## AWS Identity and Access Management (IAM)
## Securely manage identities and access to AWS services and resources.
One of the best ways to prevent security incidents before they happen is through proper permission and access management. With IAM, by default, all actions are denied. You must explicitly grant permission to someone before they can perform any actions in your account.
When you grant permissions, you should provide access only on a need-to-have basis. This concept is called the principle of least privilege.
The principle of least privilege dictates that you should only give people and systems access to what they need and nothing else.
IAM provides users, groups, and roles so you can configure access based on your company’s specific operational and security needs. IAM policies define the needed access for these identities.
To learn more about IAM identities and controls, choose each of the following five numbered markers.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/39f68834-b691-4489-b1f9-32f245f707cb" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/6c33ac16-a188-4075-9790-9ef9705b1585" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/d713ab28-30f5-4079-ace5-f5d3bd2a1167" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/d9bbc227-43a7-4cd9-a10c-7ef6c2a1dbbe" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/1c6ab6a1-3ddd-4e1d-b870-0365981092b4" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/b1c5b097-c22d-4bdd-8d18-a2e19d418533" />

## Additional access management services
Let's examine some additional AWS services that can help you enforce the principle of least privilege across AWS environments. Collectively, these services help streamline the administration of AWS environments while bolstering your security practices.

## AWS IAM Identity Center
IAM Identity Center centralizes identity and access management across AWS accounts and applications. IAM Identity Center can also connect to an existing identity source and provide your workforce with single sign-on access to all your connected AWS services and accounts. This is called federated identity management.

**Federated identity management** is a system that allows users to access multiple applications, services, or domains using a single set of credentials.

## AWS Secrets Manager
Secrets Manager provides a secure way to manage, rotate, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. This helps keep your applications, services, and IT resources safe.
Secrets are confidential or private information intended to be known only to specific individuals or groups. Examples include passwords, database credentials, and API keys.

## AWS Systems Manager
Systems Manager provides a centralized view of nodes across your organization’s accounts and Regions and multi-cloud and hybrid environments. With this service, you can quickly access node information, such as ID and operating system details, and automate registry edits, user management, and security patching.
**Nodes** are connection points in a network, system, or structure.
