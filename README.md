# ☸️ KubeCon + CloudNativeCon India 2026 Highlights

> Community meetup presentation by Jaydipsinh Jadeja

---

## 🎯 About

This repository contains my meetup presentation summarizing the biggest technical trends from KubeCon + CloudNativeCon India 2026.

Topics include:

- AI + Kubernetes
- Platform Engineering
- Crossplane
- Kyverno
- GitOps
- LitmusChaos
- vLLM
- KServe
- Production LLMs

---

## 📖 Agenda

- Introduction
- AI + Cloud Native
- LLM Inference
- Platform Engineering
- Crossplane
- Policy as Code
- Chaos Engineering
- Key Takeaways

---

## 🏗 Architecture

### Production LLM Stack

```text
User
   │
API Gateway
   │
KServe
   │
vLLM
   │
GPU
   │
Llama
```

---

## 🚀 Platform Engineering

```text
Developer

↓

Crossplane Claim

↓

Composition

↓

AWS

↓

RDS
```

---

## 🔐 Policy as Code

```text
Developer

↓

Kyverno

↓

Validate

↓

Mutate

↓

Deploy
```

---

## 💥 Chaos Engineering

```text
Production

↓

Inject Failure

↓

Observe

↓

Improve
```

---

## 📚 CNCF Projects Covered

- Kubernetes
- Crossplane
- Kyverno
- LitmusChaos
- KServe
- Argo CD
- Score
- vLLM

---

## 📷 Photos

(Images from KubeCon India 2026)

---

## 🙌 Acknowledgements

Thanks to CNCF, speakers, maintainers, and the Kubernetes community.
