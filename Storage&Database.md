## Amazon Simple Storage Service (Amazon S3)
- In object storage, each object consists of data, metadata, and a key.
- The data might be an image, video, text document, or any other type of file.
- Metadata contains information about what the data is, how it is used, the object size, and so on. 
- An object’s key is its unique identifier.

### Types of S3 Storage

#### S3 Standard (can be used for website hosting)
- Durable
- Designed for frequently accessed data
- Stores data in a minimum of three Availability Zones

#### S3 Standard Infrequent Access
- Ideal for infrequently accessed data
- Similar to Amazon S3 Standard but has a lower storage price and higher retrieval price

#### S3 Glacier Flexible Retrieval
- Low-cost storage designed for data archiving
- Able to retrieve objects within a few minutes to hours

#### S3 One Zone-Infrequent Access (S3 One Zone-IA)
- Stores data in a single Availability Zone
- Has a lower storage price than Amazon S3 Standard-IA

#### S3 Intelligent-Tiering
- Ideal for data with unknown or changing access patterns
- Requires a small monthly monitoring and automation fee per object

#### S3 Glacier Instant Retrieval
- Works well for archived data that requires immediate access
- Can retrieve objects within a few milliseconds

#### S3 Glacier Deep Archive
- Lowest-cost object storage class ideal for archiving
- Able to retrieve objects within 12 hours

#### S3 Outposts
- Creates S3 buckets on Amazon S3 Outposts
- Makes it easier to retrieve, store, and access data on AWS Outposts

## Amazon Relational Database Service (Amazon RDS)
- Automated patching
- Backups
- Redundancy
- Failover
- Disaster Recovery

## Amazon Aurora
- Manages relational db options
	- MySQL
	- PostegreSQL
	- 1/ 10th of commercial db price
	- Data replication
	- Up to 15 read replicas
	- Continuous backup to s3
	- Point in time recovery

## Amazon DynamoDB
- is a key-value database service. It delivers single-digit millisecond performance at any scale.
- DynamoDB is serverless, which means that you do not have to provision, patch, or manage servers. 
- As the size of your database shrinks or grows, DynamoDB automatically scales to adjust for changes in capacity while maintaining consistent performance.