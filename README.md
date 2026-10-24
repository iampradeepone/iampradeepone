<!-- Dynamic Animated Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:3b82f6&height=220&section=header&text=Pradeep%20Kumar&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Senior%20Site%20Reliability%20Engineer%20%7C%20Cloud%20%26%20Distributed%20Systems&descAlignY=58&descSize=18" width="100%" alt="Header Banner" />

  <!-- Typing SVG Animation -->
  <a href="https://github.com/iampradeepone">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Architecting+High-Availability+Cloud+Infrastructure;Automating+Everything+%7C+Terraform+%E2%80%A2+Kubernetes+%E2%80%A2+GitOps;Engineering+for+99.99%25+Uptime%2C+SLOs+%26+Zero-Downtime;Observability%2C+Chaos+Engineering+%26+Self-Healing+Systems" alt="Typing SVG" />
  </a>

  <!-- Status & Social Badges -->
  <p>
    <a href="https://linkedin.com/in/YOUR_LINKEDIN_HANDLE" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:YOUR_EMAIL@example.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/iampradeepone?tab=followers">
      <img src="https://img.shields.io/github/followers/iampradeepone?label=Followers&style=for-the-badge&color=1e293b&logo=github&logoColor=white" alt="GitHub Followers" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=iampradeepone&label=Profile%20Views&color=3b82f6&style=for-the-badge" alt="Profile Views" />
  </p>
</div>

---

### 🖥️ `$ kubectl describe engineer pradeep-kumar`

```yaml
apiVersion: engineering.sre/v1
kind: SeniorSiteReliabilityEngineer
metadata:
  name: pradeep-kumar
  handle: "@iampradeepone"
  location: "Bengaluru, India"
spec:
  corePhilosophy: "Treat operations as a software problem. Automate toil, enforce SLOs, design for failure."
  specializations:
    - Multi-Cloud Infrastructure & Kubernetes Platform Engineering
    - Full-Stack Observability, OpenTelemetry & Prometheus/Grafana
    - GitOps Delivery Pipelines, IaC & Automated Incident Remediation
    - High-Scale Enterprise & Mission-Critical Distributed Systems
  currentFocus:
    - eBPF-based Kernel Observability & Network Security
    - AI-Driven Incident Response (AIOps) & Self-Healing Workflows
    - Kubernetes Operator Development in Go & Python
status:
  availability: "Always open to discussing architecture, reliability, and high-scale engineering"
```

---

### 🏗️ Reference Production Architecture

```mermaid
graph LR
    subgraph GitOps & CI/CD
        A[GitHub Repo] -->|Actions CI| B(Container Registry)
        A -->|Terraform Plan/Apply| C[Cloud Infra]
        B -->|ArgoCD Sync| D{Kubernetes Cluster}
    end

    subgraph Runtime & Service Mesh
        D --> E[Ingress / Envoy]
        E --> F[Microservices Pods]
        F --> G[(Distributed DB / Cache)]
    end

    subgraph Observability & Self-Healing
        F -.->|Metrics & Traces| H[OpenTelemetry / Prometheus]
        H --> I[Grafana / Alertmanager]
        I -.->|Webhook Remediation| J[Automated Runbooks]
        J -.->|Scale / Rollback| D
    end

    style D fill:#1e293b,stroke:#38bdf8,stroke-width:2px,color:#fff
    style H fill:#0f172a,stroke:#f43f5e,stroke-width:2px,color:#fff
    style J fill:#0f172a,stroke:#10b981,stroke-width:2px,color:#fff
```

---

### 🛠️ Production Arsenal

<div align="center">

| Domain | Technologies & Ecosystem |
| :--- | :--- |
| **Cloud & OS** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) ![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| **Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white) ![Istio](https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white) |
| **IaC & GitOps** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white) ![ELK](https://img.shields.io/badge/Elastic_Stack-005571?style=for-the-badge&logo=elastic&logoColor=white) |
| **Code & Scripting** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white) |

</div>

---

### 📌 Featured Blueprints & Engineering Focus

| Area | Architecture & Implementation Focus | Core Stack |
| :--- | :--- | :--- |
| **Multi-Cluster GitOps** | Automated production-grade Kubernetes cluster provisioning, policy enforcement, and zero-downtime deployment pipelines. | `Terraform` `K8s` `ArgoCD` `Helm` |
| **Unified Observability & SLOs** | End-to-end telemetry pipelines with custom exporters, multi-window burn-rate alerts, and distributed tracing. | `Prometheus` `Grafana` `OpenTelemetry` |
| **Self-Healing Automation** | Event-driven remediation scripts, chaos engineering workflows, and automated runbooks to minimize MTTR. | `Python` `Go` `Ansible` `Linux` |

---

### 📊 Live Telemetry & Engineering Metrics

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=iampradeepone&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=c9d1d9&count_private=true" alt="Pradeep's GitHub Stats" />
  <img height="175em" src="https://streak-stats.demolab.com?user=iampradeepone&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=f43f5e&currStreakLabel=38bdf8" alt="GitHub Streak" />
</div>

<div align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=iampradeepone&bg_color=0d1117&color=38bdf8&line=3b82f6&point=ffffff&area=true&hide_border=true" alt="Pradeep's Activity Graph" />
</div>

---

<details>
<summary><b>⚡ Click to expand: My Core SRE Operating Principles</b></summary>
<br>

1. **SLOs Over Gut Feelings:** If an alert doesn't threaten an Error Budget or impact customer-facing SLIs, it shouldn't page an engineer at 2 AM.
2. **Eliminate Toil Recursively:** If an operational task has to be performed manually more than twice, it belongs in a Terraform module, Kubernetes controller, or automated runbook.
3. **Blameless Postmortems:** Outages are systemic failures, never human failures. Every incident is an investment in hardening the architecture.
4. **Immutable Infrastructure:** Servers are cattle, not pets. Patching means redeploying from a verified pipeline.

</details>

<!-- Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,50:1e293b,100:0f172a&height=110&section=footer" width="100%" alt="Footer Banner" />