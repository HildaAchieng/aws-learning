# ☁️ AWS Cloud Practitioner Essentials - Day 4

**Date:** July 2026

---

# 📚 Topics Covered

- Amazon S3
- Storage Classes
- Object Storage
- Amazon EBS
- Amazon EFS

---

# 🪣 Amazon Simple Storage Service (S3)

Amazon S3 is an object storage service designed to store and retrieve any amount of data from anywhere.

### Key Features
- Highly durable storage
- Scalable
- Secure
- Accessible over the internet
- Pay only for the storage you use

### 📝 My Notes

Amazon S3 stores files as **objects** inside **buckets**.

Examples of files:
- Images
- Videos
- PDFs
- Documents
- Backups

Think of a **bucket** as a folder that holds your files in the cloud.

---

# 📦 S3 Storage Classes

AWS offers different storage classes depending on how often data is accessed.

Examples include:

- S3 Standard
- S3 Intelligent-Tiering
- S3 Standard-IA
- S3 Glacier Instant Retrieval
- S3 Glacier Flexible Retrieval
- S3 Glacier Deep Archive

### 📝 My Notes

Frequently used files should stay in Standard storage.

Old backups can be moved to Glacier to save money.

---

# 💾 Amazon Elastic Block Store (EBS)

Amazon EBS provides block storage for Amazon EC2 instances.

### Key Features

- Persistent storage
- Used as virtual hard drives
- High performance
- Can be backed up using snapshots

### 📝 My Notes

EBS is like attaching a hard drive to a virtual computer (EC2).

---

# 📂 Amazon Elastic File System (EFS)

Amazon EFS provides shared file storage for multiple EC2 instances.

### Key Features

- Shared storage
- Automatically scales
- Accessible from multiple EC2 instances

### 📝 My Notes

Unlike EBS, multiple EC2 servers can access the same files at the same time.

---

# 💡 Key Takeaways

- S3 is used for storing files and objects.
- Buckets contain objects.
- Storage classes help reduce costs.
- EBS acts like a virtual hard drive.
- EFS allows multiple servers to share files.

---

# 🤔 Questions for Review

- When should I use EBS instead of S3?
- Which storage class is best for backups?
- What is the difference between object storage and block storage?

---

# 🚀 Progress

- [x] Completed Day 4
- [ ] Review today's notes
- [ ] Continue to Day 5
