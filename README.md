# Kelvin Fernandes

**DevOps Engineer** and student at FACAPE. I turn manual processes into simple, repeatable pipelines, and I like building systems that are easy to run: one command to start, safe to re-run, and clear about what failed.

> 🇧🇷 Engenheiro DevOps e estudante na FACAPE. Gosto de transformar processos manuais em pipelines simples e repetíveis. A maioria dos projetos abaixo está documentada em português.

## Projects

**[radar-licitacoes](https://github.com/kelvinfff/radar-licitacoes)**: an assistant that answers questions about Brazilian public procurement using open data from PNCP, citing its sources. It's designed to run like a production system. Stage 1 of 8, in progress: an ingestion pipeline with resumable checkpoints, idempotent upserts, exponential backoff on 429/5xx, and a Postgres advisory lock that allows only one run at a time.
<br><sub>Python · PostgreSQL + pgvector · Alembic · Docker Compose</sub>

**[banco-de-residuos](https://github.com/kelvinfff/banco-de-residuos)**: a marketplace that connects agricultural waste and by-products with buyers who can reuse them, starting in the São Francisco Valley. A single `docker compose up` starts the whole stack (API, web app, database), applies the migrations and loads the demo data.
<br><sub>TypeScript · Express · Prisma · Next.js · PostgreSQL · Docker</sub>

**[kelvinfernandes.me](https://github.com/kelvinfff/kelvinfff.github.io)**: my portfolio site. It's containerized (nginx in production) and a GitHub Actions workflow deploys it to GitHub Pages on every push to `main`.
<br><sub>Astro · Docker · GitHub Actions · GitHub Pages</sub>

**[api-produtos-cloudflare](https://github.com/kelvinfff/api-produtos-cloudflare)**: a product API that runs on Cloudflare Workers, backed by a D1 database provisioned with Terraform.
<br><sub>Cloudflare Workers · D1 · Terraform · Vitest</sub>

## Tech Stack

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Learning:**
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

## Connect

[![Website](https://img.shields.io/badge/kelvinfernandes.me-000000?style=flat-square&logo=astro&logoColor=white)](https://kelvinfernandes.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kelvin-fernandes-491444292/)

---

<p align="center"><sub>Always learning. Always automating.</sub></p>
