<div align="center">

<img src="https://accuknox.com/wp-content/uploads/accuknox-logo-2.png" alt="AccuKnox" width="280"><br><br>

# Zero Trust CNAPP for the AI Era

**Runtime-first cloud, application, API, and AI security, built on eBPF and KubeArmor.**

[Website](https://www.accuknox.com) · [Platform](https://accuknox.com/platform) · [Docs](https://help.accuknox.com) · [Product Tour](https://accuknox.com/product-tour) · [Schedule a Demo](https://www.accuknox.com/contact-us)

![GitHub org](https://img.shields.io/badge/org-accuknox-blue?style=flat-square)
![KubeArmor](https://img.shields.io/github/stars/kubearmor/kubearmor?label=KubeArmor%20stars&style=flat-square)
![Compliance](https://img.shields.io/badge/compliance%20frameworks-45%2B-success?style=flat-square)
![Integrations](https://img.shields.io/badge/integrations-30%2B-success?style=flat-square)

<img src="https://accuknox.com/wp-content/uploads/cnapp-v3-home.webp" alt="AccuKnox CNAPP platform overview" width="850">

</div>

---

## What AccuKnox does

Most CNAPP tools stop at posture scanning. They find the misconfiguration and leave the fix to you. AccuKnox blocks the attack at runtime, in the kernel, using eBPF and Linux Security Modules (AppArmor, BPF-LSM, SELinux) through our open source engine, [KubeArmor](https://github.com/kubearmor/KubeArmor).

One platform covers cloud, container, Kubernetes, application, API, and AI workloads, on any cloud, on-prem, or air-gapped. Zero Trust policies enforce "never trust, always verify" instead of alerting after the fact. Runtime blocking runs under 1% CPU overhead.

A DevSecOps team running 18,000+ assets across GCP, VMs, and Kubernetes cut alert noise by 85% after switching from a legacy CNAPP. A 200+ account financial services customer cut quarterly audit prep from 60 hours to under 5.

---

## The platform, by domain

Each card links to the live product page. Screenshots are pulled straight from [accuknox.com/platform](https://accuknox.com/platform).

<table>
<tr>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/cspm"><img src="https://accuknox.com/wp-content/uploads/CSPM1-dashboard-home.webp" width="100%"></a>

### [Cloud Security (CSPM)](https://accuknox.com/platform/cspm)
Misconfiguration detection and drift prevention across AWS, Azure, GCP, and Oracle Cloud.
[Docs →](https://help.accuknox.com/use-cases/cloud-misconfigurations/)

</td>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/cwpp"><img src="https://accuknox.com/wp-content/uploads/CWPP1-dashboard-home.webp" width="100%"></a>

### [Workload Security (CWPP)](https://accuknox.com/platform/cwpp)
Runtime protection for VMs, containers, and serverless, with automated zero-trust policy generation.
[Docs →](https://help.accuknox.com/use-cases/crypto-mining/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/kspm"><img src="https://accuknox.com/wp-content/uploads/KSPM1-dashboard-home.webp" width="100%"></a>

### [Kubernetes Security (KSPM)](https://accuknox.com/platform/kspm)
Cluster posture plus in-line enforcement that stops zero-days before they spread. Includes Kubernetes Identity and Entitlement Management (KIEM) to kill excessive standing permissions.
[Docs →](https://help.accuknox.com/use-cases/kiem/)

</td>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/aspm"><img src="https://accuknox.com/wp-content/uploads/ASPM1-dashboard-home.webp" width="100%"></a>

### [Application Security (ASPM)](https://accuknox.com/platform/aspm)
Shift-left SAST, SCA, and DAST tied to runtime context, so teams fix what is actually exploitable.
[Docs →](https://help.accuknox.com/use-cases/dast-xss/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/api-security"><img src="https://accuknox.com/wp-content/uploads/api1-dashboard-home.webp" width="100%"></a>

### [API Security](https://accuknox.com/platform/api-security)
Finds broken access control, broken authentication, and injection flaws across every exposed API.
[Docs →](https://help.accuknox.com/use-cases/asset-inventory/)

</td>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/ai-security"><img src="https://accuknox.com/wp-content/uploads/AI-SPM1-dashboard-home.webp" width="100%"></a>

### [AI and LLM Security](https://accuknox.com/platform/ai-security)
Discovers, scans, and sandboxes every model, agent, and prompt path. Full module breakdown below.
[Docs →](https://help.accuknox.com/use-cases/shadow-ai-discovery/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/dspm"><img src="https://accuknox.com/wp-content/uploads/DSPM1-dashboard-home.webp" width="100%"></a>

### [Data Security (DSPM)](https://accuknox.com/platform/dspm)
Tracks sensitive data exposure, uncontrolled access, and exfiltration paths across cloud and AI stores.
[Docs →](https://help.accuknox.com/use-cases/cloud/aws-storage/)

</td>
<td width="50%" valign="top">

<a href="https://accuknox.com/solutions/sbom"><img src="https://accuknox.com/wp-content/uploads/SBOM1-dashboard-home.webp" width="100%"></a>

### [Supply Chain Security (SBOM)](https://accuknox.com/solutions/sbom)
Generates SBOM, HBOM, AIBOM, CBOM, and QBOM, with VEX and CSAF support for audit-ready provenance.
[Docs →](https://help.accuknox.com/use-cases/knoxguard-supply-chain/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://accuknox.com/solutions/secrets-management"><img src="https://accuknox.com/wp-content/uploads/secrets-manager-dashboard-home.webp" width="100%"></a>

### [Secrets Manager](https://accuknox.com/solutions/secrets-management)
Detects and blocks leaked API keys, passwords, and credentials before they leave the environment.
[Docs →](https://help.accuknox.com/use-cases/secret-scan-cicd-aws/)

</td>
<td width="50%" valign="top">

<a href="https://accuknox.com/platform/compliance"><img src="https://accuknox.com/wp-content/uploads/COMPLIANCE1-dashboard-home.webp" width="100%"></a>

### [Compliance and Governance](https://accuknox.com/platform/compliance)
45+ frameworks mapped and continuously audited, including HIPAA, GDPR, SOC 2, ISO 27001, and FedRAMP.
[Docs →](https://help.accuknox.com/use-cases/compliance/)

</td>
</tr>
</table>

**[→ See the full platform](https://accuknox.com/platform)**, including CDR, SIEM, 5G security, and hybrid/private cloud coverage.

---

## AI Security 2.0

<div align="center">
<img src="https://accuknox.com/wp-content/uploads/agentz-tab-home-1.webp" alt="AccuKnox Agentic AI security" width="850">
</div>

Launched at RSA 2026. Eight modules, built on the open standards SPIFFE and OpenFGA, integrated with Amazon Bedrock, Gemini, Ollama, and vLLM.

| Module | What it does |
|---|---|
| [AI Security Posture Management (AI-SPM)](https://accuknox.com/platform/ai-spm) | Live, agentless inventory of every model in use |
| [Agentic AI Security](https://accuknox.com/platform/agentz) | Sandboxes every AI agent at the kernel level with eBPF and LSM |
| [AI Detect & Respond (AI-DR)](https://accuknox.com/solutions/ai-dr) | Reconstructs attack chains across prompts and tool calls |
| [AI Guardrails, Stateful Prompt Firewall](https://accuknox.com/solutions/prompt-firewall) | Filters, audits, and blocks malicious LLM prompts and responses |
| [AI Red Teaming & Pen Testing](https://accuknox.com/solutions/ai-red-teaming) | Runs automated adversarial tests for prompt injection, hallucination, and toxicity |
| AI Identity Security | Scopes permissions per agent and kills standing credentials |
| [AI Model & Dataset Security (ModelArmor)](https://accuknox.com/platform/modelarmor) | Scans 5 model formats for backdoors and unsafe code |
| [AI Compliance & Governance (AI-GRC)](https://accuknox.com/platform/grc) | Assigns an EU AI Act risk tier instantly, mapped to your controls |

A healthcare AI customer cut PII leak risk by 85% under HIPAA. An AI workload customer cut data leakage risk by 85% after deploying AI-SPM.

[Explore AI Security →](https://accuknox.com/platform/ai-security)

---

## Deploy anywhere

<div align="center">
<img src="https://accuknox.com/wp-content/uploads/infra-sec-tab-1-home.webp" alt="AccuKnox infrastructure coverage" width="850">
</div>

| Environment | Coverage |
|---|---|
| [Public cloud](https://accuknox.com/platform/public-cloud-security) | AWS, Azure, GCP, Oracle Cloud |
| [Private cloud](https://accuknox.com/platform/private-cloud-security) | OpenStack, Red Hat OpenShift, VMware Tanzu, Nutanix, IBM Cloud |
| [On-premise](https://accuknox.com/platform/on-premise-security) | Full CNAPP stack, no external dependency |
| [5G and IoT/Edge](https://accuknox.com/platform/5g-security) | 89% uptime in production telecom deployments |
| AI and LLM assets | Hugging Face, OpenAI, TensorFlow, Ollama, managed and private models |

---

## Resources

**Documentation:** [Getting started](https://help.accuknox.com/introduction/home/) · [Deployment models](https://help.accuknox.com/getting-started/deployment-models/) · [AI/ML support matrix](https://help.accuknox.com/support-matrix/aiml-support-matrix/) · [CI/CD support matrix](https://help.accuknox.com/support-matrix/cicd-support-matrix/) · [IaC support](https://help.accuknox.com/support-matrix/iac/)

**Integrations:** [AWS](https://help.accuknox.com/integrations/aws-overview/) · [Azure](https://help.accuknox.com/integrations/azure-overview/) · [GCP](https://help.accuknox.com/integrations/google-overview/) · [GitHub](https://help.accuknox.com/integrations/github-overview/) · [GitLab](https://help.accuknox.com/integrations/gitlab-overview/) · [Jenkins](https://help.accuknox.com/integrations/jenkins-overview/) · [See all 30+ →](https://accuknox.com/integrations)

**Use cases:** [Asset inventory](https://help.accuknox.com/use-cases/asset-inventory/) · [Cloud misconfigurations](https://help.accuknox.com/use-cases/cloud-misconfigurations/) · [Crypto mining detection](https://help.accuknox.com/use-cases/crypto-mining/) · [Shadow AI discovery](https://help.accuknox.com/use-cases/shadow-ai-discovery/) · [KIEM](https://help.accuknox.com/use-cases/kiem/) · [Prompt firewall](https://help.accuknox.com/use-cases/prompt-firewall/)

**Case studies:** [Banking & fintech](https://accuknox.com/case-studies/banking-fintech) · [Healthcare](https://accuknox.com/case-studies/healthcare) · [Telecom](https://accuknox.com/case-studies/telecommunications) · [Public sector](https://accuknox.com/case-studies/public-sector) · [US DoD](https://accuknox.com/case-studies/us-dod)

---

## Open source

<div align="center">
<img src="https://accuknox.com/wp-content/uploads/2023/10/kubearmor-new.webp" alt="KubeArmor" height="40">
&nbsp;&nbsp;&nbsp;
<a href="https://accuknox.com/platform/modelarmor"><b>ModelArmor</b></a>
</div>

- **[KubeArmor](https://github.com/kubearmor/KubeArmor)** — runtime security enforcement engine for containers, VMs, and nodes, built on eBPF and LSM. CNCF project, 1M+ downloads.
- **[ModelArmor](https://accuknox.com/platform/modelarmor)** — open source runtime sandboxing for LLM and ML workloads. CNCF project.

**[→ All open source repos](https://accuknox.com/open-source-repos)**

---

## Company

Incubated at SRI International (Stanford Research Institute). Backed by National Grid Partners, Dolby Family Ventures, Dreamit Ventures, Avanta Ventures, 5G Open Innovation Lab, and NVIDIA. Distributed through TD SYNNEX in North America and Carahsoft for the federal channel. Listed on AWS, Azure, Red Hat, and Oracle Cloud marketplaces.

<div align="center">

**[Explore our repositories below](https://github.com/orgs/accuknox/repositories)** · **[Talk to Security Experts](https://www.accuknox.com/contact-us)**

</div>
