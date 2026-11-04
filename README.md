<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=000000&height=220&section=header&text=Tanjim%20Ahmed&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Automating%20Reliable%20Infrastructure%20at%20Scale&descSize=20&descAlignY=60&animation=fadeIn" alt="Tanjim Ahmed - Automating Reliable Infrastructure at Scale" width="100%" />

<a href="https://github.com/tanahmeeedsx">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1400&color=000000&center=true&vCenter=true&width=780&height=40&lines=DevOps+Engineer+Intern+%40+Springer+Capital+%7C+Wilmette%2C+Illinois%2C+USA;Automate+%C2%B7+Deploy+%C2%B7+Observe+%C2%B7+Secure;AWS%2C+Docker%2C+Kubernetes%2C+DevSecOps%2C+AIOps+and+AI+Agents" alt="Typing animation" />
</a>

<br/>

<a href="https://www.linkedin.com/in/tanahmedd"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:tanjimahmed450@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://tanjim-ahmed-devops-portfolio.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0a1628?style=for-the-badge&logo=googlechrome&logoColor=38bdf8" alt="Portfolio" /></a>
<a href="https://tanjim-ahmed-devops-portfolio.netlify.app/resume.pdf"><img src="https://img.shields.io/badge/Resume-1d4ed8?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume" /></a>

</div>

<br/>

> I take code from commit to a **reachable, observable production URL**. I ship Dockerized apps through GitHub Actions to AWS, watch them with health checks, logs and alerts, and learn by breaking real systems and fixing them.

<br/>

## At a Glance

| | |
| :--- | :--- |
| **Currently** | DevOps Engineer Intern @ **Springer Capital** · Remote (Wilmette, Illinois, USA) |
| **Core** | Linux · Git & GitHub · Docker · CI/CD · AWS · Kubernetes |
| **Building** | **Kleos** (LLM DevOps assistant) · **DevSecOps Agent** |
| **Based in** | Dhaka, Bangladesh |
| **Open to** | DevOps · Cloud · SRE · Platform Engineering |

<br/>

## Story So Far

| When | What |
| :--- | :--- |
| **Aug 2026 – Present** | DevOps Engineer Intern @ **Springer Capital**: n8n automation, local LLM serving, Grafana Loki audits |
| **Aug 2026 – Present** | DevOps and Cloud Engineering bootcamp @ **bongoDev** |
| **Nov 2025 – Feb 2026** | Junior Executive @ **SkyTech Solutions** |
| **Dec 2021 – Dec 2025** | B.Sc. in Computer Engineering @ **BUBT** |

<br/>

## The Pipeline I Ship With

```mermaid
flowchart LR
    A(["git push"]) --> B{{"GitHub Actions<br/>lint · test · scan"}}
    B -- "fail" --> X(["Blocked + email alert"])
    B -- "pass" --> C["Docker build"]
    C --> D[("Amazon ECR")]
    D --> E["ECS Fargate / EC2"]
    E --> F(["CloudWatch + SNS"])
```

<br/>

## Featured Work

<table>
<tr>
<td width="50%" valign="top">

### 🚨 [Incident Manager](https://github.com/tanahmeeedsx/incident-management)
MERN incident and on-call tracker on **AWS EC2**. Deployed to Ubuntu 24.04 with Security Groups, SSH key auth and MongoDB under systemd.

`AWS EC2` `Ubuntu` `systemd` `MongoDB` `Bash`

</td>
<td width="50%" valign="top">

### ☁️ [CloudMentor](https://github.com/tanahmeeedsx/cloud-mentor)
Serverless AI classroom. React on EC2 + Nginx, API Gateway + Lambda, S3 and DynamoDB, deployed with AWS SAM through GitHub Actions.

