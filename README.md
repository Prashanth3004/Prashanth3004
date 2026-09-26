<div align="center">

# 👋 Hi, I'm Prashanth

### AWS DevOps Engineer | Cloud Infrastructure | Kubernetes | DevSecOps

**Automate → Deploy → Observe → Secure**

Building reliable and scalable cloud infrastructure through
automation, Infrastructure as Code and continuous delivery.

</div>

---

## 👨‍💻 About Me

I'm an **AWS DevOps Engineer with 4+ years of experience** working on
cloud infrastructure, CI/CD automation, containerization and DevSecOps.

My primary focus is building and maintaining reliable infrastructure
using **AWS, Terraform, Docker and Kubernetes**, while improving
software delivery through **Jenkins, GitHub Actions and GitOps practices**.

I enjoy troubleshooting real-world infrastructure problems,
automating repetitive tasks, and continuously improving deployment
and monitoring workflows.

---

## ⚙️ Engineering Stack

<table>
<tr>
<td width="33%" valign="top">

### ☁️ Cloud

- AWS
- EC2
- VPC
- IAM
- S3
- ALB / ELB
- Auto Scaling
- RDS
- EKS
- Fargate
- CloudWatch

</td>

<td width="33%" valign="top">

### 🏗️ Infrastructure

- Terraform
- Terraform Modules
- Ansible
- Linux
- Bash
- Git

</td>

<td width="33%" valign="top">

### 🐳 Containers

- Docker
- Kubernetes
- Amazon EKS
- Helm

</td>
</tr>

<tr>
<td valign="top">

### 🔄 CI/CD

- Jenkins
- GitHub Actions
- Maven
- Argo CD

</td>

<td valign="top">

### 🔐 DevSecOps

- SonarQube
- Trivy
- tfsec
- Secure CI/CD practices

</td>

<td valign="top">

### 📊 Monitoring

- Prometheus
- Grafana
- CloudWatch
- Datadog

</td>
</tr>
</table>

---

# 🚀 DevOps Delivery Architecture

