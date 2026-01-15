# Intoduction to Database

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/b4f82e86-34f2-4580-b8b7-f77cb7172e17" />

AWS offers a wide range of database services to meet various data storage and management needs. These services are designed to be scalable, reliable, and easy to use for businesses of all sizes. AWS database services include options for relational databases, nonrelational databases, in-memory caches, and purpose-built services for use cases like document management.

# AWS shared responsibility model
The AWS shared responsibility model groups services into three categories based on the ownership of administrative tasks. These categories are fully managed, managed, and unmanaged. The AWS services that you will be exploring in this module are primarily fully managed, with a few managed services, and no unmanaged services.
To learn more about how these categories relate to database services, expand the following three categories.

## Fully managed services

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/2a542641-1c89-48c5-ae88-a0030f1fffaa" />

For fully managed services, AWS handles nearly all operational tasks like provisioning, scaling, patching, backups, performance optimization, and security patches. AWS also provides built-in monitoring and metrics. Fully managed AWS database services only require customers to be responsible for designing data structures and managing access controls.

## Managed services

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/f3744792-eef3-4a3e-b103-dcf52345a566" />

With managed database services, AWS handles routine tasks like backups, patching, and hardware provisioning while customers are responsible for database configuration, query optimization, and performance tuning decisions.

## Unmanaged services

<img width="670" height="670" alt="image" src="https://github.com/user-attachments/assets/0e37a9e2-d121-4755-817e-acdd3d44985e" />

With unmanaged databases, customers are responsible for installation, configuration, patching, maintenance tasks, database security, backups, high availability setup, and performance optimization. An example of an unmanaged database in AWS would be a database management system like MySQL installed directly on an Amazon Elastic Compute Cloud (Amazon EC2) instance.
