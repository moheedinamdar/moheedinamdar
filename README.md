<img src="assets/header.svg" width="100%" alt="Moheed Inamdar — Senior DevSecOps & Cloud Security Engineer" />

<div align="center">

# Hey, I'm Moheed! <img src="assets/wave.svg" width="30px" alt="waving hand"/>

### Senior DevSecOps & Cloud Security Engineer · 7+ Years · Securing Developer Platforms at Enterprise Scale

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/moheedinamdar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/moheedinamdar)
[![Website](https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://moheedinamdar.github.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:moheedinamdar@gmail.com)

<img src="https://komarev.com/ghpvc/?username=moheedinamdar&label=Profile%20views&color=0e75b6&style=flat" alt="moheedinamdar" />

</div>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## About Me

```yaml
apiVersion: platform.engineering/v1
kind: SeniorEngineer
metadata:
  name: Moheed Inamdar
  namespace: pune-maharashtra
  labels:
    role: Senior DevSecOps & Cloud Security Engineer
    company: Globant (Client: Roche - GxP regulated)
    experience: "7+ years"
    started: "January 2019"
spec:
  summary: |
    Enterprise-scale DevSecOps and Cloud Security Engineer architecting
    security-first developer platforms across 300+ orgs, 180K+ repos,
    and 5K+ groups in regulated industries (pharma, healthcare,
    cybersecurity). Shifted the enterprise from opt-in to
    enforced-by-default scanning (~100% pipeline coverage), cut CI/CD
    onboarding by ~60%, and built enterprise-adopted security metrics
    platforms used by 100+ product owners.
  currentFocus:
    - Software Supply Chain Security (SLSA, SBOM, Sigstore/cosign)
    - Internal Developer Platforms (Backstage, golden-path templates)
    - Policy-as-Code (OPA, Kyverno) and Kubernetes Security
    - AI-Augmented DevSecOps (LLM-driven vulnerability triage, RAG)
    - LLMOps reference architectures on Kubernetes
  openTo:
    roles:
      - Staff / Principal DevSecOps Engineer
      - Platform Engineering Lead (IC track)
      - Cloud Security Architect
    locations: [Pune, Hyderabad, UAE, Singapore, Remote]
  certifications:
    earned:
      - AWS Certified Developer – Associate (recertifying 2026)
    inProgress:
      - CKA (Certified Kubernetes Administrator)
  education:
    - B.E. in Computer Engineering — Pune University (2015–2018)
```

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Secure SDLC at Enterprise Scale

```mermaid
flowchart LR
  Dev([Commit / PR]) --> CI{CI Pipeline}
  CI --> SAST[SAST]
  CI --> SCA[SCA / Dependencies]
  CI --> SEC[Secret Scan]
  CI --> IMG[Container Scan]
  SAST --> Gate{Policy Gate}
  SCA --> Gate
  SEC --> Gate
  IMG --> Gate
  Gate -- pass --> Sign[Sign + SBOM + Provenance] --> Deploy([Deploy])
  Gate -- fail --> Block([Block + Alert])
```

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Career Journey (Jan 2019 – Present)

```
2019           2020              2024              2026 →
 │              │                 │                 │
 ├──────────────┼─────────────────┼─────────────────┤
 │ CenturySoft  │ Zymr (Virsec)   │ Globant (Roche) │ Staff / Principal
 │ Associate    │ Senior DevOps   │ Sr. DevSecOps & │ DevSecOps /
 │ Developer    │ Engineer (Lead) │ Cloud Security  │ Platform Architect
 ├──────────────┼─────────────────┼─────────────────┤
   AWS · Jenkins  Docker · K8s ·    DevSecOps at        Supply chain security,
   Python · ETL   Terraform ·       enterprise scale —  IDPs (Backstage),
   Cloud Migrate  Container Sec     180K+ repos,        LLMOps,
                  shift-left sec    300+ orgs,          AI-augmented security
                  pipelines         ~100% scan coverage
```

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Featured Projects

> A few things I'm actively building and documenting in public.

| Project | Description | Status |
|---------|-------------|--------|
| **[Supply Chain Security Pipeline](https://github.com/moheedinamdar/supply-chain-security-pipeline)** | SLSA Level 3 + SBOM (Syft) + vulnerability scanning (Grype) + Sigstore cosign signing + Kyverno admission verification on EKS | Building |
| **[AI Vulnerability Triage](https://github.com/moheedinamdar/ai-vulnerability-triage)** | LangChain + LLM + RAG over CVE/EPSS data for auto-prioritization and de-duplication of SAST/SCA findings | Building |

<div align="center">

<a href="https://github.com/moheedinamdar/supply-chain-security-pipeline"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=moheedinamdar&repo=supply-chain-security-pipeline&theme=tokyonight&hide_border=true" alt="supply-chain-security-pipeline" /></a>
<a href="https://github.com/moheedinamdar/ai-vulnerability-triage"><img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=moheedinamdar&repo=ai-vulnerability-triage&theme=tokyonight&hide_border=true" alt="ai-vulnerability-triage" /></a>

</div>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Tech Stack & Expertise

<div align="center">

### Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)

### Containers & Orchestration

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=for-the-badge&logo=rancher&logoColor=white)

### CI/CD & GitOps

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

### Security Scanning (SAST · DAST · SCA · Container · IaC)

![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=for-the-badge&logo=snyk&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white)
![Checkmarx](https://img.shields.io/badge/Checkmarx-54B848?style=for-the-badge&logo=checkmarx&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-3DA639?style=for-the-badge&logo=semgrep&logoColor=white)

### Supply Chain Security & Policy-as-Code (building in public)

![Sigstore](https://img.shields.io/badge/Sigstore_cosign-FFD23F?style=for-the-badge&logo=sigstore&logoColor=black)
![SLSA](https://img.shields.io/badge/SLSA-1F2937?style=for-the-badge&logoColor=white)
![Syft](https://img.shields.io/badge/Syft_SBOM-0066CC?style=for-the-badge&logoColor=white)
![OPA](https://img.shields.io/badge/OPA-7B42BC?style=for-the-badge&logo=openpolicyagent&logoColor=white)
![Kyverno](https://img.shields.io/badge/Kyverno-326CE5?style=for-the-badge&logoColor=white)

### Secrets & Identity

![Vault](https://img.shields.io/badge/HashiCorp_Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![AWS Secrets Manager](https://img.shields.io/badge/AWS_Secrets_Manager-DD344C?style=for-the-badge&logo=awssecretsmanager&logoColor=white)

### Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

### Platform Engineering & AI (learning)

![Backstage](https://img.shields.io/badge/Backstage-9BF0E1?style=for-the-badge&logo=backstage&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![BentoML](https://img.shields.io/badge/BentoML-000000?style=for-the-badge&logoColor=white)

### Languages & Scripting

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell_Script-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![HCL](https://img.shields.io/badge/HCL-844FBA?style=for-the-badge&logo=terraform&logoColor=white)

</div>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Key Achievements

<table>
<tr>
<td width="50%">

**At Globant — Client: Roche (2024–Present)**

- Architected **Unified Security Metrics Platform** (Python/GraphQL/DuckDB/Grafana) adopted enterprise-wide
- Owned security posture across **300+ orgs · 180K+ repos · 5K+ groups**
- Drove security scanning from opt-in to enforced-by-default (~100% pipeline coverage)
- Designed reusable secure CI/CD templates cutting onboarding by **~60%**
- Built internal security dashboard empowering **100+ product owners**
- Led team of 3 engineers · 15+ enablement sessions

</td>
<td width="50%">

**At Zymr — Client: Virsec (2020–2024)**

- Shifted security left, catching the majority of vulnerabilities pre-staging
- Hardened **50+ Docker images** against CIS Benchmarks
- Reduced infra provisioning time by **70%** with serverless architecture
- Designed DR & high availability (multi-AZ) on AWS Well-Architected
- Led microservices migration, mentoring 10+ developers
- Core member of Virsec product security research team

</td>
</tr>
</table>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Awards & Recognition

| Award | Year | Details |
|-------|------|---------|
| **Pat on the Back Award** — Globant | 2024 | Recognized for leading the internal security dashboard & reporting system, driving cross-functional innovation in security automation |
| **Hackathon Winner (2nd Place)** — Zymr | 2023 | Built an AI-powered NLP summarization system using synthetic and open datasets — foundation for current AI-augmented security work |

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=moheedinamdar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=moheedinamdar&show_icons=true&theme=tokyonight&hide_border=true&layout=compact" alt="Top Languages" />

<img width="100%" src="https://raw.githubusercontent.com/moheedinamdar/moheedinamdar/output/github-snake-dark.svg" alt="Contribution snake" />

</div>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Currently

- Architecting enterprise security frameworks at **Globant (Roche / GxP regulated)**
- Building open-source work around **supply chain security** and **AI-augmented DevSecOps**
- Working toward **CKA** (Certified Kubernetes Administrator)
- Writing about DevSecOps and platform engineering at scale; articles are on the way for Medium and Dev.to
- **Open to Staff / Principal DevSecOps · Platform Engineering Lead · Cloud Security Architect** roles in Pune, Hyderabad, UAE, Singapore, or Remote

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

<div align="center">

### Let's Connect

**Open to collaborating on DevSecOps, Platform Engineering, Software Supply Chain Security, and Cloud Security projects.**

[![Email](https://img.shields.io/badge/moheedinamdar@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:moheedinamdar@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/moheedinamdar)
[![Website](https://img.shields.io/badge/moheedinamdar.github.io-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://moheedinamdar.github.io/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
