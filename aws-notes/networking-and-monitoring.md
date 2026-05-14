AWS Networking and Monitoring

VPC

VPC stands for Virtual Private Cloud.
It allows users to create isolated private networks inside AWS.

Features of VPC

- Secure networking environment
- Custom IP address range
- Control over routing and security
- Internet connectivity support


Subnet

Subnet is a smaller network inside a VPC.

Types of Subnets

Public Subnet
Connected to the internet.

Private Subnet
Not directly connected to the internet.


Internet Gateway

Allows communication between VPC and the internet.


Route Table

Controls network traffic inside the VPC.


NACL

NACL stands for Network Access Control List.
Provides subnet-level security.

Features

- Stateless security
- Controls inbound and outbound traffic


Security Group

Provides instance-level security.

Features

- Stateful firewall
- Controls traffic for EC2 instances


Elastic IP

Static public IP address used in AWS.


NAT Gateway

Allows private subnet instances to access the internet securely.


CloudWatch

Monitoring service in AWS.

Functions

- Monitor EC2 performance
- Create alarms
- View metrics and logs


CloudTrail

Tracks AWS account activity and API calls.

Uses

- Security auditing
- Activity tracking
- Compliance monitoring


SNS

Simple Notification Service used for sending alerts and notifications.


SQS

Simple Queue Service used for message queuing between applications.


AWS CLI

Command line tool used to manage AWS resources.

Useful Commands

aws configure
Configures AWS credentials.

aws s3 ls
Lists S3 buckets.

aws ec2 describe-instances
Displays EC2 instance details.


Basic EC2 Connection

ssh -i mykey.pem ec2-user@public-ip

Purpose

Connects securely to a Linux EC2 instance.


Shared Responsibility Model

AWS Responsibility

- Physical infrastructure
- Hardware security
- Network infrastructure

Customer Responsibility

- Data security
- Password management
- Application security
- IAM permissions
