<div align="center">

# Tanjim Ahmed

### DevOps Engineer | Cloud | SRE

**Building. Automating. Scaling.**

[![GitHub](https://img.shields.io/badge/GitHub-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/tanahmeeedsx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-238636?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tanahmedd/)
[![Portfolio](https://img.shields.io/badge/Portfolio-238636?style=flat-square&logo=netlify&logoColor=white)](https://tanjim-devops-latest-portfolio.netlify.app/)
[![Email](https://img.shields.io/badge/Email-238636?style=flat-square&logo=gmail&logoColor=white)](mailto:tanjimahmed450@gmail.com)
![Open to work](https://img.shields.io/badge/Open%20to%20work-DevOps%20%C2%B7%20Cloud%20%C2%B7%20SRE%20%C2%B7%20Platform-2ea043?style=flat-square)

</div>

---

## About

I design, automate and operate cloud-native infrastructure on AWS. I take code from a commit to a reachable, observable production system: pipelines, containers, clusters, cloud infrastructure, and the debugging that starts when a green pipeline still is not reachable. Every project below is a real pipeline, cluster or server that broke at least once, and I document what broke and how I fixed it.

| | |
|---|---|
| **Role** | Junior DevOps Engineer |
| **Based in** | Mirpur, Dhaka, Bangladesh |
| **Education** | B.Sc. in Computer Science and Engineering (Major in AI), BUBT |
| **Looking for** | DevOps Engineer, Cloud Engineer, SRE and Platform Engineer roles |
| **Contact** | [tanjimahmed450@gmail.com](mailto:tanjimahmed450@gmail.com) |

**What I work on**

- Cloud infrastructure and automation on AWS
- Containers and Kubernetes
- CI/CD pipelines and GitOps
- Monitoring and observability
- DevSecOps and cloud security

---

## Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=aws,terraform,ansible,docker,kubernetes,githubactions,jenkins,git,prometheus,grafana,linux,bash,python,fastapi,flask,react,postgres,redis,nginx,ollama&perline=10"/>
</p>

| Area | Tools |
|---|---|
| **Cloud** | AWS: EC2, S3, IAM, VPC, EKS, ECS Fargate, ECR, Lambda, API Gateway, DynamoDB, CloudFormation, AWS SAM, CloudWatch, SNS, ALB and Auto Scaling |
| **Infrastructure as Code** | Terraform, Ansible, HashiCorp Nomad, CloudFormation, AWS SAM |
| **Containers and Kubernetes** | Docker, Docker Compose, containerd, Minikube, kind, kubeadm, K3s, EKS, Kustomize, Traefik, RBAC |
| **CI/CD and GitOps** | GitHub Actions, GitHub OIDC, Jenkins, Argo CD, Git, GitHub |
| **Monitoring and Observability** | Prometheus, Grafana, Loki, Grafana Alloy, cAdvisor, Node Exporter, AWS CloudWatch |
| **DevSecOps** | Trivy, Docker Scout, CodeQL, secret scanning, least-privilege IAM, SSH hardening |
| **AIOps and LLMOps** | Ollama, MCP, Qwen 2.5, Llama 3.2, OmniRoute, k6, AWS Distributed Load Testing, n8n, Streamlit |
| **Linux and Scripting** | Ubuntu, Bash, Python, boto3, cron, systemd, Nginx, Redis |
| **Development** | FastAPI, Flask, React, Node.js, PostgreSQL, MongoDB, Redis |
| **IT and Systems** | Windows Server 2022, Active Directory, DNS, DHCP, Group Policy, VLANs, hardware and network troubleshooting |

---

## Featured Projects

| Project | Description | Tech |
|---|---|---|
| [**DevConnect**](https://github.com/tanahmeeedsx/end-to-end-microservice-project) | End-to-end microservices platform. 7 microservices on AWS EC2, provisioned with Terraform and run on K3s, delivered by Argo CD GitOps, with Redis async processing, Prometheus, Grafana and Loki observability, and Trivy-driven image fixes. | FastAPI, React, Docker, Terraform, K3s, Argo CD, Prometheus, Grafana, Loki |
| [**DeployWatch**](https://github.com/tanahmeeedsx/k8s-eks-project) | Kubernetes monitoring dashboard on Amazon EKS, deployed by GitHub Actions using GitHub OIDC (no long-lived AWS keys), with namespace-scoped RBAC and a LoadBalancer Service. 3 Deployments and 9 Pods ready across 5 Namespaces. Docker image cut from about 455 MB to 79.2 MB. | Flask, Docker, EKS, GitHub Actions, OIDC, RBAC |
| [**Expense Tracker**](https://lnkd.in/dvFpxMPB) | Dockerized MERN app on AWS with multi-stage builds, custom networks, health checks and Docker Scout and Trivy scanning. Cron-based MongoDB backups to S3, with the latest backup restored into a separate test database and verified. | Docker Compose, Nginx, EC2, S3, IAM |
| [**CloudMentor**](https://github.com/tanahmeeedsx/cloud-mentor) | Serverless AI classroom. Backend on API Gateway, Lambda, S3, DynamoDB and CloudWatch, with React on EC2 and Nginx. Deployed as code with CloudFormation and SAM, and GitHub Actions CI/CD. | Lambda, API Gateway, DynamoDB, S3, SAM |
| [**Kleos**](https://lnkd.in/ddrN9aUq) | MCP-powered, read-only DevOps chatbot that investigates GitHub Actions failures and job logs through MCP tools and a local Qwen 2.5 1.5B model. Under active development. | Python, Streamlit, MCP, Ollama |
| [**DevSecOps Agent**](https://github.com/tanahmeeedsx/devsecops-agent) | Dashboard for container health and Trivy vulnerability scans, with AWS security inspection (SSM, ECS, ECR, Security Groups, S3, IAM) and AI-assisted remediation advice. Under active development. | Trivy, Docker, AWS SSM, ECS, ECR, IAM |

### Additional Hands-on Work

| Project | Highlights |
|---|---|
| [**Incident Management**](https://github.com/tanahmeeedsx/incident-management-v2) | Observability stack with Prometheus, Grafana, Loki, Alloy, Node Exporter and cAdvisor, tested with live traffic and errors |
| **FlashScale** | AIOps load test with 170K users using k6 and AWS Distributed Load Testing, CloudWatch alarms and SNS alerts |
| **Jenkins CI/CD** | Master-agent setup on two EC2 instances with a parameterized declarative pipeline for DEV and PROD |
| **Ansible and Terraform** | One control node and four managed nodes; Terraform on AWS with a VPC, EC2 and an S3 backend |
| **HashiCorp Nomad** | HCL job spec running Nginx with the Docker driver, resource limits and port mapping |
| **AWS Auto Scaling and ALB** | CPU-based scale-out and scale-in with a launch template, Nginx and CloudWatch alarms |
| **Cloud Health Monitor** | Node.js dashboard on ECS Fargate with GitHub Actions CI, ECR and email alerts |
| **Container security fixes** | Docker Scout and Trivy findings cut from 21 to 0; multi-stage build shrank an image from 278 MB to 90.9 MB |
| **Kubernetes with kubeadm** | Two-node EC2 cluster with containerd and Calico, plus Minikube and kind practice |
| **Local LLM orchestration** | Qwen 2.5 and Llama 3.2 on Ollama through OmniRoute and FastAPI; model crashes fixed by tuning concurrency |
| **n8n quiz pipeline** | Baserow, webhook, n8n and Mattermost automation for quiz submissions |
| **Linux hardening** | ED25519-only SSH, tmpfs storage, load testing and cron-based monitoring |
| **Windows Server labs** | Active Directory, DNS, DHCP, Group Policy, file server with FSRM, and SOHO router administration |

Case studies for each project are on my [portfolio](https://tanjim-devops-latest-portfolio.netlify.app/).

---

## Experience

| Organization | Position | Duration |
|---|---|---|
| **Springer Capital** (Remote, Wilmette, Illinois, USA) | DevOps Engineer Intern | Jun 2026 - Nov 2026 |
| **SkyTech Global** (Uttara, Dhaka, on-site) | IT Support | Jan 2026 - May 2026 |
| **SkyTech Global** (Dhaka, part-time) | Junior Executive, Client Support and Help Desk | Oct 2025 - Dec 2025 |
| **BUBT Cultural Club** | Vice President | 2024 - 2025 |
| **BUBT IT Club** | Executive | 2024 - 2025 |
| **BUBT Cultural Club** | Joint Event Secretary | 2023 - 2024 |

**Springer Capital**

- Built an event-driven n8n pipeline (Baserow, webhook, field mapping, Mattermost) and evaluated n8n in a staging environment
- Audited Grafana Loki for high-cardinality labels and documented stream and query impact
- Built a local LLM serving stack (Qwen 2.5, Llama 3.2, Ollama, OmniRoute, FastAPI, Docker) and fixed model crashes by tuning concurrency

**SkyTech Global**

- Diagnosed and resolved hardware, software and network issues for users
- Installed, configured and updated operating systems and applications, and performed system maintenance
- Handled client queries and first-level troubleshooting, coordinating with teams to resolve issues

**BUBT Clubs**

- Led cultural activities, supervised event planning and coordinated the executive committee
- Planned and ran university events: logistics, scheduling and participant communication
- Supported IT programs, technical learning and student engagement

---

## Certifications and Education

| Certification | Issuer | Date |
|---|---|---|
| AWS Cloud Practitioner Essentials | Amazon Web Services | Nov 2026 |
| [Claude 101](https://academy.claude.com/verify/046217e9f803381fe89dfc9105311043) | Anthropic Academy | Nov 2026 |
| DevOps and Cloud Engineering | bongoDev | Aug 2026 |

**B.Sc. in Computer Science and Engineering (Major in AI)**, Bangladesh University of Business and Technology (BUBT), 2022 - 2025

**Research:** *Railway Track Fault Detection and Interpretation using Deep Learning and Explainable AI*, final-year project, published May 19, 2026. DenseNet121 with Grad-CAM explanations, reaching 98% accuracy and 0.9942 AUC on 5,081 images.

---

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=tanahmeeedsx&show_icons=true&theme=merko&hide_border=true&include_all_commits=true"/> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanahmeeedsx&layout=compact&theme=merko&hide_border=true"/>

<img width="95%" src="https://streak-stats.demolab.com?user=tanahmeeedsx&theme=merko&hide_border=true"/>

<br/>

**Automate Infrastructure · Deliver Reliability · Keep Improving**

</div>
