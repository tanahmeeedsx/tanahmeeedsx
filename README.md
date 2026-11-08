 <div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0f2b50,70:075985,100:0ea5e9&height=260&section=header&text=TANJIM%20AHMED&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=DEVOPS%20ENGINEERING%20%7C%20CLOUD%20%7C%20AUTOMATION%20%7C%20RELIABILITY&descSize=17&descAlignY=57&animation=fadeIn" width="100%" alt="Tanjim Ahmed - DevOps Engineering, Cloud, Automation and Reliability"/>

  <h3>Building Reliable Systems. Automating Everything Possible.</h3>

  <p>
    <img src="https://img.shields.io/badge/COMMIT-0f172a?style=flat-square&logo=git&logoColor=white" alt="Commit"/>
    <img src="https://img.shields.io/badge/BUILD-1d4ed8?style=flat-square&logo=docker&logoColor=white" alt="Build"/>
    <img src="https://img.shields.io/badge/TEST-0891b2?style=flat-square&logo=githubactions&logoColor=white" alt="Test"/>
    <img src="https://img.shields.io/badge/SECURE-6d28d9?style=flat-square&logo=trivy&logoColor=white" alt="Secure"/>
    <img src="https://img.shields.io/badge/DEPLOY-15803d?style=flat-square&logo=amazonaws&logoColor=white" alt="Deploy"/>
    <img src="https://img.shields.io/badge/OBSERVE-0e7490?style=flat-square&logo=grafana&logoColor=white" alt="Observe"/>
  </p>

  <p>
    <a href="https://www.linkedin.com/in/tanahmedd">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="mailto:tanjimahmed450@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://tanjim-ahmed-devops-portfolio.netlify.app">
      <img src="https://img.shields.io/badge/Portfolio-0a1628?style=for-the-badge&logo=googlechrome&logoColor=38bdf8" alt="Portfolio"/>
    </a>
    <a href="https://tanjim-ahmed-devops-portfolio.netlify.app/resume.pdf">
      <img src="https://img.shields.io/badge/Resume-1d4ed8?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"/>
    </a>
  </p>
</div>

<br/>

> I take code from commit to a **reachable, observable production URL**. I ship Dockerized apps through GitHub Actions to AWS, watch them with health checks, logs and alerts, and learn by breaking real systems and fixing them.

<br/>

## At a Glance

| | |
|---|---|
| **Currently** | DevOps Engineer Intern @ **Springer Capital** · Remote (Wilmette, Illinois, USA) |
| **Core** | Linux · Git & GitHub · Docker · CI/CD · AWS · Kubernetes |
| **Building** | **Kleos** (LLM DevOps assistant) · **DevSecOps Agent** |
| **Based in** | Dhaka, Bangladesh |
| **Open to** | DevOps · Cloud · SRE · Platform Engineering |

<br/>

## Story So Far

| When | What |
|---|---|
| **Aug 2026 – Present** | DevOps Engineer Intern @ **Springer Capital**: n8n automation, local LLM serving, Grafana Loki audits |
| **Aug 2026 – Present** | DevOps and Cloud Engineering bootcamp @ **bongoDev** |
| **Nov 2025 – Feb 2026** | Junior Executive @ **SkyTech Solutions** |
| **Dec 2021 – Dec 2025** | B.Sc. in Computer Engineering @ **BUBT** |

<br/>

## Featured Work

| Project | Project |
|---|---|
| ### 🚨 [Incident Manager](https://github.com/tanahmeeedsx/incident-management)<br>MERN incident and on-call tracker on **AWS EC2**. Deployed to Ubuntu 24.04 with Security Groups, SSH key authentication and MongoDB under systemd.<br><br>`AWS EC2` `Ubuntu` `systemd` `MongoDB` `Bash` | ### ☁️ [CloudMentor](https://github.com/tanahmeeedsx/cloud-mentor)<br>Serverless AI classroom. React on EC2 + Nginx, API Gateway + Lambda, S3 and DynamoDB, deployed with AWS SAM through GitHub Actions.<br><br>`AWS Lambda` `API Gateway` `DynamoDB` `S3` `CloudFormation` `GitHub Actions` |
| ### 🐳 [Expense Tracker](https://github.com/tanahmeeedsx/expense-tracker)<br>Dockerized expense app on **AWS EC2**. Multi-stage builds, Docker Compose with custom networks, and MongoDB backups to S3 via cron, restore-tested.<br><br>`Docker` `Docker Compose` `AWS EC2` `S3` `IAM` | ### 📈 [FlashScale](https://github.com/tanahmeeedsx/aiops-flashscale-app)<br>AIOps load-testing platform. A load test reaching **170K users**, with CloudWatch dashboards, alarms and SNS alerts. EC2 provisioned with Terraform.<br><br>`k6` `Terraform` `CloudWatch` `SNS` `NGINX` `Redis` |
| ### 🛡️ [DevSecOps Agent](https://github.com/tanahmeeedsx/devsecops-agent)<br>Container and cloud security platform. Trivy image scans, container health, and AWS inspection across ECS, ECR, Security Groups, S3 and IAM.<br><br>`Trivy` `Docker` `AWS SSM` `ECS` `ECR` `IAM` | ### 🤖 [Kleos · LLM DevOps Assistant](https://github.com/tanahmeeedsx/LLM-chatbot-assistant)<br>MCP-powered chatbot for CI/CD troubleshooting. Investigates GitHub Actions failures and analyzes job logs using a local Qwen 2.5 model via Ollama.<br><br>`Python` `Streamlit` `MCP` `Ollama` `GitHub CLI` |

