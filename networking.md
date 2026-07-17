# 🌐 AWS Cloud Practitioner Essentials - Networking

**17:** July 2026

---

# 📚 Topics Covered

- Amazon VPC
- Subnets
- Internet Gateway
- Route Tables
- Security Groups
- Network ACLs
- Elastic IP Address

---

# 🌐 Amazon VPC (Virtual Private Cloud)

Amazon VPC allows you to create your own private network inside AWS.

Features:
- Isolated network
- Secure
- Customizable IP address range

### My understanding

A VPC is like my own private office building in the AWS cloud where I control who can enter.

---

## 🏠 Subnets

A subnet is a smaller section of a VPC.

Types:
- Public Subnet
- Private Subnet

### My understanding

A public subnet can connect to the internet.

A private subnet cannot be accessed directly from the internet.

---

## 🌍 Internet Gateway

An Internet Gateway allows resources inside a VPC to communicate with the internet.

### My understanding

Without an Internet Gateway, my EC2 instances cannot access the internet.

---

## 🛣️ Route Tables

Route tables decide where network traffic should go.

Example:
- Local traffic stays inside the VPC.
- Internet traffic goes through the Internet Gateway.

### My understanding

Route tables are like Google Maps for network traffic.

---

## 🔒 Security Groups

Security Groups act as virtual firewalls for AWS resources.

Features:
- Allow inbound traffic
- Allow outbound traffic
- Stateful

### My understanding

Security Groups decide who is allowed to communicate with my EC2 instance.

---

## 🚧 Network ACLs (Access Control Lists)

Network ACLs provide security at the subnet level.

Features:
- Allow and deny rules
- Stateless

### My understanding

Security Groups protect individual servers, while Network ACLs protect entire subnets.

---

## 📍 Elastic IP Address

An Elastic IP is a static public IP address that can be attached to an EC2 instance.

### My understanding

Unlike a normal public IP, an Elastic IP stays the same even after restarting an instance.

---

# ⭐ Key Takeaways

- VPC = Private network in AWS.
- Subnets divide a VPC into smaller networks.
- Internet Gateway provides internet access.
- Route Tables control traffic flow.
- Security Groups protect instances.
- Network ACLs protect subnets.
- Elastic IP provides a permanent public IP.

---

# 📝 Things I Learned Today

- AWS networking keeps cloud resources secure.
- VPC is the foundation of AWS networking.
- Security Groups and Network ACLs work together to improve security.
