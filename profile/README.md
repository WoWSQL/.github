<br />

<p align="center">
  <a href="https://wowsql.com">
    <img src="./images/banner.svg" alt="WoWSQL — Open Source Postgres Backend" width="900" />
  </a>
</p>

<p align="center">
  <a href="https://wowsql.com">
    <img src="https://wowsql.com/logo/wowbaselogo.png" alt="WoWSQL" width="220" />
  </a>
</p>

<h1 align="center">WoWSQL</h1>

<p align="center">
  <strong>The open-source Postgres backend for modern apps.</strong><br />
  Database · Auth · Storage · Realtime · REST · MCP — cloud or self-hosted.
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=2DD4BF&center=true&vCenter=true&multiline=true&width=720&height=70&lines=Build+backends+in+minutes%2C+not+weeks.;Postgres+%C2%B7+Auth+%C2%B7+Storage+%C2%B7+Realtime+%C2%B7+MCP;Cloud+or+self-host+with+one+compose+up.">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=2DD4BF&center=true&vCenter=true&multiline=true&width=720&height=70&lines=Build+backends+in+minutes%2C+not+weeks.;Postgres+%C2%B7+Auth+%C2%B7+Storage+%C2%B7+Realtime+%C2%B7+MCP;Cloud+or+self-host+with+one+compose+up." alt="WoWSQL typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://wowsql.com"><img src="https://img.shields.io/badge/Website-wowsql.com-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://wowsql.com/docs"><img src="https://img.shields.io/badge/Docs-Get%20Started-0EA5E9?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs" /></a>
  <a href="https://discord.com/invite/AnBzbqRFU9"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://x.com/WoWSQL"><img src="https://img.shields.io/badge/X-@WoWSQL-111111?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://github.com/WoWSQL/WoWSQL"><img src="https://img.shields.io/github/stars/WoWSQL/WoWSQL?style=for-the-badge&logo=github&color=2DD4BF&labelColor=0B1220" alt="Stars" /></a>
</p>

---

## Why WoWSQL?

WoWSQL turns Postgres into a full backend platform — so you ship products instead of wiring auth, APIs, storage, and realtime from scratch.

| | |
|---|---|
| **Postgres Database** | Every project is real Postgres — portable, RLS-ready, SQL-first |
| **Authentication** | Email, OAuth, magic links, OTP, and Row Level Security |
| **Auto REST API** | Schema → PostgREST endpoints instantly |
| **Storage** | Buckets, uploads, and access policies built in |
| **Realtime** | WebSocket subscriptions for live data changes |
| **MCP Server** | Connect Claude, Cursor, and other agents to your database |
| **Dashboard** | Table editor, SQL editor, API docs, and project controls |
| **Self-host or Cloud** | `docker compose up` locally, or ship on [wowsql.com](https://wowsql.com) |

---

## Start in seconds

**Cloud**

```bash
# 1. Create a project at https://wowsql.com
# 2. Install the SDK
npm install @wowsql/sdk
```

```ts
import { createClient } from '@wowsql/sdk'

const wow = createClient(WOWSQL_URL, WOWSQL_KEY)

const { data } = await wow.from('users').select('*')
```

**Self-hosted**

```bash
git clone https://github.com/WoWSQL/WoWSQL.git
cd WoWSQL/docker
cp .env.example .env
docker compose pull && docker compose up -d
```

Dashboard → http://localhost:3000 · API → http://localhost:8080

---

## Open source

| Project | Description |
|---|---|
| [**WoWSQL**](https://github.com/WoWSQL/WoWSQL) | Self-hosted Postgres BaaS — Auth, Storage, Realtime, Studio |
| [**TypeScript SDK**](https://github.com/WoWSQL/WoWSQL-typescript) | Official JS/TS client |
| [**Python SDK**](https://github.com/WoWSQL/WoWSQL-Python) | Official Python client |
| [**Go SDK**](https://github.com/WoWSQL/wowsql-go) | Official Go client |
| [**PHP SDK**](https://github.com/WoWSQL/WoWSQL-sdk-php) | Official PHP client |
| [**Swift SDK**](https://github.com/WoWSQL/WoWSQL-swift) | Official Swift client |
| [**MCP Server**](https://github.com/WoWSQL/MCP-Server) | AI agent access to your database |
| [**VS Code**](https://github.com/WoWSQL/vs-code) | Query and manage WoWSQL from the editor |

---

## Build with us

<p align="center">
  <a href="https://wowsql.com">Website</a> ·
  <a href="https://wowsql.com/docs">Documentation</a> ·
  <a href="https://github.com/WoWSQL/WoWSQL">Self-hosting</a> ·
  <a href="https://discord.com/invite/AnBzbqRFU9">Discord</a> ·
  <a href="https://x.com/WoWSQL">X / Twitter</a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1200&color=94A3B8&center=true&vCenter=true&width=560&lines=Star+the+repo.+Ship+something+WOW." alt="Footer typing" />
</p>

<p align="center">
  <sub>Built with ❤️ by the WoWSQL team · Apache 2.0</sub>
</p>
