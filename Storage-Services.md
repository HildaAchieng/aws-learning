# 💾 AWS Cloud Practitioner Essentials - AWS Storage Services

**23:** July 2026

---

# 📚 Topics Covered

- Amazon S3
- Amazon EBS
- Amazon EFS
- Amazon S3 Glacier
- AWS Storage Gateway

---

# 🪣 Amazon Simple Storage Service (Amazon S3)

Amazon S3 is an object storage service used to store and retrieve any amount of data.

### Key Features

- Highly durable
- Scalable
- Secure
- Stores objects inside buckets

### Common Uses

- Website hosting
- Image and video storage
- Data backups
- Application data

### 📝 My Notes

S3 is ideal for storing files that need to be accessed from anywhere.

---

# 💽 Amazon Elastic Block Store (Amazon EBS)

Amazon EBS provides block storage for Amazon EC2 instances.

### Key Features

- Persistent storage
- High performance
- Used with EC2

### 📝 My Notes

EBS acts like a hard drive attached to an EC2 instance.

---

# 📂 Amazon Elastic File System (Amazon EFS)

Amazon EFS provides shared file storage for multiple EC2 instances.

### Key Features

- Shared storage
- Automatically scales
- Supports Linux file systems

### 📝 My Notes

EFS is useful when several EC2 instances need access to the same files.

---

# 🧊 Amazon S3 Glacier

Amazon S3 Glacier is designed for long-term data archiving.

### Key Features

- Very low storage cost
- Long-term backups
- Slower retrieval times

### 📝 My Notes

Glacier is best for files that are rarely accessed but must be kept safely.

Examples:
- Medical records
- Financial archives
- Legal documents

---

# 🔄 AWS Storage Gateway

AWS Storage Gateway connects on-premises storage with AWS cloud storage.

### Key Features

- Hybrid cloud storage
- Secure data transfer
- Supports backups and disaster recovery

### 📝 My Notes

Storage Gateway helps businesses gradually move to the cloud without replacing all their existing storage.

---

# ⭐ Key Takeaways

- S3 = Object storage
- EBS = Block storage for EC2
- EFS = Shared file storage
- Glacier = Low-cost archive storage
- Storage Gateway = Connects on-premises storage to AWS

---

# 🌍 Real-World Example

Imagine a library:

- S3 = Bookshelves for everyday books
- EBS = A student's personal notebook
- EFS = A shared study room where everyone accesses the same books
- Glacier = The archive room in the basement
- Storage Gateway = A bridge connecting two libraries

---

# 📖 Reflection

Today I learned that AWS offers different storage services for different needs. Choosing the right storage service depends on how often data is accessed, whether it needs to be shared, and how quickly it must be retrieved.

---

# 🚀 Progress

- [x] Completed AWS Storage Services
- [ ] Review storage options
- [ ] Continue to the next module
