# Storage and Archiving Overview

This module covers AWS storage services, their use cases, and how they integrate into workloads.

---

<details>
<summary>Amazon Elastic Block Store (EBS)</summary>

**What it is:** Block-level storage volumes that attach to Amazon EC2 instances.  

**Use cases:**
- Persistent storage for EC2 (retains data after instance stops).  
- Databases and applications needing low-latency, high-performance storage.  
- Snapshots for backup and disaster recovery.  

</details>

---

<details>
<summary>Instance Store</summary>

**What it is:** Ephemeral block storage physically attached to the host machine.  

**Use cases:**
- Temporary data storage for caches, buffers, or scratch data.  
- High-speed storage for workloads where data doesn’t need to persist after instance stop/termination.  

</details>

---

<details>
<summary>Amazon Elastic File System (EFS)</summary>

**What it is:** Fully managed, scalable file storage for use with AWS compute services.  

**Use cases:**
- Shared file system for multiple EC2 instances.  
- Content management systems, web serving, and data analytics.  
- Lift-and-shift enterprise apps requiring shared storage.  

</details>

---

<details>
<summary>Amazon Simple Storage Service (S3)</summary>

**What it is:** Object storage built for scalability, durability, and availability.  

**Use cases:**
- Data lakes and big data analytics.  
- Backup, restore, and disaster recovery.  
- Hosting static websites.  
- Media storage and content distribution.  

</details>

---

<details>
<summary>Amazon S3 Glacier</summary>

**What it is:** Low-cost object storage for long-term archiving and backup.  

**Use cases:**
- Archival of compliance data (medical, financial, legal).  
- Storing backups for months to years.  
- Rarely accessed data that must be retained.  

</details>

---

<details>
<summary>AWS Storage Gateway</summary>

**What it is:** Hybrid cloud storage service bridging on-premises environments with AWS storage.  

**Use cases:**
- Extending on-premises storage to AWS.  
- Backup/archival with S3 or Glacier while maintaining local access.  
- Cloud-based disaster recovery.  

</details>

---

<details>
<summary>AWS Transfer Family & Migration Services</summary>

**What it is:** Fully managed support for SFTP, FTPS, and FTP to transfer data into and out of S3 or EFS.  

**Use cases:**
- Securely migrating large datasets to AWS.  
- Integrating legacy file transfer workflows into cloud storage.  
- Data onboarding from partners or external vendors.  

</details>

---


<details>
<summary>✅ Labs & Activities Completed</summary>
 
- [182 - Lab - Working with Amazon EBS](./labs/lab-182.md) 

</details>