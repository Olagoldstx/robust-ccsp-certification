# Domain 1: Cloud Concepts, Architecture & Design

## Concept: Shared Responsibility Model
**Deep Reasoning:** This is the most fundamental concept in cloud security. It defines the division of security tasks between the cloud provider (CSP) and the customer (you). Misunderstanding this leads to critical security gaps.

**Core Analogy: The Cloud as a City**
- **IaaS (Infrastructure as a Service):** Leasing land. You are responsible for the security of everything you build on it (your house, your locks), while the provider is responsible for the underlying infrastructure (utility grid, physical security of the land).
- **PaaS (Platform as a Service):** Renting an apartment. The landlord (provider) manages the building's security, structure, plumbing. You are responsible for your unit's interior and who you let inside.
- **SaaS (Software as a Service):** Booking a hotel room. You are only responsible for your behavior and data within the room. The hotel manages everything else.

## Hands-On Lab: Exploring the Model in AWS
**Objective:** Visually identify provider vs. customer responsibilities in the AWS console.

**Steps:**
1.  Log into the AWS Management Console.
2.  Navigate to **EC2** (IaaS). Note the security warnings: they are your responsibility (Instance Firewall/SG, OS patches).
3.  Navigate to **AWS Lambda** (FaaS, a type of PaaS). Note the interface: you only upload code. AWS manages the OS, execution environment.
4.  Navigate to **Amazon S3** (Storage Service). Note the security settings: Bucket Policy (your responsibility) vs. AWS's infrastructure security (their responsibility).

**Conclusion:** The console itself is designed around this model. The security configurations you *see* are almost always *your* responsibility.
