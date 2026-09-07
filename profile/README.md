<div align="center">

# AccuKnox — Zero Trust CNAPP for the AI Era

**Runtime-first cloud, application, API, and AI security, built on eBPF and KubeArmor.**

[Website](https://www.accuknox.com) · [Docs](https://help.accuknox.com) · [Schedule a Demo](https://www.accuknox.com/contact-us) · [Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=seller-yzcds4cyvvvpe)

![GitHub org](https://img.shields.io/badge/org-accuknox-blue?style=flat-square)
![KubeArmor](https://img.shields.io/github/stars/kubearmor/kubearmor?label=KubeArmor%20stars&style=flat-square)
![Compliance](https://img.shields.io/badge/compliance%20frameworks-45%2B-success?style=flat-square)
![Integrations](https://img.shields.io/badge/integrations-30%2B-success?style=flat-square)

</div>

---

## What AccuKnox does

Most CNAPP tools stop at posture scanning. They find the misconfiguration and leave the fix to you. AccuKnox blocks the attack at runtime, in the kernel, using eBPF and Linux Security Modules (AppArmor, BPF-LSM, SELinux) through our open source engine, [KubeArmor](https://github.com/kubearmor/KubeArmor).

One platform covers cloud, container, Kubernetes, application, API, and AI workloads, on any cloud, on-prem, or air-gapped. Zero Trust policies enforce "never trust, always verify" instead of alerting after the fact. Runtime blocking runs under 1% CPU overhead.

A DevSecOps team running 18,000+ assets across GCP, VMs, and Kubernetes cut alert noise by 85% after switching from a legacy CNAPP. A 200+ account financial services customer cut quarterly audit prep from 60 hours to under 5.

---

## The platform, by domain

<table>
<tr>
<td width="33%">

### Cloud Security (CSPM)
Misconfiguration detection and drift prevention across AWS, Azure, GCP, and Oracle Cloud.

</td>
<td width="33%">

### Workload Security (CWPP)
Runtime protection for VMs, containers, and serverless, with automated zero-trust policy generation.

</td>
<td width="33%">

### Kubernetes Security (KSPM)
Cluster-level posture plus in-line enforcement that stops zero-day attacks before they spread.

</td>
</tr>
<tr>
<td width="33%">

### Application Security (ASPM)
Shift-left scanning (SAST, SCA, DAST) tied to runtime context, so teams fix what's actually exploitable.

</td>
<td width="33%">

### API Security
Finds broken access control, broken auth, and injection flaws across every exposed API.

</td>
<td width="33%">

### AI and LLM Security
Discovers, scans, and sandboxes every model, agent, and prompt path. See the AI Security 2.0 section below.

</td>
</tr>
<tr>
<td width="33%">

### Data Security (DSPM)
Tracks sensitive data exposure, uncontrolled access, and exfiltration paths across cloud and AI stores.

</td>
<td width="33%">

### Identity (CIEM / KIEM)
Cloud and Kubernetes identity and entitlement management, built to kill excessive standing permissions.

</td>
<td width="33%">

### Supply Chain (SBOM)
Generates SBOM, HBOM, AIBOM, CBOM, and QBOM, with VEX and CSAF support for audit-ready provenance.

</td>
</tr>
<tr>
<td width="33%">

### Secrets Manager
Detects and blocks leaked API keys, passwords, and credentials before they leave the environment.

</td>
<td width="33%">

### Compliance and Governance
45+ frameworks mapped and continuously audited, including HIPAA, GDPR, SOC 2, ISO 27001, and FedRAMP.

</td>
<td width="33%">

### Detection and Response (CDR)
Correlates findings across cloud, container, cluster, and code (4C coverage) into one investigation.

</td>
</tr>
</table>

---

## AI Security 2.0

Launched at RSA 2026. Eight modules, built on the open standards SPIFFE and OpenFGA, integrated with Amazon Bedrock, Gemini, Ollama, and vLLM.

| Module | What it does |
|---|---|
| **AI Security Posture Management (AI-SPM)** | Live, agentless inventory of every model in use |
| **Agentic AI Security** | Sandboxes every AI agent at the kernel level with eBPF and LSM |
| **AI Detect & Respond (AI-DR)** | Reconstructs attack chains across prompts and tool calls |
| **AI Guardrails, Stateful Prompt Firewall** | Filters, audits, and blocks malicious LLM prompts and responses |
| **AI Red Teaming & Pen Testing** | Runs automated adversarial tests for prompt injection, hallucination, and toxicity |
| **AI Identity Security** | Scopes permissions per agent and kills standing credentials |
| **AI Model & Dataset Security** | Scans 5 model formats for backdoors and unsafe code |
| **AI Compliance & Governance (AI-GRC)** | Assigns an EU AI Act risk tier instantly, mapped to your controls |

A healthcare AI customer cut PII leak risk by 85% under HIPAA. An AI workload customer cut data leakage risk by 85% after deploying AI-SPM.

---

## Deploy anywhere

| Environment | Coverage |
|---|---|
| Public cloud | AWS, Azure, GCP, Oracle Cloud |
| Private cloud | OpenStack, OpenShift, VMware, Nutanix |
| On-premise and air-gapped | Full CNAPP stack, no external dependency |
| Edge and IoT | 89% uptime in production telecom deployments |
| AI and LLM assets | Hugging Face, OpenAI, TensorFlow, Ollama, managed and private models |

---

## Open source

- **[KubeArmor](https://github.com/kubearmor/KubeArmor)** — runtime security enforcement engine for containers, VMs, and nodes, built on eBPF and LSM. CNCF project, 1M+ downloads.
- **[ModelArmor](https://github.com/accuknox/ModelArmor)** — open source runtime sandboxing for LLM and ML workloads. CNCF project.

---

## Company

Incubated at SRI International (Stanford Research Institute). Backed by National Grid Partners, Dolby Family Ventures, Dreamit Ventures, Avanta Ventures, 5G Open Innovation Lab, and NVIDIA. Distributed through TD SYNNEX in North America and Carahsoft for the federal channel. Listed on AWS, Azure, Red Hat, and Oracle Cloud marketplaces.

<div align="center">

**[Explore our repositories below](https://github.com/orgs/accuknox/repositories)** · **[Talk to Security Experts](https://www.accuknox.com/contact-us)**

</div>
