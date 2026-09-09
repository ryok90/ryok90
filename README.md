<div align="center">

# Rodrigo Yokota

**Platform Engineer @ [Zephyr Cloud](https://zephyr-cloud.io)** · Module Federation whisperer · full-stack since 2018

[![Website](https://img.shields.io/badge/yokota.dev-00D9C0?style=for-the-badge&logo=nextdotjs&logoColor=121212&labelColor=121212)](https://yokota.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-00D9C0?style=for-the-badge&logoColor=121212&labelColor=121212)](https://www.linkedin.com/in/rodrigo-yokota/)
[![Email](https://img.shields.io/badge/rodrigo@yokota.dev-00D9C0?style=for-the-badge&logo=maildotru&logoColor=121212&labelColor=121212)](mailto:rodrigo@yokota.dev)
[![Résumé](https://img.shields.io/badge/Résumé-00D9C0?style=for-the-badge&logo=readdotcv&logoColor=121212&labelColor=121212)](https://drive.google.com/uc?export=download&id=1Q_JRCt0mZmhP7ieBWEMdeMBt8gAwfTA8)

</div>

---

### `whoami`

```ts
const rodrigo = {
  role: 'Platform Engineer @ Zephyr Cloud',
  from: 'Maringá, PR 🇧🇷',
  since: 2018,
  doing: ['module federation', 'build tooling', 'cloud deploy pipelines', 'DX that does not hurt'],
  stack: ['TypeScript', 'Node.js', 'React', 'Rspack', 'Webpack', 'Vite', 'Nx', 'AWS'],
  alsoWrites: ['Swift', 'Python', 'PHP', 'Dart', 'a suspicious amount of YAML'],
  motto: 'Ship it, then make it boring.',
} as const;
```

### What I actually do all day

Micro-frontends are easy to draw and hard to ship. My job is the arrow nobody likes.

```mermaid
flowchart LR
  A[Remote app] -->|build| B[Rspack / Webpack / Vite]
  B -->|Module Federation| C[Zephyr Cloud]
  C -->|versioned deploy| D[Edge]
  D -->|resolved at runtime| E[Host shell]
  E -.->|something broke| F((me))
  F -.->|fix the plugin, not the symptom| B
```

- Build-tool plugins and integrations across **webpack, Rspack, Vite, Rollup, Nx, Next.js, Astro, Tauri**
- Module Federation consulting: turning "why is React loaded twice" into a Monday-morning answer
- Reference examples, repros, and the unglamorous issue-replication repos that make bugs fixable

### Track record

| When | Where | What |
| --- | --- | --- |
| 2023 → now | **Valor Software / Zephyr Cloud** | Zephyr platform features, Module Federation consulting, standards & architecture |
| 2023 | **Vaullti** (Seattle) | Digital-twin protection service: AWS CDK, event-driven workflows, cost-first design |
| 2021 → 2023 | **Groundbreaker** (Chicago) | Fund administration: React → federated micro-frontends, Go → Node.js serverless |
| 2020 → 2021 | **Gazin Tech** | E-commerce apps, new mobile app + APIs, checkout as a micro-frontend |
| 2019 → 2020 | **Vivaworks** | Corporate suite: PHP/Zend, Flutter app, the module everyone was afraid of |
| 2015 → 2019 | **Full House** | Ran ops & finance. Automated my own job with VBA. That's how this started. |

<sub>AWS Certified Cloud Practitioner · Computer Science @ UEM (unfinished, still curious)</sub>

### Toolbox

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=121212)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Rspack](https://img.shields.io/badge/Rspack-F93920?style=flat-square&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=121212)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Nx](https://img.shields.io/badge/Nx-143055?style=flat-square&logo=nx&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logoColor=121212)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=121212)

### Side quests

| Project | The pitch |
| --- | --- |
| [**guaranate**](https://github.com/ryok90/guaranate) | Native macOS keep-awake CLI in Swift. Talks to IOKit directly, does **not** wrap `caffeinate`. Named after guaraná, because Brazil solves caffeine differently. `brew install ryok90/guaranate/guaranate` |
| [**nextjs-mf-examples**](https://github.com/ryok90/nextjs-mf-examples) | Next.js ↔ Module Federation, working, with receipts |
| [**yokota.dev**](https://github.com/ryok90/yokota.dev) | My corner of the internet. Next.js, teal, opinionated |
| [**tapple**](https://github.com/ryok90/tapple) | The board game Tapple, dragged onto the web |
| [**zmk-config**](https://github.com/ryok90/zmk-config) | 36-key Corne layout. Yes, I have opinions about layers |

### Fun facts

- I spent four years running events ops before writing code professionally. Spreadsheets radicalized me.
- If a bug can't be reproduced in a clean repo, it isn't a bug yet — hence the small pile of `*-issue-replication` repos.
- I'll take a boring solution over a clever one, right up until the boring one gets slow.

<div align="center">

[![Followers](https://img.shields.io/github/followers/ryok90?style=for-the-badge&color=00D9C0&labelColor=121212&logo=github&logoColor=00D9C0)](https://github.com/ryok90?tab=followers)
[![Stars](https://img.shields.io/github/stars/ryok90?affiliations=OWNER&style=for-the-badge&color=00D9C0&labelColor=121212&logo=github&logoColor=00D9C0)](https://github.com/ryok90?tab=repositories&q=&type=source&sort=stargazers)
[![Profile views](https://komarev.com/ghpvc/?username=ryok90&style=for-the-badge&color=00D9C0&label=PROFILE+VIEWS)](https://github.com/ryok90)

<sub>Want to talk federated frontends, build pipelines, or keyboards? <a href="mailto:rodrigo@yokota.dev">rodrigo@yokota.dev</a></sub>

</div>
