EC2 and EBS Notes

EC2

EC2 stands for Elastic Compute Cloud.
It provides virtual servers in AWS.

Features of EC2

- Scalable virtual servers
- Multiple operating systems support
- Remote access using SSH
- Flexible storage and networking

EC2 Instance Types

General Purpose
Balanced compute, memory, and networking.

Compute Optimized
Used for high performance processing.

Memory Optimized
Used for memory-intensive applications.

Storage Optimized
Used for high disk performance workloads.


EC2 Instance Lifecycle

Pending
Instance is launching.

Running
Instance is active.

Stopping
Instance is shutting down.

Stopped
Instance is stopped.

Terminated
Instance is permanently deleted.


Security Group

Acts as a virtual firewall for EC2 instances.

Functions

- Controls inbound traffic
- Controls outbound traffic
- Allows specific ports and IP addresses


Key Pair

Used for secure login into EC2 instances.

Public Key
Stored in AWS.

Private Key
Stored with the user.


EBS

EBS stands for Elastic Block Store.
It provides persistent storage for EC2 instances.

Features of EBS

- Persistent storage
- High availability
- Supports snapshots
- Can be attached or detached from instances

EBS Volume Types

gp2 / gp3
General purpose SSD volumes.

io1 / io2
High performance SSD volumes.

st1
Throughput optimized HDD.

sc1
Cold HDD storage.


Snapshot

Backup copy of an EBS volume.

Advantages

- Data backup
- Disaster recovery
- Volume restoration


Attach Volume

Used to connect EBS storage to EC2 instances.

Detach Volume

Used to remove EBS storage from EC2 instances safely.