<br/>

## Incident Log

*Real breakages from my projects, and what they taught me.*

| 🔥 Problem | 🛠️ Fix | 💡 Lesson |
|---|---|---|
| **Deploy failed** on a missing `SAM_STACK_NAME` secret in GitHub Actions | Read the Actions logs, added the missing repository secret, re-ran the deploy | Read the logs before changing code |
| **Backend image** flagged with **21** Docker Scout findings | Removed the bundled npm CLI from the runtime image, rebuilt and rescanned: now **0** in Docker Scout and Trivy | Build tools belong in the builder stage, not production |
| **Backups** with no restore test yet | Restored the latest MongoDB backup into a separate test database and verified every record | A backup is only real after a restore |

<br/>

## What I Work On

| Area | Technologies |
|---|---|
| ☁️ **AWS** | EC2 · ECS Fargate · ECR · Lambda · API Gateway · S3 · DynamoDB · CloudFormation · IAM |
| 🐳 **Containers** | Docker · Docker Compose · Multi-stage builds · Docker Scout |
| ⎈ **Kubernetes** | Minikube · Kind · kubeadm · Pods · Deployments · Services · Ingress · YAML manifests |
| 🛡️ **DevSecOps** | Trivy · CodeQL · npm audit · Secret scanning · Least-privilege IAM |
| 📈 **AIOps & Observability** | k6 load testing · CloudWatch alarms · SNS · Grafana · Loki · Prometheus |
| 🤖 **AI Agents** | MCP · Ollama · Qwen 2.5 · Llama 3.2 · FastAPI · Streamlit |
| 🔄 **CI/CD & Automation** | GitHub Actions · n8n · Terraform · Bash · systemd |

<br/>

## Tech Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,git,github,linux,bash,grafana,prometheus,py,fastapi,nodejs,go,mongodb,redis,nginx&perline=10" alt="Tech stack"/>
</p>

<br/>

## Open Source & Streak

<p align="center">
  <a href="https://github.com/bongodev/git-and-github">
    <img src="https://img.shields.io/badge/%E2%AD%90_Contributor-bongodev%2Fgit--and--github-38bdf8?style=for-the-badge&logo=github&logoColor=white" alt="Contributor to bongodev/git-and-github"/>
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=tanahmeeedsx&theme=dark&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub streak stats"/>
</p>

<br/>

## Let's Build Something Reliable

Looking for **DevOps, Cloud, SRE and Platform Engineering** roles where I can ship, operate and improve production systems, and automate the parts that keep them up at 3 a.m.

<div align="center">

  <a href="https://www.linkedin.com/in/tanahmedd">
    <img src="https://img.shields.io/badge/-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/>
  </a>
  <a href="mailto:tanjimahmed450@gmail.com">
    <img src="https://img.shields.io/badge/-Say%20Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Say hello by email"/>
  </a>
  <a href="https://tanjim-ahmed-devops-portfolio.netlify.app/resume.pdf">
    <img src="https://img.shields.io/badge/-View%20Resume-1d4ed8?style=for-the-badge&logo=readthedocs&logoColor=white" alt="View resume"/>
  </a>

  <br/><br/>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,35:075985,70:0f2b50,100:020617&height=190&section=footer&text=SHIP%20WITH%20CONFIDENCE.&fontSize=34&fontColor=ffffff&fontAlignY=42&desc=AUTOMATE%20%7C%20SECURE%20%7C%20OBSERVE%20%7C%20SCALE&descSize=15&descAlignY=62&animation=fadeIn" width="100%" alt="Ship with confidence - Automate, Secure, Observe, Scale"/>

</div>
