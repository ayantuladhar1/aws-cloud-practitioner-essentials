# Protecting Data
## Data encryption
So much of what you do on AWS is driven by data. Keeping your data safe is important to make sure your applications run smoothly and to maintain customer trust.
Encryption is a key component of data protection. Let's review how data encryption works.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/c6b56bf6-d0bb-42e8-b4bc-67500ae1bbba" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/fd9f798c-1521-497a-920d-17531a8b85f8" />

## AWS data protection
AWS has a variety of methods for protecting data. They include built-in data protection for storage options and services specifically designed for enhanced data protection.
Let's review some of the data protection methods. 

## AWS built-in data protection
To learn more about AWS storage options with built-in data protection, choose each of the following flashcards.

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/49ecfc1f-8980-44e9-be8a-29bee5d16a5c" />
<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/825d072d-9851-40fa-aed6-160db8077e2b" />

## AWS data protection services
AWS also offers the following services to help protect your data.

## AWS Key Management Service (AWS KMS)
You can use AWS KMS to create and manage cryptographic keys. These keys can then be used to encrypt and decrypt your data. You can also control the use of keys across a wide range of services and in your applications. For example, you can specify which IAM users and roles can manage keys. Your keys never leave AWS KMS, and you can temporarily disable them so they can no longer be used.
A cryptographic key is a random string of digits used for locking (encrypting) and unlocking (decrypting) data.

## Amazon Macie
With Amazon Macie, you can monitor your sensitive data at rest to make sure it's safe. Macie uses machine learning (ML) and automation to discover sensitive data stored in Amazon S3. You can use Macie to assess your security posture, which is especially helpful for meeting compliance requirements.

## AWS Certificate Manager (ACM)
ACM centralizes the management of your SSL/TLS certificates that provide data encryption in transit. It can be used to protect various AWS services and your connected on-premises resources.
SSL/TLS certificates are used to establish encrypted network connections from one system to another.
