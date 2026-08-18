# Hi, I'm Thanos 👋

**DevOps & Cloud Engineer.** I build, break, and fix systems, then automate what's left.

Most of my side projects run on one idea: local-first tooling that proves its own work. A pipeline that re-runs the gate and shows zero violations. A supply chain that blocks an unsigned image at admission. An eval harness that fails the build when an LLM regresses. The code stays on your machine and the proof is in the run.

---

### 🔧 Featured projects

| Project | What it does |
|---|---|
| **[policy-as-code-ai](https://github.com/KatsaounisThanasis/policy-as-code-ai)** | Local-first Policy-as-Code with *provable* remediation. A local LLM explains each Terraform misconfiguration, a deterministic engine writes the fix, and the pipeline re-scans to prove **0 violations**. Nothing leaves your machine. `OPA/Rego · Terraform · Ollama` |
| **[secure-supply-chain](https://github.com/KatsaounisThanasis/secure-supply-chain)** | End-to-end zero-trust supply chain: Hadolint + Gitleaks → Trivy CVE scan (SARIF) → CycloneDX SBOM → Cosign keyless signing → Kyverno admission control. Self-proving on every push. `Sigstore · SLSA · Kyverno` |
| **[llm-reliability-lab](https://github.com/KatsaounisThanasis/llm-reliability-lab)** | A CI/CD evaluation harness that gates LLM regressions on accuracy, latency, cost & error rate. Policy-as-Code, but for AI behavior. `Python · LiteLLM · CI` |
| **[Multi-Cloud-Hub](https://github.com/KatsaounisThanasis/Multi-Cloud-Hub)** ([live demo](https://katsaounisthanasis.github.io/Multi-Cloud-Hub/)) | A portal to deploy and manage infrastructure across Azure & GCP from one place. `FastAPI · React · Terraform` |

---

### ✍️ Writing

I write up how these projects work and the calls I made building them:

- [I built a policy scanner that fixes my Terraform and proves the fix holds](https://medium.com/@katsathanasis2/i-built-a-policy-scanner-that-fixes-my-terraform-and-proves-the-fix-holds-2cb12ac60637)
- [I built a CI/CD pipeline that refuses to run code it can't prove it built](https://medium.com/@katsathanasis2/i-built-a-ci-cd-pipeline-that-refuses-to-run-code-it-cant-prove-it-built-e6cc30813524)

More on [Medium](https://medium.com/@katsathanasis2).

---

### 🧰 Tech I reach for

**Cloud** Azure · GCP  
**IaC & Policy** Terraform · Bicep · OPA/Rego · Kyverno  
**Supply chain & security** Cosign / Sigstore · Trivy · SBOM (CycloneDX) · SLSA  
**Languages** Python · Go · Shell · HCL  
**CI/CD & runtime** GitHub Actions · Docker · Kubernetes

---

### 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thanos-katsaounis/)

<sub>Automating stuff and learning daily, one project at a time. 🚀</sub>
