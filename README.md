# Balint Bende

**Cloud | DevOps | Backend Engineering**

Building cloud infrastructure with a focus on automation, reliability, and clean delivery pipelines.

---

## About

I design, build, and operate cloud infrastructure:

- **Cloud infrastructure** - provisioning and managing environments on AWS and Azure, from networking and compute to managed services
- **Infrastructure as Code** - Terraform for AWS and Azure, reproducible and version-controlled across environments
- **CI/CD pipelines** - GitHub Actions workflows and Azure Pipelines for automated build, test, and deployment
- **Kubernetes** - multi-env cluster design and workload management
- **Backend engineering** - strong development foundation that informs how I design platforms developers actually want to use

## Technology Stack

### Infrastructure & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=fff)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)

### Cloud & CI/CD
![AWS](https://custom-icon-badges.demolab.com/badge/AWS-%23FF9900.svg?logo=aws&logoColor=white)
![Microsoft Azure](https://custom-icon-badges.demolab.com/badge/Microsoft%20Azure-0089D6?logo=msazure&logoColor=white)

### Development
![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)
![F#](https://img.shields.io/badge/F%23-378BBA?logo=fsharp&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?logo=node.js&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=fff)

### Database
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?logo=mongodb&logoColor=white)

## Projects and references

### bimlens - cloud-native BIM platform delivered end-to-end via GitOps

A full-stack platform for extracting and storing building element data from IFC models, built from the browser down to the cluster as infrastructure-as-code and GitOps-driven delivery.

- Cluster-as-a-service infrastructure on Azure AKS, provisioned with Terraform
- GitOps continuous delivery with FluxCD — new images auto-released to the cluster
- Kubernetes workloads packaged and templated with Helm
- ASP.NET Core (.NET 10) REST backend with SOLID controller/service/repository layering
- React 19 + TypeScript frontend with client-side IFC parsing (IFC.js)

**Why this matters:** This is a complete system built the way platforms are run in production, but the full delivery chain from provisioning to release. It demonstrates ownership of the whole stack: infrastructure, deployment automation, and the backend and frontend it serves.

Project repos:
[web](https://github.com/balintbende/bimlens-web)
[api](https://github.com/balintbende/bimlens-api)
[terraform](https://github.com/balintbende/bimlens-terraform)
[helm-charts](https://github.com/balintbende/bimlens-helm-charts)
[flux](https://github.com/balintbende/bimlens-flux)

## Certifications

- Certified Kubernetes Administrator (CKA) ✅

**Roadmap**
- HashiCorp Terraform Associate
- Certified Kubernetes Security Specialist (CKS)
- Certified Kubernetes Application Developer (CKAD)
- Kubernetes and Cloud Native Associate (KCNA)
- Kubernetes and Cloud Native Security Associate (KCSA)
