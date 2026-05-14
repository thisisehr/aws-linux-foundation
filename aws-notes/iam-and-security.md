AWS IAM and Security

IAM

IAM stands for Identity and Access Management.
It is used to securely manage access to AWS services and resources.

Features of IAM

- User management
- Group management
- Permission control
- Secure access management


IAM User

Represents an individual user in AWS.

IAM Group

Collection of IAM users with similar permissions.

IAM Role

Temporary access permissions assigned to AWS services or users.

IAM Policy

JSON document that defines permissions.


Types of Policies

Managed Policy
Predefined policy managed by AWS.

Customer Managed Policy
Custom policy created by users.

Inline Policy
Policy directly attached to a user or role.


MFA

MFA stands for Multi-Factor Authentication.
Adds extra security during login.


Root User

Main AWS account with full access permissions.

Best Practices

- Avoid using root account daily
- Enable MFA
- Use strong passwords
- Create IAM users for regular tasks


Password Policy

Used to enforce password security rules.


AWS Shield

Provides protection against DDoS attacks.


AWS WAF

Web Application Firewall used to filter web traffic.


KMS

KMS stands for Key Management Service.
Used for encryption key management.


Secrets Manager

Used to securely store passwords and API keys.


AWS Inspector

Security assessment service used to identify vulnerabilities.


AWS GuardDuty

Threat detection service for AWS accounts and workloads.


AWS Artifact

Provides AWS compliance and security reports.


Principle of Least Privilege

Users should only receive permissions required for their tasks.


CloudTrail

Records API activity and account actions in AWS.


Security Group

Acts as a virtual firewall for EC2 instances.

NACL

Provides subnet-level security for VPC networks.