`AWS Lambda` `API Gateway` `DynamoDB` `S3` `CloudFormation` `GitHub Actions`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐳 [Expense Tracker](https://github.com/tanahmeeedsx/expense-tracker)
Dockerized expense app on **AWS EC2**. Multi-stage builds, Docker Compose with custom networks, and MongoDB backups to S3 via cron, restore-tested.

`Docker` `Docker Compose` `AWS EC2` `S3` `IAM`

</td>
<td width="50%" valign="top">

### 📈 [FlashScale](https://github.com/tanahmeeedsx/aiops-flashscale-app)
AIOps load-testing platform. A load test reaching **170K users**, with CloudWatch dashboards, alarms and SNS alerts. EC2 provisioned with Terraform.

`k6` `Terraform` `CloudWatch` `SNS` `NGINX` `Redis`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [DevSecOps Agent](https://github.com/tanahmeeedsx/devsecops-agent)
Container and cloud security platform. Trivy image scans, container health, and AWS inspection across ECS, ECR, Security Groups, S3 and IAM.

`Trivy` `Docker` `AWS SSM` `ECS` `ECR` `IAM`

</td>
<td width="50%" valign="top">

### 🤖 [Kleos · LLM DevOps Assistant](https://github.com/tanahmeeedsx/LLM-chatbot-assistant)
MCP-powered chatbot for CI/CD troubleshooting. Investigates GitHub Actions failures and analyzes job logs using a local Qwen 2.5 model via Ollama.

`Python` `Streamlit` `MCP` `Ollama` `GitHub CLI`

</td>
</tr>
</table>

<br/>

## Incident Log

*Real breakages from my projects, and what they taught me.*

| 🔥 Problem | 🛠️ Fix | 💡 Lesson |
| :--- | :--- | :--- |
| **Deploy failed** on a missing `SAM_STACK_NAME` secret in GitHub Actions | Read the Actions logs, added the missing repository secret, re-ran the deploy | Read the logs before changing code |
| **Backend image** flagged with **21** Docker Scout findings | Removed the bundled npm CLI from the runtime image, rebuilt and rescanned: now **0** in Docker Scout and Trivy | Build tools belong in the builder stage, not production |
| **Backups** with no restore test yet | Restored the latest MongoDB backup into a separate test database and verified every record | A backup is only real after a restore |

<br/>

## What I Work On

| | |
| :--- | :--- |
| ☁️ **AWS** | EC2 · ECS Fargate · ECR · Lambda · API Gateway · S3 · DynamoDB · CloudFormation · IAM |
| 🐳 **Containers** | Docker · Docker Compose · multi-stage builds · Docker Scout |
| ⎈ **Kubernetes** | Minikube · Kind · kubeadm · Pods · Deployments · Services · Ingress · YAML manifests |
| 🛡️ **DevSecOps** | Trivy · CodeQL · npm audit · secret scanning · least-privilege IAM |
| 📈 **AIOps & Observability** | k6 load testing · CloudWatch alarms · SNS · Grafana · Loki · Prometheus |
| 🤖 **AI Agents** | MCP · Ollama · Qwen 2.5 · Llama 3.2 · FastAPI · Streamlit |
| 🔄 **CI/CD & Automation** | GitHub Actions · n8n · Terraform · Bash · systemd |

<br/>

## Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,git,github,linux,bash,grafana,prometheus,py,fastapi,nodejs,go,mongodb,redis,nginx&perline=10" alt="Tech stack" />
</p>

<br/>

## Open Source & Streak

<p align="center">
  <a href="https://github.com/bongodev/git-and-github"><img src="https://img.shields.io/badge/%E2%AD%90_Contributor-bongodev%2Fgit--and--github-38bdf8?style=for-the-badge&logo=github&logoColor=white" alt="Contributor to bongodev/git-and-github" /></a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=tanahmeeedsx&theme=dark&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub streak stats" />
</p>

<br/>

## Let's Build Something Reliable

Looking for **DevOps, Cloud, SRE and Platform Engineering** roles where I can ship, operate and improve production systems, and automate the parts that keep them up at 3 a.m.

<div align="center">

<a href="https://www.linkedin.com/in/tanahmedd"><img src="https://img.shields.io/badge/-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="mailto:tanjimahmed450@gmail.com"><img src="https://img.shields.io/badge/-Say%20Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Say hello by email" /></a>
<a href="https://tanjim-ahmed-devops-portfolio.netlify.app/resume.pdf"><img src="https://img.shields.io/badge/-View%20Resume-1d4ed8?style=for-the-badge&logo=readthedocs&logoColor=white" alt="View resume" /></a>

<br/><br/>

<sub>🛠️ <b>Build it. Ship it. Watch it. Improve it.</b></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a1628,55:1d4ed8,100:38bdf8&height=120&section=footer" alt="" width="100%" />

</div>
