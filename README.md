# Aurélio Maicá — Public Engineering Portfolio

> Curated **public** work for recruiters and hiring managers.  
> No private client code. No NDAs. Only what you can clone and inspect.

**Profile:** [github.com/amaica](https://github.com/amaica) · **LinkedIn:** [aurelio-maica](https://www.linkedin.com/in/aurelio-maica-616a13228)

---

## 30-second pitch

Backend engineer with **17 years** in corporate systems (public sector + multinationals).  
Strong on **Java / Spring Boot APIs**, **Brazilian fiscal integrations**, and **vision/biometrics** services.

**Open-source signal:** contributor to **[t3wv/nfse](https://github.com/t3wv/nfse)** (NFS-e Brazil) with a production-driven PR after NT 008/2026 suspended the official DANFSe ADN API.

---

## Open source contributions (verified on GitHub)

| Project | Role / evidence | Link |
|---------|-----------------|------|
| **[t3wv/nfse](https://github.com/t3wv/nfse)** | Upstream PR — local DANFSe PDF via Jasper (NT 008/2026) | [#55 (open)](https://github.com/t3wv/nfse/pull/55) |
| **[rsynki](https://github.com/rsynki)** | Org member (public) | [github.com/rsynki](https://github.com/rsynki) |

**Fork used for NFS-e work:** [amaica/nfse2](https://github.com/amaica/nfse2) (from `t3wv/nfse`).

> Note: other public forks (Chatwoot, Vision Pilot, etc.) are exploration/study. The **hiring-relevant OSS** line is **t3wv/nfse** + **rsynki**.

---

## Featured repositories (owned / public)

| Project | Why it matters | Stack | Repo |
|---------|----------------|-------|------|
| **banco-digital** | Clean challenge API: transfer + statement + notification | Spring Boot 3, MySQL, Flyway, Swagger | [link](https://github.com/amaica/banco-digital) |
| **desafio-votacao** | End-to-end product: timed voting + React UI | Spring Boot, React, MySQL, Compose | [link](https://github.com/amaica/desafio-votacao) |
| **api-dfe** | SEFAZ inbound NF-e distribution microservice | Spring Boot 3, java-nfe, jobs | [link](https://github.com/amaica/api-dfe) |
| **api-recognition-facenetMtcnn** | Face detect + embed + match as REST | Java, DL4J, FaceNet, MTCNN | [link](https://github.com/amaica/api-recognition-facenetMtcnn) |
| **openalpr** | ALPR daemon/tooling experiments | OpenALPR / plate recognition | [link](https://github.com/amaica/openalpr) |
| **sap-btp-pilot** | SemVer + promotion DEV/HOM/PROD | Git governance | [link](https://github.com/amaica/sap-btp-pilot) |
| **quarkus-kafka-microservices** | Event-driven trade pipeline: CDI/Arc, Kafka emit/consume, OIDC + token propagation, Panache, Quartz, BFF OpenAPI | Quarkus 2.x, CDI, Kafka, OIDC, Panache, PostgreSQL, Docker | [link](https://github.com/amaica/quarkus-kafka-microservices) |

---

## Architecture snapshot (typical API I ship)

```text
                    ┌──────────────┐
   Clients ───────► │  REST API    │──► Auth (Basic / JWT)
                    │  Spring Boot │
                    └──────┬───────┘
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
         Migrations     Domain       Jobs / SEFAZ
          (Flyway)     Services      / CV / Jasper
              │            │            │
              └────────────┴─────► MySQL / files
```

---

## How to evaluate me in under 10 minutes

1. Read **[t3wv/nfse#55](https://github.com/t3wv/nfse/pull/55)** — real fiscal OSS contribution  
2. Open **[banco-digital](https://github.com/amaica/banco-digital)** → `./init.sh` → Swagger  
3. Skim **[desafio-votacao](https://github.com/amaica/desafio-votacao)** → Docker Compose full stack  
4. Glance **[api-dfe](https://github.com/amaica/api-dfe)** + **[api-recognition-facenetMtcnn](https://github.com/amaica/api-recognition-facenetMtcnn)**
5. Skim **[quarkus-kafka-microservices](https://github.com/amaica/quarkus-kafka-microservices)** → Docker Compose + Kafka UI

---

## What I am looking for

- Backend / platform roles (Java or polyglot with strong API design)
- Teams that value **integrations, observability, and safe delivery**
- Domains: enterprise, public sector, fintech-adjacent, fiscal BR, security/vision

---

## Languages

| | |
|--|--|
| Portuguese | Native |
| English | Technical reading / writing |

---

## License / scope

This portfolio index is public documentation. Individual projects keep their own licenses.  
**Private / client work is intentionally excluded.**
