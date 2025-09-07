# AWS Servers, Serverless, and Scaling Overview

This module covers compute services on AWS, from traditional server hosting to modern serverless and container-based approaches, as well as scaling and name resolution.

---



<details>
<summary>Amazon Elastic Compute Cloud (EC2)</summary>

**What it is:** Virtual servers in the cloud offering full control over operating system and software.  

**Use cases:**
- Hosting dynamic websites and applications.  
- Running legacy workloads.  
- Development and testing environments.  
- Custom applications needing root-level access.  

</details>

---

<details>
<summary>AWS Elastic Beanstalk</summary>

**What it is:** Managed service for deploying applications without managing infrastructure.  

**Use cases:**
- Quickly deploy and manage web apps.  
- Developers who want to focus on code, not servers.  
- Applications requiring auto-scaling, monitoring, and patching built-in.  

</details>

---

<details>
<summary>AWS Lambda</summary>

**What it is:** Serverless compute service that runs code in response to events without provisioning or managing servers.  

**Use cases:**
- Event-driven applications (S3 uploads, DynamoDB streams).  
- APIs with low and variable traffic.  
- Automation tasks and scheduled jobs.  
- Backend processing for mobile/web apps.  

</details>

---

<details>
<summary>Amazon API Gateway</summary>

**What it is:** Fully managed service for creating, publishing, and securing APIs at scale.  

**Use cases:**
- Exposing Lambda functions as APIs.  
- Managing RESTful and WebSocket APIs.  
- Handling authorization, throttling, and monitoring for APIs.  

</details>

---

<details>
<summary>AWS Step Functions</summary>

**What it is:** Orchestration service that coordinates multiple AWS services into workflows.  

**Use cases:**
- Defining workflows for serverless applications.  
- Long-running or multi-step business processes.  
- Automating error handling and retries.  

</details>

---

<details>
<summary>Containers on AWS</summary>

**What it is:** Containerized application hosting using ECS, EKS, or Fargate.  

**Use cases:**
- Microservices architectures.  
- Migrating applications from on-premises Kubernetes/Docker setups.  
- Running scalable, portable container workloads.  

</details>

---

<details>
<summary>Elastic Load Balancing (ELB)</summary>

**What it is:** Distributes incoming traffic across multiple targets (EC2, containers, Lambda).  

**Use cases:**
- High availability and fault tolerance.  
- Scaling web applications horizontally.  
- Routing traffic by path or host (Application Load Balancer).  

</details>

---

<details>
<summary>Amazon EC2 Auto Scaling</summary>

**What it is:** Automatically adjusts the number of EC2 instances based on demand.  

**Use cases:**
- Ensuring application availability during traffic spikes.  
- Reducing costs during low-demand periods.  
- Maintaining performance for variable workloads.  

</details>

---

<details>
<summary>Amazon Route 53</summary>

**What it is:** Scalable and highly available DNS and domain name management service.  

**Use cases:**
- Registering and routing domain names.  
- Failover routing for disaster recovery.  
- Latency-based and weighted routing for global traffic.  

</details>

---

<details>
<summary>Amazon CloudFront</summary>

**What it is:** Global Content Delivery Network (CDN) that caches and delivers content close to users.  

**Use cases:**
- Low-latency delivery of static and dynamic content.  
- Secure delivery of APIs, video, and web apps.  
- Frontend acceleration for global websites.  

</details>

---

<details>
<summary>✅ Labs & Activities Completed</summary>

- [170-[JAWS]-Activity – Create a Website on S3]()  
- [171-[JAWS]-Lab – Creating Amazon EC2 Instances]()  
- [172-[JAWS]-Lab – [Challenge] EC2 Instance Exercise]()  
- [173-[JAWS]-Activity – Troubleshoot Create Instance]() 
- [178-[JAWS]-Activity – Working with AWS Lambda]() 
- [177-[JAWS]-Lab – [Challenge] AWS Lambda Exercise]()
- [174-[JAWS]-Lab – Scale and Load Balance your Architecture]()
- [175-[JAWS]-Lab – Using Auto Scaling in AWS (Linux)]()
- [176-[JAWS]-Activity – Route 53 Failover Routing]() 

</details>
