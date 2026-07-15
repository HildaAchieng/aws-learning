# Day 2 - AWS Cloud Practitioner Essentials

## Topics Covered

- AWS Global Infrastructure
- AWS Regions
- Availability Zones (AZs)
- Edge Locations
- AWS Shared Responsibility Model

---

## Key Concepts

### AWS Regions
An AWS Region is a physical geographic location where AWS hosts its data centers. Each Region contains multiple Availability Zones.

### Availability Zones (AZs)
Availability Zones are separate data centers within a Region. They are isolated from each other to improve fault tolerance and high availability.

### Edge Locations
Edge Locations are used by services such as Amazon CloudFront to deliver content to users with lower latency by caching data closer to them.

### AWS Shared Responsibility Model

AWS is responsible for:
- Physical security of data centers
- Hardware
- Networking
- Cloud infrastructure

Customers are responsible for:
- Data
- Identity and Access Management (IAM)
- Operating systems (where applicable)
- Application security
- Security configurations

---

## What I Learned

- A Region contains multiple Availability Zones.
- Using multiple Availability Zones improves application availability.
- AWS secures the cloud infrastructure, while customers secure what they deploy in the cloud.
- Edge Locations help improve performance by serving content closer to users.

---

## Key Takeaways

- High availability is achieved by distributing resources across multiple Availability Zones.
- Understanding the Shared Responsibility Model is essential for cloud security.
- AWS has a global infrastructure designed for reliability, scalability, and performance.

---

## Next Steps

- Continue with the next AWS Cloud Practitioner module.
- Practice identifying AWS services and their use cases.
- Review today's concepts before moving forward.
