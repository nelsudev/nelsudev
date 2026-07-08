# Hey, I'm Nelson 👋

**Platform engineer who ships things that run themselves** — Kubernetes
operators, GitOps pipelines, self-hosted infrastructure with hard isolation
walls. Based in Portugal 🇵🇹 · [nelsoncarv.work](https://nelsoncarv.work)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![FluxCD](https://img.shields.io/badge/FluxCD-5468FF?style=flat-square)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logoColor=white)

## 🚢 Things I've built in the open

### 🕵️ [zeedfai-kubernetes-operator-gitops](https://github.com/nelsudev/zeedfai-kubernetes-operator-gitops)

A Kubernetes operator (Go) that runs fraud-scoring stream pipelines — and
**proves it can be trusted with them**: consumer-lag autoscaling, SLO
self-healing, canary with automatic rollback, all delivered through FluxCD.
Every claim verified with a live run (burst 3 000 ev/s → replicas 2→10→2;
a 50%-fault canary rolled back automatically in ~80 s), with the bugs found
along the way documented in the FAQ and postmortems — not hidden.

### 🏰 [vps-multi-tenant-sovereign](https://github.com/nelsudev/vps-multi-tenant-sovereign)

One VPS, many tenants, zero awareness of each other. Incus + rootless
Docker + ZFS + per-tenant Cloudflare Tunnels — a full design study plus a
ready-to-run Ansible template. Built for running untrusted workloads (AI
agents included) where the neighbor shouldn't just be blocked; it should
**not exist**.

## 🧭 How I work

- **Verify live, then write it down.** A feature isn't done when it
  compiles — it's done when it survived a burst test, a killed broker, or a
  deliberately broken canary, and the run is on the record.
- **GitOps as a discipline, not a buzzword.** The cluster reflects Git,
  never the other way around — my operators refuse to fight Flux over the
  source of truth by design.
- **Honest docs.** Every design decision ships with its trade-offs and its
  failure modes; my FAQs are built from the problems I actually hit.
- **AI-assisted, engineer-driven.** I build with Claude (Fable/Claude Code)
  as a daily tool — the architecture conversations, the verification runs,
  and the judgment stay mine.

## 📫 Reach me

[![Website](https://img.shields.io/badge/nelsoncarv.work-2a78d6?style=flat-square&logo=googlechrome&logoColor=white)](https://nelsoncarv.work)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nelsoncarv)
