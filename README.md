<div align="center">

# Matheus Felipe

### Full Stack Developer · DevOps · Cybersecurity

Building software from **application architecture to infrastructure**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-felipe-silva-de-moraiss)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/oblivius321)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matheusfelipe3839@gmail.com)

</div>

---

## About Me

I'm a Brazilian software developer focused on building **complete systems**, combining software engineering, infrastructure, automation and security.

My work goes beyond writing application code. I enjoy understanding the entire environment where software operates — from the user interface and backend architecture to containers, Linux servers, networking, monitoring and security.

Currently, my main areas of interest are:

- Full Stack Development
- Backend Engineering
- DevOps & Infrastructure
- Cybersecurity
- System Architecture
- Automation
- Android Enterprise / MDM
- Artificial Intelligence

I particularly enjoy turning **real operational problems into software products**.

---

## Tech Stack

<p align="center">
  <img src="./assets/tech-icons-loop.svg" width="100%" alt="Technology Stack" />
</p>

### Development

`Python` · `JavaScript` · `TypeScript` · `React` · `Node.js` · `FastAPI` · `REST APIs` · `WebSockets`

### Data

`PostgreSQL` · `MySQL` · `SQLite` · `Redis` · `SQL`

### DevOps & Infrastructure

`Docker` · `Docker Compose` · `Linux` · `Git` · `GitHub` · `VPS` · `Networking` · `CI/CD`

### Observability

`Zabbix` · `Grafana` · `Webhooks` · `Real-time Monitoring`

### Security

`Application Security` · `Authentication` · `RBAC` · `Encryption` · `Network Security` · `Ethical Hacking`

---

## GitHub Analytics

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=oblivius321&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117" alt="Matheus Felipe GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=oblivius321&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117" alt="Top Languages" />
</p>

---

# Featured Project

## GIM — Gestão de Inventário e Mobilidade

> An enterprise platform designed to centralize **IT Asset Management, Mobile Device Management, Service Desk, Monitoring and Logistics operations**.

GIM started from a real operational problem.

The organization needed better control over corporate assets and Android devices while several processes still depended on spreadsheets and disconnected tools.

Instead of creating another isolated inventory application, I designed a platform capable of bringing these operations together.

Today, GIM is evolving into a modular enterprise platform.

### IT Asset Management

- Hardware and equipment inventory
- Asset lifecycle management
- Purchase and supplier information
- Warranty tracking
- Asset assignment and transfers
- Operational history
- Audit trails
- Document and responsibility term generation
- Excel exports and reports

### Mobile Device Management

Custom Android Enterprise architecture for managing corporate devices.

- Android Device Owner provisioning
- QR Code enrollment
- Kiosk Mode
- Remote device policies
- Application management
- Device telemetry
- Secure enrollment
- Silent application installation
- Device status monitoring
- Real-time communication with the management platform

The MDM architecture separates device administration from the operational application:

```text
                 Android Device
                       │
                       ▼
              ┌─────────────────┐
              │     GIM DPC     │
              │  Device Owner   │
              └────────┬────────┘
                       │
               Secure Enrollment
                       │
                       ▼
              ┌─────────────────┐
              │   GIM Backend   │
              │ Commands / API  │
              └────────┬────────┘
                       │
                 Policies / Apps
                       │
                       ▼
              ┌─────────────────┐
              │    GIM Kiosk    │
              │ Operational App │
              └─────────────────┘