```text
                         SOFTWARE DELIVERY

 Developer
     │
     ▼
  GitHub
     │
     ▼
 ┌───────────┐
 │  Jenkins  │
 │ Build/Test│
 └─────┬─────┘
       │
       ▼
    Docker
       │
       ▼
   AWS ECR
       │
       ▼
 ┌───────────┐
 │    EKS    │
 │ Kubernetes│
 └─────┬─────┘
       │
       ▼
    Argo CD
       │
       ▼
 ┌───────────────┐
 │ Application   │
 │   Workloads   │
 └───────┬───────┘
         │
         ▼
 Prometheus ──► Grafana
         │
         ▼
      Observe
         │
         ▼
 Continuous Improvement
🔄 Delivery Flow

Code → Build → Containerize → Store → Deploy → Observe → Improve

🏗️ Infrastructure as Code

I use Terraform to provision and maintain cloud infrastructure in a
repeatable and version-controlled way.

Terraform
    │
    ├── AWS VPC
    ├── IAM
    ├── EKS
    ├── Node Groups
    ├── S3
    ├── Route 53
    └── Supporting AWS Resources
Infrastructure Principles
Repeatable
    ↓
Automated
    ↓
Version Controlled
    ↓
Consistent
    ↓
Observable
    ↓
Secure
🔐 DevSecOps

Security should be integrated into the delivery lifecycle rather than
treated as a final step.

                       SOURCE CODE
                           │
                           ▼
                     ┌───────────┐
                     │ SonarQube │
                     └─────┬─────┘
                           │
                           ▼
                     ┌───────────┐
                     │   tfsec   │
                     └─────┬─────┘
                           │
                           ▼
                     ┌───────────┐
                     │   Trivy   │
                     └─────┬─────┘
                           │
                           ▼
                      Build / Test
                           │
                           ▼
                     Docker Image
                           │
                           ▼
                       AWS / EKS
Security Tooling
SonarQube — code quality and static analysis
Trivy — container and dependency vulnerability scanning
tfsec — Terraform security analysis
☸️ Kubernetes

My Kubernetes work focuses on deploying, operating and troubleshooting
containerized workloads on Amazon EKS.

Areas of Focus
Kubernetes
    │
    ├── Pods
    ├── Deployments
    ├── Services
    ├── Ingress
    ├── ConfigMaps
    ├── Secrets
    ├── Resource Management
    ├── Autoscaling
    ├── Troubleshooting
    └── Monitoring
Troubleshooting Approach
Problem
   ↓
Identify the failing layer
   ↓
Check Pod / Deployment status
   ↓
Inspect Events
   ↓
Check Logs
   ↓
Validate Configuration
   ↓
Check Resources / Networking
   ↓
Apply the smallest safe change
   ↓
Validate the result
   ↓
Document the Root Cause
📊 Observability

Reliable infrastructure requires visibility into what is happening.

Applications
     │
     ▼
 Kubernetes / AWS
     │
     ├───────────────┐
     ▼               ▼
Prometheus       CloudWatch
     │
     ▼
  Grafana
     │
     ▼
Dashboards / Metrics / Alerts
Monitoring Stack
Prometheus
Grafana
AWS CloudWatch
Datadog
Kubernetes metrics
Infrastructure monitoring
🔄 CI/CD

I focus on making software delivery repeatable and automated.

Developer
    │
    ▼
  GitHub
    │
    ▼
 Jenkins / GitHub Actions
    │
    ├── Build
    ├── Test
    ├── Security Checks
    └── Package
    │
    ▼
 Docker Image
    │
    ▼
 Container Registry
    │
    ▼
 Kubernetes / EKS
CI/CD Technologies
Jenkins
GitHub Actions
Maven
Docker
Argo CD
Git
📦 Featured Engineering Projects

I prefer building a smaller number of practical projects with
meaningful documentation rather than maintaining many incomplete
repositories.

☁️ AWS EKS + Terraform

Infrastructure as Code

A practical AWS infrastructure project demonstrating Terraform-based
provisioning and Kubernetes infrastructure.

Focus:

AWS VPC
IAM
EKS
Node Groups
Terraform modules
Infrastructure lifecycle
Cloud networking

AWS Terraform EKS VPC

🔨 Jenkins + Docker CI/CD

Automated application delivery

A CI/CD implementation demonstrating how source code can be built,
tested and packaged into container images.

Focus:

Jenkins pipelines
Maven
Docker
Build automation
CI/CD troubleshooting

Jenkins Docker Maven CI/CD

☸️ Kubernetes + GitOps

Kubernetes deployment using GitOps practices

A Kubernetes project demonstrating application deployment and
configuration management using GitOps concepts.

Focus:

Kubernetes
Amazon EKS
Argo CD
Helm fundamentals
Deployment configuration

Kubernetes EKS Argo CD Helm

📈 Kubernetes Monitoring

Container and infrastructure observability

A monitoring stack demonstrating how Kubernetes workloads and
infrastructure metrics can be visualized and monitored.

Focus:

Prometheus
Grafana
Kubernetes metrics
Dashboards
Monitoring and troubleshooting

Prometheus Grafana Kubernetes

🧪 DevOps Lab

This is where I experiment with new technologies, automation patterns
and infrastructure concepts.

┌────────────────────────────────────────────┐
│              PRASHANTH'S LAB               │
├────────────────────────────────────────────┤
│                                            │
│ ☁️  AWS Cloud                              │
│     Cloud infrastructure & architecture    │
│                                            │
│ 🏗️  Terraform                             │
│     Infrastructure as Code                 │
│                                            │
│ ☸️  Kubernetes                             │
│     EKS & workload troubleshooting         │
│                                            │
│ 🔄  CI/CD                                  │
│     Jenkins & GitHub Actions               │
│                                            │
│ 🔁  GitOps                                  │
│     Argo CD                                │
│                                            │
│ 🔐  DevSecOps                              │
│     Trivy • SonarQube • tfsec              │
│                                            │
│ 📊  Observability                          │
│     Prometheus • Grafana • CloudWatch      │
│                                            │
└────────────────────────────────────────────┘
🧠 Troubleshooting Mindset

When something breaks, I prefer understanding the failure before
changing the configuration.

Symptom
   ↓
Identify the failing layer
   ↓
Logs / Metrics / Events
   ↓
Validate configuration
   ↓
Reproduce where possible
   ↓
Apply the smallest safe change
   ↓
Validate
   ↓
Document Root Cause
Areas I Troubleshoot
Linux systems
CI/CD pipelines
Kubernetes workloads
Docker containers
AWS infrastructure
Networking
Application availability
Monitoring and alerts
📚 Currently Learning

I'm continuously expanding my knowledge across cloud, platform and
DevOps engineering.

☸️  Advanced Kubernetes
☁️  AWS Cloud Architecture
🏗️  Platform Engineering
🔐  DevSecOps Automation
🤖  AI-assisted DevOps
🎯 Engineering Principles
Infrastructure should be reproducible.

Deployments should be automated.

Configuration should be version controlled.

Failures should be observable.

Security should be integrated.

Automation should reduce repetitive work.

Documentation should explain WHY,
not only HOW.
📊 GitHub Activity
<div align="center">

</div>
🗂️ What You'll Find in My Repositories
Infrastructure
├── Terraform
├── AWS
└── Kubernetes

Automation
├── Jenkins
├── GitHub Actions
└── Bash

Containers
├── Docker
└── Kubernetes / EKS

GitOps
└── Argo CD

Security
├── Trivy
├── SonarQube
└── tfsec

Observability
├── Prometheus
├── Grafana
└── CloudWatch
🤝 Let's Connect
<div align="center">
Cloud • DevOps • Kubernetes • Terraform • DevSecOps

I'm always interested in learning, building and discussing
cloud infrastructure and DevOps engineering.

<br>

LinkedIn: https://www.linkedin.com/in/prashanth-bhaskari

GitHub: @Prashanth3004

</div>
<div align="center">
┌──────────────────────────────────────────────┐
│                                              │
│       AUTOMATE • DEPLOY • OBSERVE            │
│                                              │
│                   • SECURE •                 │
│                                              │
└──────────────────────────────────────────────┘
Thanks for visiting my profile 👋
</div> ```
