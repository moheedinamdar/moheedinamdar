<img src="assets/header.svg" width="100%" alt="Moheed Inamdar, Senior Platform & DevOps Engineer" />

<div align="center">

# Hey, I'm Moheed! <img src="assets/wave.svg" width="30px" alt="waving hand"/>

### Senior Platform & DevOps Engineer · 7+ Years · Developer Platforms, Delivery & Platform Security

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
    role: Senior Platform & DevOps Engineer
    company: Globant (Client: Roche - GxP regulated)
    experience: "7+ years"
    started: "January 2019"
spec:
  summary: |
    Platform and DevOps engineer building internal developer platforms,
    golden-path CI/CD and secure-by-default delivery across a
    GxP-regulated estate of 300+ GitHub orgs, 180K+ repositories and
    5K+ GitLab groups in pharma, healthcare and cybersecurity. Moved
    the enterprise from opt-in to enforced-by-default scanning on every
    eligible project, cut CI/CD onboarding by ~60%, and built the
    governance and measurement layer underneath it.
  currentFocus:
    - Internal Developer Platforms (Backstage scaffolder, golden-path templates)
    - Repository-centric security and governance automation at scale
    - Verification: per-run least-privilege credentials, fail-closed
      preflight, dry-run, audit on every outcome
    - Vulnerability operations: scanner normalisation, MTTR, backlog age
  learningInPublic:
    - Workload identity and OIDC federation (no production experience yet)
    - Policy engines: OPA/Rego and Kyverno (no production experience yet)
    - OpenTelemetry (no production experience yet)
  openTo:
    roles:
      - Senior Platform Engineer
      - Security Platform Engineer
      - DevEx Platform Engineer
      - Senior DevOps Engineer
    locations: [Pune, Hyderabad, UAE, Singapore, Remote]
  certifications: none currently held
  education:
    - B.E. in Computer Engineering, Pune University (2015-2018)
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

## Career Journey (Jan 2019 - Present)

```
2019           2020              2024              2026 →
 │              │                 │                 │
 ├──────────────┼─────────────────┼─────────────────┤
 │ CenturySoft  │ Zymr (Virsec)   │ Globant (Roche) │ Senior Platform /
 │ Associate    │ Senior DevOps   │ Sr. DevSecOps   │ Security Platform
 │ Developer    │ Engineer (Lead) │ Engineer (SME)  │ Engineer
 ├──────────────┼─────────────────┼─────────────────┤
   AWS · Jenkins  Docker · K8s ·    Platform · IDPs     Developer platforms,
   Python · ETL   Terraform ·       Backstage · GHAS    governance
   Cloud Migrate  Container Sec     180K+ repo estate,  automation,
                  shift-left sec    300+ orgs,          verification
                  pipelines         enforced scanning
```

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Featured Projects

> Things I maintain, and things I am learning in public. The status column is honest:
> "working" means you can run it today, "scaffold" means the interfaces exist and the
> hard parts are still TODO.

