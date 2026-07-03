# ☁️ AWS Cloud Practitioner Essentials - Day 3

**03/07:** July 2026

---

## 📚 Topics Covered

- Amazon EC2
- Amazon VPC
- Security Groups
- Elastic IP Addresses
- Auto Scaling (Introduction)

---

## 🖥️ Amazon EC2

Amazon Elastic Compute Cloud (EC2) is a virtual server that allows users to run applications in the AWS Cloud.

### Key Features
- Virtual machines in the cloud
- Scalable computing capacity
- Multiple instance types
- Pay only for what you use

### 📝 My Notes

EC2 is like renting a computer online. Instead of buying physical hardware, I can launch a virtual machine whenever I need one.

---

## 🌐 Amazon VPC

Amazon Virtual Private Cloud (VPC) allows users to create their own isolated network within AWS.

### Key Features
- Private networking
- Control over IP addresses
- Public and private subnets
- Secure communication between resources

### 📝 My Notes

A VPC is like creating my own private office inside a huge building (AWS). I decide who can enter and how everything connects.

---

## 🔒 Security Groups

Security Groups act as virtual firewalls that control inbound and outbound traffic for AWS resources.

### 📝 My Notes

Security Groups decide who is allowed to connect to my EC2 instance.

Example:
- Allow SSH (Port 22)
- Allow HTTP (Port 80)
- Deny everything else unless permitted

---

## 🌍 Elastic IP Address

An Elastic IP is a static public IP address that can be attached to an EC2 instance.

### 📝 My Notes

Normally an EC2 instance's public IP can change after restarting it.

Elastic IP keeps the same address even if the instance changes.

---

## 📈 Auto Scaling

Auto Scaling automatically adds or removes EC2 instances depending on demand.

### 📝 My Notes

Instead of manually creating more servers when traffic increases, AWS can do it automatically.

Example:
- 100 visitors → 1 server
- 10,000 visitors → AWS launches more servers automatically.

---

# 💡 Key Takeaways

- EC2 provides virtual servers in the cloud.
- VPC creates a secure private network.
- Security Groups act like firewalls.
- Elastic IP addresses provide a fixed public IP.
- Auto Scaling improves availability and reduces costs.

---

# 🤔 Questions for Review

- When should I use an Elastic IP?
- What is the difference between a Security Group and a Network ACL?
- How does Auto Scaling decide when to launch new instances?

---

# 🚀 Progress

- [x] Completed Day 3
- [ ] Review notes tomorrow
- [ ] Continue with Day 4
