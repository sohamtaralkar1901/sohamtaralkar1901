<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0c2d48,70:0284c7,100:0d1117&height=140&section=header&text=Soham%20Taralkar&fontSize=44&fontColor=38bdf8&fontAlignY=65&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=680&lines=Cloud+%26+DevOps+Learning+Engineer.;Passionate+about+Automation%2C+IaC+%26+Kubernetes.;AWS+%7C+Docker+%7C+Terraform+%7C+GitOps+%7C+Linux.;Building+Production-Ready+Labs+in+Public.;Learn.+Automate.+Deploy.+Observe.+Repeat." alt="Typing SVG"/>

### ☁️ Cloud & DevOps Learning Engineer | Aspiring SRE & Platform Engineer

*Bridging development and operations by building resilient infrastructure, automating CI/CD pipelines, and mastering cloud-native architectures.*

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/sohamtaralkar1901)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soham-taralkar/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sohamtaralkar1901)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sohamtaralkar1901@gmail.com)
[![Docker](https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/)

<img src="https://komarev.com/ghpvc/?username=sohamtaralkar1901&label=Engineers%20Visited&color=38bdf8&style=flat-square" alt="Soham Taralkar Profile Visitors" />

</div>

---

> [!NOTE]
> **Mission Statement:** Transforming from traditional development to modern **Cloud Native & DevOps Engineering**. Every project in this repository is built following industry-standard GitOps, Infrastructure as Code, and Shift-Left Security practices.

---

## ⚡ Interactive Terminal Preview

```bash
soham@cloud-workstation:~$ neofetch --devops
```
```yaml
Host:              Soham Taralkar (Cloud & DevOps Learning Engineer)
Current Focus:     Hands-on Multi-Cluster Kubernetes & Terraform Blueprints
Cloud Ecosystem:   AWS (Primary), GCP (Learning), Hybrid Bare-Metal
Daily Stack:       Linux (Ubuntu/Arch) · Docker · K8s · Terraform · Helm · Bash
CI/CD & GitOps:    GitHub Actions · ArgoCD · GitLab CI · Docker Compose
Observability:     Prometheus · Grafana · OpenTelemetry · Loki
Security (SecOps): Trivy · SonarQube · HashiCorp Vault · Infracost
Motto:            "Don't just run containers—orchestrate, secure, and monitor them."
Status:            Ready for Cloud / DevOps / SRE Internships & Entry-Level Roles 🚀
```

---

## 🧠 Continuous Learning & Competency Tracker

Here is an honest, real-time snapshot of my active upskilling roadmap in Cloud, DevOps, and Platform Engineering:

| Domain | Core Focus Areas | Progress | Status |
|:-------|:-----------------|:--------:|:------:|
| 🐧 **Linux & Networking** | Bash Scripting, Systemd, Process Mgmt, DNS, TCP/IP, IPtables, SSH | `██████████` 95% | **Solid** |
| 🐳 **Containers & Docker** | Multi-stage Dockerfiles, Distroless images, Docker Compose, Networking | `█████████░` 90% | **Proficient** |
| ⚙️ **CI/CD & Automation** | GitHub Actions workflows, Artifact caching, Reusable actions, Jenkins | `█████████░` 88% | **Proficient** |
| 🏗️ **Infrastructure as Code** | Terraform modules, State management, Terragrunt, Drift detection | `████████░░` 80% | **Active Lab** |
| ☸️ **Kubernetes (K8s)** | Pods, Deployments, Services, Ingress, Helm Charts, RBAC, CKA Prep | `████████░░` 78% | **Daily Focus** |
| ☁️ **AWS Cloud Architecture** | VPC, EKS, RDS, S3, IAM Least-Privilege, CloudWatch, SAA-C03 Prep | `███████░░░` 75% | **In Progress** |
| 📊 **Observability & SRE** | Prometheus metric scraping, Grafana dashboards, Alertmanager, SLOs | `███████░░░` 70% | **Active Lab** |
| 🔄 **GitOps & Mesh** | ArgoCD app-of-apps pattern, Canary rollouts, Istio service mesh | `██████░░░░` 62% | **Exploring** |
| 🛡️ **DevSecOps & FinOps** | Trivy vulnerability scanning, Infracost budgeting, Vault secrets | `██████░░░░` 60% | **Exploring** |

---

## 🚀 Hands-on Labs & Capstone Projects

Below are the end-to-end cloud and DevOps platforms I have architected and deployed during my practical learning journey:

### 1. [KubeScale — Multi-Tier GitOps Kubernetes Platform](https://github.com/sohamtaralkar1901)
> `🚀 Production-Grade Lab` · AWS EKS · ArgoCD · Helm 3 · Istio · Prometheus

```
[Developer Git Push] ➔ [GitHub Actions CI] ➔ [Image Push to ECR] ➔ [ArgoCD Sync] ➔ [AWS EKS Cluster]
```
- Built a multi-tenant microservices deployment on **AWS EKS** managed entirely through **GitOps (ArgoCD)**.
- Packaged full application stacks with custom **Helm 3 charts** supporting dev, staging, and prod overrides.
- Implemented **Istio Service Mesh** for mutual TLS (mTLS) pod-to-pod communication and canary traffic splitting.
- Configured dynamic ingress routing with **NGINX Ingress Controller** and **Cert-Manager** for automated Let's Encrypt TLS certs.

`Kubernetes` `AWS EKS` `ArgoCD` `Helm` `Istio` `Docker` `Terraform` `Prometheus`

---

### 2. [TerraForge — Automated Multi-Environment AWS IaC](https://github.com/sohamtaralkar1901)
> `🛠️ Infrastructure as Code` · Terraform · Terragrunt · AWS VPC · S3 Remote Backend

- Authored reusable, production-ready **Terraform modules** for bootstrapping resilient AWS Landing Zones.
- Configured secure remote state backend using **S3 bucket versioning** with **DynamoDB state locking**.
- Automated validation checks with **TFLint**, **tfsec** security analysis, and **Infracost** for PR cost projection.
- Provisions 3-tier networking: Public/Private subnets, NAT Gateways, Internet Gateway, and Route Tables.

`Terraform` `Terragrunt` `AWS` `VPC` `DynamoDB` `S3` `Infracost` `Bash`

---

### 3. [ZeroOps-Pipeline — End-to-End DevSecOps Continuous Delivery](https://github.com/sohamtaralkar1901)
> `🔒 Shift-Left DevSecOps` · GitHub Actions · Docker · Trivy · SonarQube · Slack Alerts

- Automated multi-stage CI/CD pipeline triggering on pull requests and pushes to main.
- Integrated **SonarQube** for static code quality analysis and test coverage gates.
- Built hardened container images using multi-stage builds and scanned them with **Trivy** for CVE vulnerabilities.
- Automatic image signing using **Cosign** before pushing to registry and notifying team via Slack Webhooks.

`GitHub Actions` `Docker` `Trivy` `SonarQube` `Cosign` `Security` `Slack API`

---

### 4. [ObservaPulse — Full-Stack Telemetry & Monitoring Stack](https://github.com/sohamtaralkar1901)
> `📈 SRE & Monitoring Lab` · Prometheus · Grafana · Node Exporter · Alertmanager · Loki

- Designed a centralized monitoring hub collecting cluster metrics and application logs.
- Configured custom **Grafana dashboards** visualizing Golden Signals: *Latency, Traffic, Errors, and Saturation*.
- Established **Alertmanager rules** sending real-time threshold notifications for CPU throttling, high memory, and container crash-loops.

`Prometheus` `Grafana` `Alertmanager` `Loki` `Node Exporter` `Linux` `Docker`

---

### 5. [CloudSaver — Serverless AWS Cost Optimizer & Janitor](https://github.com/sohamtaralkar1901)
> `💰 Cloud FinOps` · Python · AWS Lambda · Boto3 · CloudWatch Events

- Serverless Python automation bot executing daily via **AWS EventBridge (CloudWatch cron)**.
- Identifies and cleans up orphaned EBS volumes, idle Elastic IPs, and obsolete snapshots to minimize cloud waste.
- Automated scheduled start/stop of non-production EC2 and RDS instances during off-peak weekend hours.

`Python` `AWS Lambda` `Boto3` `EventBridge` `CloudWatch` `FinOps`

---

## 🛠️ The DevOps Engineer Toolbox

<div align="center">

<table>
  <tr>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=aws" width="48" height="48" alt="AWS"/><br>AWS</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=gcp" width="48" height="48" alt="GCP"/><br>GCP</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=azure" width="48" height="48" alt="Azure"/><br>Azure</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=kubernetes" width="48" height="48" alt="Kubernetes"/><br>Kubernetes</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker"/><br>Docker</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=terraform" width="48" height="48" alt="Terraform"/><br>Terraform</td>
  </tr>
  <tr>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=ansible" width="48" height="48" alt="Ansible"/><br>Ansible</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux"/><br>Linux</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=bash" width="48" height="48" alt="Bash"/><br>Bash</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=githubactions" width="48" height="48" alt="GitHub Actions"/><br>GH Actions</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=jenkins" width="48" height="48" alt="Jenkins"/><br>Jenkins</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=gitlab" width="48" height="48" alt="GitLab"/><br>GitLab CI</td>
  </tr>
  <tr>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=prometheus" width="48" height="48" alt="Prometheus"/><br>Prometheus</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=grafana" width="48" height="48" alt="Grafana"/><br>Grafana</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=py" width="48" height="48" alt="Python"/><br>Python</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=go" width="48" height="48" alt="Go"/><br>Go</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=nginx" width="48" height="48" alt="Nginx"/><br>Nginx</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=cloudflare" width="48" height="48" alt="Cloudflare"/><br>Cloudflare</td>
  </tr>
  <tr>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git"/><br>Git</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub"/><br>GitHub</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL"/><br>PostgreSQL</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis"/><br>Redis</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=vscode" width="48" height="48" alt="VS Code"/><br>VS Code</td>
    <td align="center" width="92"><img src="https://skillicons.dev/icons?i=ubuntu" width="48" height="48" alt="Ubuntu"/><br>Ubuntu</td>
  </tr>
</table>

</div>

<br>

**Cloud & Compute**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

**Orchestration & Mesh**
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**IaC & Automation**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-5C4EE5?style=flat-square&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Monitoring & SRE**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

**Security & DevSecOps**
![Trivy](https://img.shields.io/badge/Trivy-0052CC?style=flat-square&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat-square&logo=vault&logoColor=white)
![Infracost](https://img.shields.io/badge/Infracost-00D9FF?style=flat-square&logoColor=black)

---

## 📐 Cloud Architecture & GitOps Delivery Lifecycle

```mermaid
flowchart TD
    subgraph Development ["💻 1. Development & Code"]
        Dev[Engineer Commit] --> GitRepo[GitHub Repository]
    end

    subgraph CI_Pipeline ["🛡️ 2. DevSecOps CI Pipeline"]
        GitRepo --> Lint[Lint & Unit Tests]
        Lint --> Trivy[Trivy Security Scan]
        Trivy --> BuildDocker[Build Distroless Container]
        BuildDocker --> SignCosign[Cosign Image Signing]
        SignCosign --> PushRegistry[Push to Container Registry]
    end

    subgraph CD_GitOps ["🔄 3. Continuous Delivery & GitOps"]
        PushRegistry --> UpdateManifest[Update Manifest Repo]
        UpdateManifest --> ArgoCD[ArgoCD Controller]
        ArgoCD -->|Sync State| K8sCluster[Kubernetes / AWS EKS]
    end

    subgraph Observability ["📊 4. Telemetry & Observability"]
        K8sCluster --> Prom[Prometheus Scraping]
        Prom --> Graf[Grafana Dashboards]
        Prom --> Alert[Alertmanager / PagerDuty]
    end
```

---

## 🎯 Certifications & Professional Milestones

| Certification | Badge / Status | Verification |
|:--------------|:--------------:|:------------:|
| **AWS Certified Solutions Architect – Associate (SAA-C03)** | ![AWS SAA](https://img.shields.io/badge/AWS-SAA--C03-FF9900?style=flat-square&logo=amazon-web-services&logoColor=white) | `In Final Preparation (Exam Scheduled)` |
| **Certified Kubernetes Administrator (CKA)** | ![CKA](https://img.shields.io/badge/CNCF-CKA-326CE5?style=flat-square&logo=kubernetes&logoColor=white) | `Active Practical Hands-on Labs` |
| **HashiCorp Certified: Terraform Associate (003)** | ![Terraform](https://img.shields.io/badge/HashiCorp-Terraform_Associate-7B42BC?style=flat-square&logo=terraform&logoColor=white) | `Completed Practice Labs` |
| **Linux Foundation: Cloud Native Practitioner** | ![CNCF](https://img.shields.io/badge/Linux_Foundation-Cloud_Native-000000?style=flat-square&logo=linux&logoColor=white) | `Completed` |

---

## 📚 Currently Reading & Devops Playbooks

> [!TIP]
> A great engineer never stops reading source docs and technical literature. Here are the playbooks currently on my desk:
- 📖 *The Phoenix Project* & *The DevOps Handbook* by Gene Kim
- 📖 *Kubernetes: Up and Running* by Kelsey Hightower, Brendan Burns, Joe Beda
- 📖 *Site Reliability Engineering (How Google Runs Production Systems)* by Google
- 📖 *Terraform: Up & Running* by Yevgeniy Brikman

---

## 📊 Live GitHub Analytics & Contribution Metrics

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=sohamtaralkar1901&theme=dark&hide_border=true&background=0d1117&stroke=38bdf8&ring=38bdf8&fire=38bdf8&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=8b949e)

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=sohamtaralkar1901&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=c9d1d9" alt="Soham's GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sohamtaralkar1901&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=c9d1d9" alt="Top Languages" />

</div>

---

<div align="center">

### 📈 Activity & Contribution Velocity

<a href="https://github.com/sohamtaralkar1901">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=sohamtaralkar1901&theme=github-dark&hide_border=true&bg_color=0d1117&color=c9d1d9&line=38bdf8&point=38bdf8&area=true&area_color=38bdf8" alt="Soham's contribution activity graph" />
</a>

</div>

---

## 🤝 Connect, Collaborate & Hire

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soham-taralkar/)
[![GitHub](https://img.shields.io/badge/Explore_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sohamtaralkar1901)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sohamtaralkar1901@gmail.com)

*Open to Junior/Associate DevOps, Cloud Engineering, Platform Engineering roles, internships, and open-source collaborations.*

</div>

---

<div align="center">
<sub>Crafted with code, containers, and continuous learning · Soham Taralkar</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0c2d48,70:0284c7,100:0d1117&height=80&section=footer" width="100%"/>
