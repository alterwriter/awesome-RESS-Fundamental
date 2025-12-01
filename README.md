<p align="center">
  <img src="https://img.shields.io/badge/Awesome%20RESS-Fundamentals-blue?style=for-the-badge&logo=google" alt="Awesome RESS Fundamentals"/>
</p>

<h1 align="center">Awesome RESS Fundamentals</h1>
<p align="center"><strong>Reliability Engineering & Secure Systems — A Beginner-Friendly Awesome List</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/PRs-welcome-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/category-RESS-orange?style=flat-square"/>
</p>

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [What is RESS?](#what-is-ress)
- [RESS vs SOC](#ress-vs-soc)
- [Core Principles of RESS](#core-principles-of-ress)
- [Books](#books)
- [Blogs & Articles](#blogs--articles)
- [Videos](#videos)
- [Tools](#tools)
  - [Monitoring & Observability](#monitoring--observability)
  - [Incident & Security Engineering](#incident--security-engineering)
  - [Resilience & Chaos Engineering](#resilience--chaos-engineering)
  - [CI/CD & Supply Chain Security](#cicd--supply-chain-security)
- [Case Studies - with Videos & Resources]#case-studies--with-videos--resources)
- [Contributing](#contributing)
- [License](#license)

---

## 🧭 Introduction

**RESS (Reliability Engineering & Secure Systems)** is the engineering discipline that combines **SRE principles** with **Security Engineering** to build systems that are **reliable, fault-tolerant, resilient, and secure-by-design**.

As modern systems become more distributed, more automated, and more exposed to security threats, RESS emerges as the next evolution of reliability and security practices.

RESS answers the question:

> *“How do we ensure systems stay reliable and secure under both operational stress and adversarial conditions?”*

---

## 🔥 What is RESS?

**Reliability Engineering & Secure Systems (RESS)** focuses on engineering secure and resilient platforms by integrating:

- SRE methodologies  
- Security architecture  
- Secure-by-design principles  
- Chaos + security testing  
- Resilience engineering  
- Threat-aware reliability strategies  
- Secure CI/CD + supply-chain hardening

RESS is **not** SOC, **not** DevSecOps, but an engineering-focused discipline that fills the gap between **system reliability** and **system security**.

---

## 🛡️ RESS vs SOC

Many engineers confuse RESS with SOC because both involve security.  
However, they serve **different purposes** and have **different scopes**:

### **RESS = Engineering Discipline**  
Focus: *Build secure, resilient, reliable systems.*

### **SOC = Operational Security Function**  
Focus: *Detect, investigate, respond to threats.*

---

### 🧩 Scope of Work Comparison

| Area | RESS | SOC |
|------|------|------|
| Mission | Build secure & reliable systems | Monitor & respond to security threats |
| Type | Engineering & architecture | Security operations |
| Focus | SLOs, resilience, hardening, secure CI/CD | SIEM alerts, threat hunting, IR |
| Mode | Proactive (design & prevent) | Reactive + proactive (detect & respond) |
| Output | Robust reliable system designs | Security alerts, incident response |

---

### ⚡ Simple Analogy

- **RESS** = civil engineer who designs a building to be earthquake-proof, fire-proof, and attack-proof.  
- **SOC** = security guard + CCTV team who monitors, detects, and responds when something goes wrong.

Both critical. Different responsibilities.

---

## 🧠 Core Principles of RESS

- **Secure Reliability** → Reliability informed by threat modeling  
- **Secure-by-Design** → Embed security early in architecture  
- **Resilience Engineering** → Systems survive failure + attack  
- **Security Observability** → Trace signals that matter  
- **Chaos & Adversarial Testing** → Validate system under attack  
- **Risk-Based SLIs/SLOs** → Reliability aligned with security risks  
- **Zero Trust Architecture** integrated into SRE practices  
- **Operational Hardening** → Runtime, infra, identity, pipelines  
- **Rapid Recovery** → MTTR improvements combined with IR readiness  

---

## 📘 Books

### **1. Building Secure & Reliable Systems (Google SRS Book)**
https://sre.google/books/building-secure-and-reliable-systems/

### **2. Site Reliability Engineering (SRE Book)**
https://sre.google/sre-book/table-of-contents/

### **3. The Site Reliability Workbook**
https://sre.google/workbook/table-of-contents/

### **4. Implementing Service Level Objectives (Alex Hidalgo)**  
https://www.oreilly.com/library/view/implementing-service-level/9781492076810/

### **5. Security Chaos Engineering**  
https://www.securitychaosengineering.com/

### **6. Defensive Security Handbook**  
Reliable operational security patterns.

---

## 📝 Blogs & Articles

- Google SRE Blog  
  https://sre.google/blog/

- PFLB – What is SRE?  
  https://pflb.us/blog/what-is-sre-site-reliability-engineering/

- Rootly – SRE Resources  
  https://rootly.com/blog/top-sre-resources-of-2024

- Security Chaos Engineering Blog  
  https://securitychaosengineering.com/blog/

- AWS Resilience Hub Blog  
  https://aws.amazon.com/blogs/architecture/tag/aws-resilience-hub/

---

## 🎥 Videos

- Google SRE Fundamentals  
  https://www.youtube.com/watch?v=uTEL8Ff1Zvk

- Security Chaos Engineering – Conf42  
  https://www.youtube.com/watch?v=8J1GzFzB9BM

- Reliability Engineering Talks (SRECon)  
  https://www.usenix.org/conferences

---

## 🛠️ Tools

### Monitoring & Observability
- Prometheus  
- Grafana  
- OpenTelemetry  
- Datadog  
- Splunk Observability  
- Honeycomb  

### Incident & Security Engineering
- PagerDuty  
- Opsgenie  
- Rootly  
- Chronicle Security  
- Wazuh  
- Elastic Security  

### Resilience & Chaos Engineering
- Chaos Mesh  
- LitmusChaos  
- Gremlin (Fault Injection)  
- AWS Fault Injection Simulator  

### CI/CD & Supply Chain Security
- GitHub Advanced Security  
- Trivy  
- ChainGuard  
- Sigstore / Cosign  
- OPA + Conftest  
- SLSA Framework  

---

## 📌 Case Studies — With Videos & Resources

### **1. Netflix — Chaos Engineering & Resilience**
- Chaos Engineering Principles (official):  
  https://netflix.github.io/chaosmonkey/
- Netflix Tech Blog: Resilience Engineering  
  https://netflixtechblog.com/tagged/chaos-engineering

---

### **2. Google — SRE + BeyondCorp Security**
- Google SRE Overview (YouTube):  
  https://www.youtube.com/watch?v=uTEL8Ff1Zvk
- BeyondCorp Security Architecture (Google Cloud):  
  https://cloud.google.com/beyondcorp
- SRECon Talk: *BeyondCorp: A New Approach to Enterprise Security*  
  https://www.youtube.com/watch?v=YG0sb7wP6CE

---

### **3. LinkedIn — Large-Scale SRE Culture & Reliability**
- LinkedIn Engineering: SRE Practices  
  https://engineering.linkedin.com/blog/topic/sre
- Kafka & Reliability (LinkedIn Engineering)  
  https://engineering.linkedin.com/apache-kafka

---

### **4. Amazon — Resilience Hub & Fault Tolerance**
- AWS Resilience Hub Overview  
  https://aws.amazon.com/resilience-hub/
- Amazon Builders' Library: *Timeouts, Retries, and Backoff*  
  https://aws.amazon.com/builders-library/timeouts-retries-and-backoff/

---

### **5. Dropbox — Secure SRE Patterns & Infrastructure Evolution**
- Dropbox Security Engineering Blog  
  https://dropbox.tech/tag/security
- Dropbox Reliability Journey  
  https://dropbox.tech/infrastructure

---

## 🤝 Contributing

PRs are welcome!  
Submit improvements, research papers, new tools, or practical guides relevant to RESS.

---

## 📄 License

MIT License.

