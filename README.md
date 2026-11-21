<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_colors=%230f2027,%23203a43,%232c5364&height=230&section=header&text=Deepak%20Singh&fontSize=42&fontColor=ffffff&animation=twinkling&desc=Staff%20DevOps%20Architect%20%7C%20Cloud%20Platform%20Engineer%20%7C%20SRE&descSize=18&descAlignY=68" width="100%" alt="Header Banner" />

<!-- Dynamic Typing Subtitle -->
<a href="https://github.com/dspkla">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=00F0FF&center=true&vCenter=true&width=780&lines=Staff+DevOps+%26+Cloud+Platform+Architect;Enterprise+Kubernetes+%26+Multi-Cloud+Infrastructure;GitOps+%7C+Zero-Downtime+Continuous+Delivery;Shift-Left+DevSecOps+%26+Supply+Chain+Attestation;Architecting+99.999%25+Reliable+Self-Healing+Platforms;FinOps+Cloud+Cost+Optimization+%26+Chaos+Engineering" alt="Typing SVG" />
</a>

<br/>

<!-- Status Badges -->
[![Profile Views](https://komarev.com/ghpvc/?username=dspkla&label=PROFILE+VIEWS&style=for-the-badge&color=00c853)](https://github.com/dspkla)
[![Consulting & Advisory](https://img.shields.io/badge/Consulting-Open%20for%20Engagements-blue?style=for-the-badge&logo=googlecalendar&logoColor=white)](mailto:dspkla@users.noreply.github.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Deepak%20Singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub Repositories](https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dspkla?tab=repositories)

<p align="center">
  <a href="#-executive-profile--philosophy"><b>Executive Profile</b></a> •
  <a href="#-elite-dora-metrics--operational-sla"><b>DORA Metrics</b></a> •
  <a href="#-enterprise-devops-architecture-matrix"><b>Architecture</b></a> •
  <a href="#-devops--cloud-technology-arsenal"><b>Tech Arsenal</b></a> •
  <a href="#-flagship-devops-solutions"><b>Flagship Solutions</b></a> •
  <a href="#-certifications--credentials"><b>Certifications</b></a> •
  <a href="#-telemetry--github-metrics"><b>Telemetry</b></a> •
  <a href="#-connect--consulting"><b>Contact</b></a>
</p>

</div>

---

## 🌐 Executive Profile & Philosophy

I architect and deliver **self-healing, zero-trust cloud platforms** and **ultra-high-velocity GitOps pipelines** designed to survive multi-region outages, eliminate deployment friction, and automate compliance from code commit to container runtime.

### 🏛️ Core Architectural Tenets
* **Declarative & Immutable:** If an asset is not declared in Git, it does not exist in production. Servers drift; containers get replaced.
* **Continuous GitOps Delivery:** Eliminating manual deployments via pull-based reconciliation (ArgoCD), canary rollouts, and automatic rollback triggers.
* **Shift-Left Zero Trust:** Security is an integrated pipeline gate—SAST, SCA, container signing (Cosign), SBOM generation, and eBPF runtime observability.
* **FinOps & Elasticity:** Cloud spending governed through automated node autoscaling (Karpenter), spot orchestration, and Infracost PR cost-diff checks.

---

## ⚡ Elite DORA Metrics & Operational SLA

| Engineering Metric | Industry Benchmark | My Architectural Standard | Production Mechanism |
| :--- | :--- | :--- | :--- |
| **Deployment Frequency** | Weekly / Monthly | **On-Demand (Multiple / Day)** | GitOps pull-based synchronization & automated trunk-based CI/CD |
| **Lead Time for Changes** | 1 to 4 Weeks | **< 15 Minutes** | Highly optimized parallel caching, rootless Docker Buildx & ephemeral environments |
| **Mean Time to Recovery (MTTR)** | Hours to Days | **< 10 Minutes** | Argo Rollouts automated metric-driven abort, health probes & instant state rollback |
| **Change Failure Rate (CFR)** | 15% – 30% | **< 0.5%** | Pre-flight policy gates (Checkov/Kyverno), automated smoke tests & canary analysis |
| **Platform Availability SLA** | 99.9% (Three Nines) | **99.999% (Five Nines)** | Multi-AZ private topologies, graceful zero-downtime draining & health checking |
| **Cloud Cost Optimization** | Unmanaged sprawl | **35% – 45% Reduction** | Karpenter dynamic right-sizing, Spot/Graviton instances & Infracost PR gates |

---

## 🔬 Enterprise DevOps Architecture Matrix

```text
  [ Developer Workspace ]
            │
            ├─► Pre-commit Hooks: Gitleaks (Secret Detection) + ShellCheck + TFLint
            ▼
  [ Continuous Integration Plane (GitHub Actions) ]
            │
            ├─► SAST (Static Code Analysis)    ──► Semgrep / SonarQube
            ├─► Secret Scanning                ──► TruffleHog / GitGuardian
            ├─► SCA (Software Composition)     ──► Aqua Trivy / Snyk
            ├─► IaC Security & Policy Check    ──► Checkov / tfsec / TFLint
            ├─► Multi-Stage Container Build    ──► Docker Buildx (Rootless & Distroless)
            ├─► Container Layer Vulnerability  ──► Aqua Trivy / Grype
            ├─► SBOM Generation                ──► Syft (SPDX / CycloneDX Standards)
            └─► Cryptographic Attestation      ──► Sigstore / Cosign Keyless Image Signing
            │
            ▼
  [ Secure Artifact & Delivery Plane ]
            │
            ├─► OCI Image Registry             ──► Amazon ECR / GitHub Container Registry (Immutable Tags)
            ├─► Declarative State Sync         ──► ArgoCD GitOps Engine (Self-Healing & Drift Remediation)
            ├─► Admission Controller Gate      ──► Kyverno / OPA Gatekeeper (Enforces Cosign Signatures)
            └─► Progressive Rollout Engine     ──► Argo Rollouts (Automated Canary Analysis & Instant Rollback)
            │
            ▼
  [ Multi-Cluster Runtime Plane (AWS EKS / Multi-AZ) ]
            │
            ├─► Network Microsegmentation      ──► Cilium (eBPF-driven Zero Trust & L7 Network Policies)
            ├─► Runtime Kernel Threat Defense  ──► Falco (Syscall Anomaly & Privilege Escalation Detection)
            ├─► Dynamic Cluster Autoscaler     ──► Karpenter (Just-in-Time Graviton & Spot Provisioning)
            ├─► Continuous CIS & CSPM Audits   ──► Prowler / Trivy Operator
            └─► Observability & Distributed SRE──► Prometheus, Grafana, OpenTelemetry, Loki & Alertmanager
```

---

## 🧰 DevOps & Cloud Technology Arsenal

<div align="left">

### ☁️ Cloud Platforms & Core Services
![AWS](https://img.shields.io/badge/AWS-Enterprise%20Cloud-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EKS](https://img.shields.io/badge/AWS%20EKS-Managed%20Kubernetes-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-Cloud%20Native-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-Enterprise-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-Edge%20%26%20WAF-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### ☸️ Containerization & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-Production%20Clusters-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Rootless%20Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm%203-Package%20Manager-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Kustomize](https://img.shields.io/badge/Kustomize-Template%20Free%20Config-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-Daemonless%20Containers-892CA0?style=for-the-badge&logo=podman&logoColor=white)

### 🏗️ Infrastructure as Code & Configuration
![Terraform](https://img.shields.io/badge/Terraform-Modular%20IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-Open%20Source%20IaC-FFDA00?style=for-the-badge&logo=opentofu&logoColor=black)
![Terragrunt](https://img.shields.io/badge/Terragrunt-DRY%20Configurations-2563EB?style=for-the-badge)
![Ansible](https://img.shields.io/badge/Ansible-Automation%20%26%20Config-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-Immutable%20AMIs-02A8EF?style=for-the-badge&logo=packer&logoColor=white)

### 🔄 CI/CD & GitOps Automation
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Workflow%20Automation-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps%20Continuous%20Delivery-EF6134?style=for-the-badge&logo=argo&logoColor=white)
![Argo Rollouts](https://img.shields.io/badge/Argo%20Rollouts-Progressive%20Canary-00C853?style=for-the-badge&logo=argo&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-Pipeline%20Engines-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-Enterprise%20Pipelines-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

### 🔒 DevSecOps, Policy & Supply Chain
![Aqua Trivy](https://img.shields.io/badge/Aqua%20Trivy-Comprehensive%20Scanner-14B8A6?style=for-the-badge&logo=aquasec&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-IaC%20Compliance-24292E?style=for-the-badge)
![Cosign](https://img.shields.io/badge/Cosign-Keyless%20Signature-2563EB?style=for-the-badge)
![Syft](https://img.shields.io/badge/Syft-SBOM%20Generation-6366F1?style=for-the-badge)
![Semgrep](https://img.shields.io/badge/Semgrep-Shift%20Left%20SAST-00C853?style=for-the-badge&logo=semgrep&logoColor=white)
![Falco](https://img.shields.io/badge/Falco-eBPF%20Runtime%20Defense-00AEC7?style=for-the-badge&logo=falco&logoColor=white)
![Kyverno](https://img.shields.io/badge/Kyverno-K8s%20Admission%20Policy-00B4D8?style=for-the-badge)
![OPA Gatekeeper](https://img.shields.io/badge/OPA%20Gatekeeper-Rego%20Engine-4B5563?style=for-the-badge&logo=open-policy-agent&logoColor=white)
![TruffleHog](https://img.shields.io/badge/TruffleHog-Secret%20Scanning-000000?style=for-the-badge)

### 📊 Observability, Monitoring & SRE
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics%20Engine-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Enterprise%20Dashboards-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-Distributed%20Tracing-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-APM%20%26%20Infra-632CA6?style=for-the-badge&logo=datadog&logoColor=white)
![Loki](https://img.shields.io/badge/Grafana%20Loki-Log%20Aggregation-F46800?style=for-the-badge)
![Alertmanager](https://img.shields.io/badge/Alertmanager-Incident%20Routing-E6522C?style=for-the-badge)

### 🌐 Service Mesh & Zero-Trust Networking
![Cilium](https://img.shields.io/badge/Cilium-eBPF%20Networking%20%26%20Security-F38020?style=for-the-badge&logo=cilium&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-mTLS%20Service%20Mesh-466BB0?style=for-the-badge&logo=istio&logoColor=white)
![Envoy](https://img.shields.io/badge/Envoy%20Proxy-Edge%20Gateway-C93770?style=for-the-badge&logo=envoyproxy&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX%20Ingress-High%20Throughput-009639?style=for-the-badge&logo=nginx&logoColor=white)

### 💻 Automation & Systems Programming
![Python](https://img.shields.io/badge/Python-Automation%20%26%20Tooling-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go%20(Golang)-Cloud%20Native%20CLIs-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Shell%20Automation-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-Cross%20Platform-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-Declarative%20Specs-CB171E?style=for-the-badge)

### 💰 FinOps & Chaos Engineering
![Infracost](https://img.shields.io/badge/Infracost-PR%20Cost%20Estimates-00C853?style=for-the-badge)
![Kubecost](https://img.shields.io/badge/Kubecost-K8s%20Cost%20Allocation-1E88E5?style=for-the-badge)
![Karpenter](https://img.shields.io/badge/Karpenter-Dynamic%20Autoscaling-FF9900?style=for-the-badge)
![Chaos Mesh](https://img.shields.io/badge/Chaos%20Mesh-Resilience%20Testing-E535AB?style=for-the-badge)

</div>

---

## 🏆 Flagship DevOps Solutions

Production-grade architectures and automated delivery pipelines engineered for real-world enterprise scale:

<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">🌐 <a href="https://github.com/dspkla/infracode">infracode</a></h3>
      <p align="center"><b>Enterprise AWS Multi-Tier VPC & Private EKS IaC</b></p>
      <p>Modular, highly reusable Terraform architecture providing:</p>
      <ul>
        <li>Multi-AZ VPC with public, private, and isolated database subnets</li>
        <li>Hardened private-only EKS control plane & managed node groups</li>
        <li>Encrypted S3 remote backend with DynamoDB state locking</li>
        <li>Automated Checkov, tfsec & TFLint compliance gates in CI</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Terraform-1.5+-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS-EKS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🚀 <a href="https://github.com/dspkla/gitops-kubernetes-cicd">gitops-kubernetes-cicd</a></h3>
      <p align="center"><b>Cloud-Native GitOps Delivery & Kubernetes Engine</b></p>
      <p>Production GitOps application release workflow featuring:</p>
      <ul>
        <li>Rootless, multi-stage microservice containerization</li>
        <li>Parametric Helm 3 charts with environment overrides</li>
        <li>ArgoCD declarative sync with automated drift correction</li>
        <li>Zero-downtime rolling updates with liveness/readiness probes</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/ArgoCD-GitOps-EF6134?style=flat-square&logo=argo&logoColor=white" />
        <img src="https://img.shields.io/badge/Kubernetes-Helm%203-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🛡️ <a href="https://github.com/dspkla/devsecops">devsecops</a></h3>
      <p align="center"><b>Shift-Left DevSecOps & Supply Chain Framework</b></p>
      <p>Reusable pipeline templates embedding strict security gates:</p>
      <ul>
        <li>Pre-commit & CI secret scans with TruffleHog and Gitleaks</li>
        <li>Deep SAST with Semgrep & license auditing with Trivy</li>
        <li>SPDX/CycloneDX SBOM generation via Syft</li>
        <li>Cryptographic Cosign image signing & Kyverno admission rules</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Cosign-Keyless%20Signing-2563EB?style=flat-square" />
        <img src="https://img.shields.io/badge/Kyverno-Policy%20Engine-00B4D8?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 📜 Certifications & Credentials

<div align="center">

| Credential | Issuing Authority | Focus Domain |
| :--- | :--- | :--- |
| **AWS Certified Solutions Architect – Professional (SAP-C02)** | Amazon Web Services | Multi-Tier Cloud Architecture, High Availability, Disaster Recovery |
| **AWS Certified DevOps Engineer – Professional (DOP-C02)** | Amazon Web Services | Continuous Delivery, Automated Guardrails, Fleet Governance |
| **Certified Kubernetes Administrator (CKA)** | Cloud Native Computing Foundation (CNCF) | Cluster Lifecycle, Networking, Ingress, Pod Scheduling & Storage |
| **Certified Kubernetes Security Specialist (CKS)** | Cloud Native Computing Foundation (CNCF) | Cluster Hardening, Kernel Syscall Auditing, Supply Chain Defense |
| **HashiCorp Certified: Terraform Associate** | HashiCorp | Infrastructure as Code, State Management, Modules & Policy |
| **Red Hat Certified System Administrator (RHCSA)** | Red Hat | Enterprise Linux Administration, Storage, Security & Networking |

</div>

---

## 📊 Telemetry & GitHub Metrics

<div align="center">

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dspkla&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="48%" alt="Deepak Singh GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dspkla&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dspkla&theme=tokyonight&hide_border=true" width="96%" alt="Contribution Streak" />
</p>

</div>

---

## 🤝 Connect & Consulting

I partner with engineering teams, startups, and enterprises to build resilient, cost-efficient, self-defending cloud infrastructure:

* **Platform Engineering Transformation:** Building internal developer platforms (IDP), self-service developer portals, and GitOps delivery engines.
* **Kubernetes Zero-Trust & Modernization:** Hardened multi-tenant clusters, Cilium eBPF mesh, and Kyverno policy governance.
* **DevSecOps Pipeline Hardening:** Eliminating pipeline vulnerabilities, automating SBOMs, and implementing SLSA Level 3 compliance.
* **Cloud Cost Optimization (FinOps):** Slashing monthly cloud spend by 30-50% through Karpenter, Graviton migration, and right-sizing audits.

<p align="center">
  <a href="https://linkedin.com">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20Deepak-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:dspkla@users.noreply.github.com">
    <img src="https://img.shields.io/badge/Email-Direct%20Inquiry-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/dspkla">
    <img src="https://img.shields.io/badge/GitHub-Follow%20%40dspkla-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_colors=%230f2027,%23203a43,%232c5364&height=120&section=footer" width="100%" alt="Footer Banner" />

<sub>Designed and engineered by <b>Deepak Singh (@dspkla)</b> • Zero-Downtime, High-Velocity, Cloud-Native Systems</sub>

</div>
