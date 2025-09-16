# Concept: Cloud Service Models

## Deep Reasoning
Service models define the division of management responsibility between the customer and the provider. They represent a trade-off between control and administrative overhead. Security responsibilities shift accordingly.

## Core Analogy: Transportation
- **On-Premises:** Owning and maintaining your own car.
- **IaaS (e.g., EC2, VMs):** Renting a car. You control the driving, provider maintains the vehicle.
- **PaaS (e.g., RDS, Beanstalk):** Taking a taxi. You control the destination, provider controls the driving.
- **FaaS/Serverless (e.g., Lambda):** Taking a bus. You just get on and off; provider manages everything else.
- **SaaS (e.g., Gmail, Office365):** Using the public water system. You just consume the service.

## Hands-On Lab: AWS Console Exploration
**Objective:** Identify services by their model.

**Findings:**
- **IaaS:** EC2 Instances (I manage the OS), EBS Volumes.
- **PaaS:** RDS (AWS manages the database engine, I manage the data), S3 (Storage service).
- **FaaS:** AWS Lambda (I just provide code, AWS manages execution environment).
- **SaaS:** AWS Chime, Amazon.com itself.

**Conclusion:** The console is a mix of IaaS and PaaS. Understanding a service's model is the first step to understanding my security responsibilities for it.
