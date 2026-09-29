👋 Hi, I'm Shivam
☁️ DevOps / Cloud Engineer

I build and automate cloud infrastructure, CI/CD pipelines, and containerized workloads with a focus on Azure and Infrastructure as Code.

My work focuses on turning:

Code → Infrastructure → CI/CD → Security → Deployment → Operations
🎯 Core Focus
☁️ Microsoft Azure
🏗️ Infrastructure as Code with Terraform
🔄 CI/CD with Azure DevOps & GitHub Actions
🐳 Docker & Containerization
☸️ Kubernetes
🔐 DevSecOps & Infrastructure Security
📊 Monitoring & Troubleshooting
🌐 Azure Networking
🛠️ Tech Stack
☁️ Cloud & Infrastructure






🔄 CI/CD & Automation







🐳 Containers & Kubernetes






🔐 Security & Quality






📊 Monitoring & Tools






🚀 Featured DevOps Projects
☁️ Azure 3-Tier Infrastructure with Terraform

Real-world scenario: Designing repeatable Azure infrastructure for a multi-tier application using Infrastructure as Code.

Architecture
                    Internet
                       │
                       ▼
              ┌─────────────────┐
              │ Application     │
              │ Gateway / LB    │
              └────────┬────────┘
                       │
              ┌────────▼────────┐
              │    Frontend     │
              └────────┬────────┘
                       │
              ┌────────▼────────┐
              │     Backend     │
              └────────┬────────┘
                       │
              ┌────────▼────────┐
              │    Database     │
              └─────────────────┘

             Azure Infrastructure
                     │
       ┌─────────────┼─────────────┐
       │             │             │
      VNet          NSG        Key Vault
       │
    Subnets
Focus Areas
Azure Resource Groups
Virtual Networks & Subnets
NSGs
Virtual Machines
Load Balancing
Key Vault
Azure Monitor
Terraform modules
Remote Terraform state
Environment-based infrastructure
☸️ Kubernetes 3-Tier Application

Real-world scenario: Deploying a containerized multi-tier application on Kubernetes with service discovery, ingress, persistence and autoscaling.

                       Internet
                          │
                          ▼
                       Ingress
                          │
                 ┌────────┴────────┐
                 ▼                 ▼
             Frontend           Backend
                                     │
                                     ▼
                                 Database
Kubernetes Concepts
Deployments
Services
Ingress
ConfigMaps
Secrets
Persistent Volumes
HPA
Health Probes
Namespace isolation
Kubernetes networking
🔄 Terraform CI/CD Pipeline

Infrastructure delivery designed around validation, security and controlled deployment.

                  Git Push / PR
                       │
                       ▼
                Terraform Format
                       │
                       ▼
                    TFLint
                       │
                       ▼
              Infrastructure Scan
                 ┌─────┴─────┐
                 ▼           ▼
              Checkov       tfsec
                 └─────┬─────┘
                       ▼
               Terraform Validate
                       │
                       ▼
                Terraform Plan
                       │
                       ▼
                Manual Approval
                       │
                       ▼
                Terraform Apply
🏢 Azure Landing Zone Lab

Enterprise-style Azure architecture focused on identity, governance and subscription organization.

                     Entra Tenant
                          │
                   Management Group
                          │
              ┌───────────┴───────────┐
              ▼                       ▼
        Platform / Core          Landing Zones
              │                       │
        ┌─────┴─────┐           ┌─────┴─────┐
        ▼           ▼           ▼           ▼
    Networking   Security      Dev         Prod
Focus Areas
Microsoft Entra ID
Management Groups
Azure Subscriptions
Azure RBAC
Governance
Naming standards
Network architecture
Identity & access management
🔐 DevSecOps & Container Security

Security is integrated into the delivery workflow instead of being treated as a final step.

Terraform
   │
   ├── TFLint
   ├── Checkov
   └── tfsec

Application
   │
   ▼
Docker Build
   │
   ▼
Trivy Scan
   │
   ▼
Container Registry
   │
   ▼
Deployment
🧠 DevOps Engineering Approach

I focus on understanding the complete lifecycle, not just individual tools.

        PLAN
          │
          ▼
   INFRASTRUCTURE
          │
          ▼
      AUTOMATION
          │
          ▼
       SECURITY
          │
          ▼
      DEPLOYMENT
          │
          ▼
      MONITORING
          │
          ▼
     TROUBLESHOOTING
          │
          └──────────────► IMPROVEMENT
📚 Currently Deepening
Azure Architecture
Terraform & Infrastructure as Code
Kubernetes Networking
CI/CD Design
Cloud Security
Monitoring & Observability
Enterprise Azure Architecture
📊 GitHub Activity










🌐 Connect With Me







💡 Building infrastructure, automating delivery, securing deployments, and continuously learning.
