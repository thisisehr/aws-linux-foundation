AWS Networking Services

VPC

VPC stands for Virtual Private Cloud.
It allows users to create isolated networks inside AWS.

Features of VPC

- Secure networking
- Custom IP ranges
- Subnet creation
- Routing control


CIDR

CIDR stands for Classless Inter-Domain Routing.
Used to define IP address ranges in a VPC.

Example

192.168.1.0/24


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

Controls traffic routing inside the VPC.


NAT Gateway

Allows private subnet instances to access the internet securely.


Elastic IP

Static public IP address in AWS.


Security Group

Acts as a stateful virtual firewall for EC2 instances.

Features

- Instance-level security
- Allows inbound and outbound traffic rules


NACL

Network Access Control List used for subnet-level security.

Features

- Stateless firewall
- Controls subnet traffic


VPC Peering

Connects two VPCs privately.


Transit Gateway

Connects multiple VPCs and on-premise networks.


VPN

Secure connection between on-premise network and AWS.


Direct Connect

Dedicated network connection between AWS and data center.


Route 53

AWS DNS web service.

Functions

- Domain management
- Traffic routing
- Health checks


CloudFront

Content Delivery Network service.

Purpose

- Faster content delivery
- Reduced latency
- Global edge locations


DNS

Domain Name System converts domain names into IP addresses.


DHCP

Dynamic Host Configuration Protocol automatically assigns IP addresses.


Public IP

IP address accessible through the internet.

Private IP

Internal IP address used inside a private network.
