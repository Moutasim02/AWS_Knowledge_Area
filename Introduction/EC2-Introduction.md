# Amazon EC2 instance types

- General purpose instances
- Compute optimized instances
- Memory optimized instances
- Accelerated computing instances (e.g: game servers)
- Storage optimized instances

# Amazon EC2 pricing

- On-Demand
- Reserved Instances
- EC2 Instance Savings Plans
- Spot Instances
- Dedicated Hosts

# Amazon EC2 Scaling

Ec2 instances autoscales either dynamically or predictively.
- Dynamic scaling responds to changing demand. 
- Predictive scaling automatically schedules the right number of Amazon EC2 instances based on predicted demand.

Amazon has its own load balancer implementation called "Elastic Load Balancer"


So this is how it works:

- A group of EC2 services are up and running -> EC2 group
- They scale horizontally for increasing demand.
- Load balancer route clients to specific servers/ instances.

# Messaging Queue

Loosely coupled architecture, using a buffer between two services/ applications, AWS Equivalent services are:

- Amazon Simple Queue Service (Amazon SQS) : Data inside messages are called payloads
- Amazon Simple Notification Service (Amazon SNS) : Uses publish/ subscribe architecture, its a channel for messages to be delivered.

# Other Computing Options: 

- Using Serverless -> e.g: AWS Lambda 
	- AWS Lambda, lets you run code without needing to manage servers. While using AWS Lambda, you pay only for the compute time that you consume.
	

- Container Services (Container orchestration tools for managing docker containers)
	- Amazon Elastic Container Service (ECS)
	- Amazon Elastic Kubernetes Service (EKS)
	- AWS Fargate : Manages orchistration tools rather than having yourself managing the EC2 instances.





