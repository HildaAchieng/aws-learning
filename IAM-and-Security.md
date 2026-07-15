# ☁️ AWS Cloud Practitioner Essentials - Day 6

**Date:** July 2026

---

# 📚 Topics Covered

- AWS Identity and Access Management (IAM)
- IAM Users
- IAM Groups
- IAM Roles
- Multi-Factor Authentication (MFA)
- Principle of Least Privilege

---

# 🔐 AWS Identity and Access Management (IAM)

AWS IAM is a service that helps manage access to AWS resources securely.

### Key Features

- Create users
- Create groups
- Assign permissions
- Create roles
- Enhance security with MFA

### 📝 My Notes

IAM controls **who can access AWS resources** and **what actions they are allowed to perform**.

---

# 👤 IAM Users

IAM Users represent individual people or applications that need access to AWS.

### 📝 My Notes

Each user should have their own login credentials instead of sharing one account.

Example:
- Hilda
- John
- Sarah

Each person gets their own AWS account access.

---

# 👥 IAM Groups

IAM Groups allow multiple users to share the same permissions.

### Example

Developers
- Alice
- Brian
- Carol

All developers receive the same permissions through the group.

### 📝 My Notes

Instead of assigning permissions one user at a time, AWS allows permissions to be managed through groups.

---

# 🎭 IAM Roles

IAM Roles provide temporary permissions to users, applications, or AWS services.

### 📝 My Notes

Roles are useful because they don't require permanent login credentials.

Example:
An EC2 instance can assume an IAM Role to access an S3 bucket securely.

---

# 🔑 Multi-Factor Authentication (MFA)

MFA adds an extra layer of security by requiring more than just a password.

Examples:
- Authentication app
- Security key
- One-time verification code

### 📝 My Notes

Even if someone knows my password, they still cannot log in without the second verification step.

---

# 🛡️ Principle of Least Privilege

Users should only receive the permissions they need to perform their work.

### 📝 My Notes

Giving unnecessary permissions increases security risks.

Example:
A finance employee should not have administrator access if they only need to view billing information.

---

# 💡 Key Takeaways

- IAM controls authentication and authorization.
- Users should have individual accounts.
- Groups simplify permission management.
- Roles provide temporary access.
- MFA significantly improves account security.
- Always follow the Principle of Least Privilege.

---

# 🌍 Real-World Example

Imagine a company office:

- IAM = Security guard
- Users = Employees
- Groups = Departments (HR, IT, Finance)
- Roles = Visitor badges for temporary access
- MFA = Employee ID card + fingerprint scan

This helps me remember how AWS manages security.

---

# 📖 Reflection

Today I learned how AWS secures access to cloud resources. IAM is one of the most important AWS services because it determines who can access resources and what actions they can perform. I also learned why Multi-Factor Authentication and the Principle of Least Privilege are essential for protecting cloud environments.

---

# 🚀 Progress

- [x] Completed Day 6
- [ ] Review IAM concepts
- [ ] Continue to Day 7