| Project | Description | Status |
|---------|-------------|--------|
| **[precommit-security-hooks](https://github.com/moheedinamdar/precommit-security-hooks)** | Pre-commit bundle that blocks secrets, unsafe Dockerfiles and insecure IaC before they reach a repo. Every scanner runs from its official, version-pinned container image. Three layered profiles | Working |
| **[setup-personal-work-git-profiles](https://github.com/moheedinamdar/setup-personal-work-git-profiles)** | Cross-platform wizard for multiple Git identities on one machine, auto-routed by directory, with per-profile SSH keys and commit signing | Working |
| **[naukri-auto-update](https://github.com/moheedinamdar/naukri-auto-update)** | Headful Playwright automation with a persistent browser profile, built around real bot-protection constraints | Working |
| **[nuke-docker](https://github.com/moheedinamdar/nuke-docker)** | One script to reset Docker to a freshly-installed state, with a full preview before it deletes anything | Working |
| **[Supply Chain Security Pipeline](https://github.com/moheedinamdar/supply-chain-security-pipeline)** | Learning in public. CI wires up Syft SBOM generation, Grype scanning and cosign signing; SLSA provenance and Kyverno admission verification are not finished | Scaffold |
| **[AI Vulnerability Triage](https://github.com/moheedinamdar/ai-vulnerability-triage)** | Learning in public. SARIF ingest and de-duplication work; EPSS/KEV enrichment and the LLM prioritiser are not implemented yet | Scaffold |

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

### Security Scanning (SAST · SCA · Secrets · Container)

![GHAS](https://img.shields.io/badge/GitHub_Advanced_Security-181717?style=for-the-badge&logo=github&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=for-the-badge&logo=snyk&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white)
![Checkmarx](https://img.shields.io/badge/Checkmarx-54B848?style=for-the-badge&logo=checkmarx&logoColor=white)
![Sysdig](https://img.shields.io/badge/Sysdig_Secure-00B6D6?style=for-the-badge&logoColor=white)

### Platform Engineering

![Backstage](https://img.shields.io/badge/Backstage-9BF0E1?style=for-the-badge&logo=backstage&logoColor=black)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

### Learning in public (no production experience yet)

![Sigstore](https://img.shields.io/badge/Sigstore_cosign-FFD23F?style=for-the-badge&logo=sigstore&logoColor=black)
![SLSA](https://img.shields.io/badge/SLSA-1F2937?style=for-the-badge&logoColor=white)
![Syft](https://img.shields.io/badge/Syft_SBOM-0066CC?style=for-the-badge&logoColor=white)
![OPA](https://img.shields.io/badge/OPA-7B42BC?style=for-the-badge&logo=openpolicyagent&logoColor=white)
![Kyverno](https://img.shields.io/badge/Kyverno-326CE5?style=for-the-badge&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

### Secrets & Identity

![Vault](https://img.shields.io/badge/HashiCorp_Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black)
![AWS Secrets Manager](https://img.shields.io/badge/AWS_Secrets_Manager-DD344C?style=for-the-badge&logo=awssecretsmanager&logoColor=white)

### Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)

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

**At Globant, Client: Roche (2024-Present)**

- Designed and built the **repository governance control plane** (Backstage scaffolder over a Python control plane) and the **GitHub security engine** (Python/FastAPI/GitHub Apps)
- Worked across an estate of **300+ orgs · 180K+ repos · 5K+ groups**
- Drove security scanning from opt-in to enforced-by-default on every eligible project
- Designed reusable secure CI/CD templates cutting onboarding by **~60%**
- Built a security analytics platform normalising every scanner into one severity model (pre-production)
- Led team of 3 engineers · 15+ enablement sessions

</td>
<td width="50%">

**At Zymr, Client: Virsec (2020-2024)**

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
| **Pat on the Back Award**: Globant | 2024 | Recognised for leading the internal developer and security metrics platform, and for cross-functional work in security automation |
| **2nd Place, Z-Hackathon**: Zymr | 2023 | AI-powered NLP summarisation system over synthetic and open datasets |

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Contribution Activity

<div align="center">

![Followers](https://img.shields.io/github/followers/moheedinamdar?style=for-the-badge&logo=github&label=Followers&color=0e75b6)

<img width="100%" src="https://raw.githubusercontent.com/moheedinamdar/moheedinamdar/output/github-snake-dark.svg" alt="Contribution snake" />

</div>

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

## Currently

- Building developer platforms and governance automation at **Globant (Roche / GxP regulated)**
- Maintaining open-source developer tooling, and learning supply-chain security in public
- Writing about platform engineering and secure delivery at scale
- **Open to Senior Platform Engineer · Security Platform Engineer · DevEx Platform Engineer · Senior DevOps** roles in Pune, Hyderabad, UAE, Singapore, or Remote

<img src="assets/rainbow-divider.svg" width="100%" alt="" />

<div align="center">

### Let's Connect

**Open to collaborating on Platform Engineering, Developer Experience, DevSecOps and secure software delivery projects.**

[![Email](https://img.shields.io/badge/moheedinamdar@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:moheedinamdar@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/moheedinamdar)
[![Website](https://img.shields.io/badge/moheedinamdar.github.io-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://moheedinamdar.github.io/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
