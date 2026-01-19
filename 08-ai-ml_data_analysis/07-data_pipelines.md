# Data Pipelines on AWS
## AWS data pipeline services
Let's dive a bit deeper into the AWS services used in a typical AWS data pipeline.

## Data ingestion services

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/497657f0-a6ae-4ff3-b359-c8a08808d9f4" />

Data ingestion involves moving data from source systems into your chosen storage solution. Use real-time ingestion when the data is needed immediately. Use batch ingestion when some latency is tolerable.

## Amazon Kinesis Data Streams
You can use Kinesis Data Streams for real-time ingestion of terabytes of data from applications, streams, and sensors. This serverless service even provides automatic provisioning and scaling in on-demand mode.

## Amazon Data Firehose
Firehose is an option for data ingestion in near real-time. This fully managed service provides automatic provisioning and scaling. It also delivers data within seconds to data lakes, warehouses, and analytics services.

## Data storage services

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/35212926-6c50-4c01-9f35-8070e44e15e9" />

Data can come from many different sources. To gain insights, data is commonly consolidated into a single location. There are two storage options for this. Flexible data lakes store vast amounts of raw data. Alternatively, the more structured data warehouses are optimized for business intelligence.

## Amazon S3
Amazon S3 is a popular choice for data lakes. This object storage service can securely house virtually any amount of structured or unstructured data. Amazon S3 is also fully elastic, automatically scaling as you add and remove data.

## Amazon Redshift
Amazon Redshift is a fully managed data warehouse service that can store petabytes of structured or semistructured data. With the scalability and pay-as-you-go pricing model, organizations can cost-effectively analyze large datasets.

## Data cataloging services

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/bfe06c30-3d0c-4a42-bf02-67f01386644d" />

Cataloging your data with metadata provides an inventory of your organization's data.

## AWS Glue Data Catalog
AWS Glue Data Catalog provides a centralized, scalable, and managed metadata repository that enhances data discovery. It improves the overall efficiency of data pipelines by delivering metadata to various data stores and analytics services.

## Data processing services

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/40533fba-595c-4125-9d5c-9b0e17e9ee7d" />

Data processing services clean and transform your data so it's ready to be analyzed.

## AWS Glue
AWS Glue is a fully managed ETL service that makes data preparation simpler, faster, and cost effective. AWS Glue ETL jobs can use the AWS Glue Data Catalog to access metadata about data sources, which can help inform transformations defined in the ETL script.

## Amazon EMR
Amazon EMR is ideal for large-scale data processing and organizations with existing big data expertise. It automatically handles infrastructure provisioning, cluster management, and scaling. Amazon EMR supports popular big data frameworks like Apache Spark, Apache Hadoop, and Apache Hive.

## Data analysis and visualization services

<img width="900" height="300" alt="image" src="https://github.com/user-attachments/assets/a9ac480b-3a8e-4580-a236-dc938d6168ce" />

Queries and visualization tools help you to develop important insights about your data.

## Amazon Athena
With Athena, you can run SQL queries to analyze data in relational, nonrelational, object, and custom data sources. This fully managed serverless service can access data hosted on Amazon S3, on premises, or even in multi-cloud environments. It offers a cost-effective solution for data analysis because you only pay for the queries you run.

## Amazon Redshift
Amazon Redshift is a fully managed data warehouse solution. Its columnar storage and massively parallel processing architecture make it ideal for analyzing large datasets. You can use it to perform complex SQL queries on large datasets for frequent, high-performance analytical workloads.

## Amazon QuickSight
With QuickSight, both technical and non-technical users can quickly create modern interactive dashboards and reports from various data sources without managing infrastructure. Amazon Q in QuickSight provides natural language queries so business analysts and users can build, discover, and share meaningful insights in seconds.

## Amazon OpenSearch Service
With OpenSearch Service, you can search for relevant content through precise keyword matching or natural language queries. Unified dashboards provide real-time data visualization as you analyze and monitor logs, traces, and metrics for various applications.
