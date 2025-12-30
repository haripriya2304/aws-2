# 📦 AWS S3 Lifecycle Policy Implementation

## 📌 Project Overview
This project demonstrates the implementation of an **AWS S3 Lifecycle Policy** to automatically manage objects stored in an S3 bucket. The lifecycle rules help optimize storage costs by transitioning objects between storage classes and deleting them after a defined period.

This project is part of my **cloud portfolio**, showcasing hands-on experience with **AWS storage management and cost optimization**.

---

## 🎯 Objectives
- Understand and implement **S3 Lifecycle Management**
- Automatically transition objects to lower-cost storage classes
- Automatically delete old or unused objects
- Reduce storage cost without manual intervention

---

## 🛠️ AWS Services Used
- Amazon S3  
- S3 Lifecycle Rules  
- AWS Management Console  

---

## 🗂️ Lifecycle Rules Implemented

| Action | Condition |
|------|----------|
| Transition to Standard-IA | After 30 days |
| Transition to Glacier | After 60 days |
| Permanent Deletion | After 180 days |

> 💡 These rules ensure that infrequently accessed data is stored at lower cost and unnecessary data is removed automatically.

---

## ⚙️ Implementation Steps
1. Created an S3 Bucket  
2. Uploaded sample objects (files)  
3. Opened **Management → Lifecycle rules**  
4. Created a new lifecycle rule  
5. Defined object scope (all objects / specific prefix)  
6. Configured transition actions  
7. Configured expiration (delete objects)  
8. Saved and verified the rule  

---

## 🔗 Resource URL
S3 bucket configured with lifecycle policies (private access).
http://project-pro1.s3-website.ap-south-1.amazonaws.com
