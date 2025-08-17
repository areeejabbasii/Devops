# What is DevOps?

The first question that came to my mind was: **What is DevOps, and what problem did it solve?**

## Before DevOps
Before DevOps, there was a big gap between **Development** and **Operations** teams:
- Developers wrote the code and then "threw it over the wall" to Operations.  
- Operations had to deploy, run, and maintain it, but often didn’t fully understand the code.  
- This caused delays, bugs, miscommunication, and blame-shifting.  
- Developers wanted to release quickly, while Operations focused on stability — leading to conflicts.  

## With DevOps
DevOps was introduced to bridge this gap by:
- **Collaboration**: Bringing Development and Operations together as one team.  
- **Automation**: Automating builds, testing, integration, and deployment.  
- **Faster Delivery**: Enabling quicker and more reliable releases.  
- **Continuous Feedback**: Improving products through monitoring and quick iteration.  

👉 In short, DevOps makes software delivery **faster, smoother, and more reliable**.
# DevOps Workflow with Tools

This section explains the DevOps pipeline, showing how code flows from developers to deployment and monitoring.

## Workflow Steps

1. **Development (Code Management)**
   - Developers write and push code to **GitHub** for version control.

2. **Build & Continuous Integration**
   - **Jenkins** is used to connect GitHub with the build pipeline.
   - **Maven** is used as a build tool for compiling and managing dependencies.

3. **Testing (Quality Assurance)**
   - Automated testing ensures code quality and catches bugs early.
   - QA teams may use unit testing, integration testing, and automation tools.

4. **Deployment**
   - Applications are deployed into environments using:
     - **Docker** → Containerization  
     - **Kubernetes** → Container orchestration  
     - **Puppet / Ansible** → Configuration management & automation  

5. **Maintenance & Monitoring**
   - After deployment, the system is continuously monitored for performance, uptime, and errors using:
     - **Nagios** → Infrastructure monitoring  
     - **AWS CloudWatch** → Cloud monitoring and logging  

---

## DevOps Pipeline Flow

**GitHub (Code) → Jenkins + Maven (Build) → Testing (QA) → Deployment (Kubernetes, Docker, Puppet, Ansible) → Monitoring (Nagios, CloudWatch)**
