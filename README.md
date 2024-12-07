# AWS-Networking

 Networking
 
VPC (Subnets, Route Tables, NAT Gateway, Internet Gateway)

	• Concepts:
		○ VPC: A private, isolated section of the AWS cloud for resources.
		○ Subnets: Logical division of VPC for public/private access.
		○ Route Tables: Rules for directing traffic within the VPC.
		○ NAT Gateway: Allows private instances to access the internet without being publicly accessible.
		○ Internet Gateway: Enables internet access for public-facing resources.
	• Real-Time Example:
		○ A SaaS company deploys a web app in a VPC with public subnets for app servers and private subnets for databases using NAT Gateway.
	• Use Cases:
		○ Public Subnet: Hosting public-facing web servers.
		○ Private Subnet: Hosting sensitive back-end resources.
	• Secondary Options: GCP VPC, Azure VNet.

Security Groups and NACLs

	• Concepts:
		○ Security Groups: Virtual firewalls at the instance level.
		○ NACLs (Network ACLs): Subnet-level stateless firewalls.
	• Real-Time Example:
		○ Security Groups: Limiting access to a web server only to HTTP/HTTPS traffic.
		○ NACLs: Blocking a specific IP range at the subnet level for added security.
	• Use Cases:
		○ Security Groups: Fine-grained, instance-level access control.
		○ NACLs: Broad, subnet-level rules for securing traffic.
