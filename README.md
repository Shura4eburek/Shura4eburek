<h1 align="center">Mamoru</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&center=true&vCenter=true&width=520&height=45&lines=Full+Stack+Developer;Next.js+%C2%B7+Python+%C2%B7+C%23+%C2%B7+PostgreSQL;I+ship+products%2C+not+demos" alt="Full Stack Developer" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ukraine-005BBB?style=for-the-badge&labelColor=FFD500&color=005BBB" alt="Ukraine" />
  <img src="https://img.shields.io/badge/Open%20to%20work-remote-2ea44f?style=for-the-badge" alt="Open to work" />
</p>

---

I build things end-to-end — Postgres schema, Redis caching, React UI, SEO, tests, deploy, monitoring — and then keep them running. By day I diagnose and build PCs at a service centre, where I also wrote the CRM, the remote-diagnostics platform and the bots my department uses every shift.

Everything below is live and in real use. None of it is tutorial work.

---

## Featured

<table>
<tr>
<td width="50%" valign="top">

### 🎬 Anime Mamoru
**Anime streaming platform · in production**

Catalogue and HLS player with Shikimori account sync, multi-source dubbing selection and a TV mode. Four external APIs behind a normalised Postgres cache and a two-tier Redis layer. ru/uk locales, JSON-LD, a 2 500-page sitemap. **1 264 tests**, ~1 700 commits, deployed to Vercel *and* a self-hosted VPS with a build gate and rollback.

`Next.js 15` `React 19` `TypeScript` `Supabase` `Redis` `PostgreSQL`

[**Live →**](https://anime.mamoru.fun)

</td>
<td width="50%" valign="top">

### 🔧 sz-diag
**Remote hardware diagnostics · ~470 tests**

Diagnose a client machine by service-ticket number, over the network, with **zero permanent footprint**. A temporary agent opens a portable sshd under SYSTEM, registers with a central hub, and rolls itself back completely on close — hotkey, host command or watchdog. Ships reboot-timeline reconstruction, SMART/WHEA probes and a GPU resolver that maps a PCI hardware ID to the exact partner SKU.

`C# / .NET` `ASP.NET Core` `SignalR` `PowerShell` `SQLite`

[**Repo →**](https://github.com/Shura4eburek/sz-diag)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🪞 Kagami
**AirPlay receiver for Windows · GPLv3**

A UxPlay fork turned into something you'd actually use: hardware D3D12 decode, latency tuning out of the box, two simultaneous mirroring sessions. The interesting part is an mDNS reflector — stock Bonjour announced the service only on the Tailscale interface, so the reflector re-announces it on the LAN with the right address. That's what makes iPhones see the PC at all.

`C` `GStreamer` `Direct3D12` `Python`

[**Repo →**](https://github.com/Shura4eburek/Kagami)

</td>
<td width="50%" valign="top">

### 📋 CRM-Service
**Service-centre CRM · used daily at work**

Ticket queue, call-centre requests, knowledge base, parcel tracking and payroll. Four roles enforced in middleware over signed session cookies, TSV bulk import, full-text KB search with one-click publishing to Telegraph, Nova Poshta tracking, automatic Google Drive backups on a cron schedule.

`Next.js 15` `PostgreSQL` `Firebase Auth` `shadcn/ui`

</td>
</tr>
</table>

---

## Also on the shelf

| | Project | Stack |
|:--:|---|---|
| 🗣️ | [**OmniChat**](https://github.com/Shura4eburek/OmniChat) — Minecraft mod that speaks chat aloud with positional audio and floating bubbles; server distributes TTS models to clients | `Java 21` `Fabric` `sherpa-onnx` `ONNX` |
| 📊 | [**Metricon**](https://github.com/Shura4eburek/Metricon) — metrics dashboard my bots push into over HTTP; drop-in client makes instrumenting a new bot a two-line change | `Django` `Chart.js` `PostgreSQL` |
| 🏷️ | [**SN-print**](https://github.com/Shura4eburek/SN-print) — QR/Code128 generator for service labels, webhook bot plus two Telegram Mini Apps | `Python` `python-telegram-bot` |
| 🔌 | [**SvitloBot VoltKeeper**](https://github.com/Shura4eburek/SvitloBot_VoltKeeper) — switches Windows power plans the moment the grid drops, so a power station lasts longer | `Python` `pystray` `Telethon` |
| 🎮 | [**FableStats**](https://github.com/Shura4eburek/FableStats) — Spigot plugin, 10+ PlaceholderAPI placeholders, EN/RU/UK | `Java` `Spigot` |
| ⚡ | **TeleSvitlo** — blackout monitoring: userbot parses a source channel, Redis history, FastAPI dashboard | `Telethon` `FastAPI` `Redis` |
| 🔍 | **Semantic Clustering Tool** — SEO keyword clustering: multilingual embeddings + SERP overlap, pluggable LLM providers | `React` `Vite` `NLP` `LLM` |
| 📨 | **odoo-telegram-notifier** — Odoo tasks to Telegram from behind a corporate VPN; real-time or digest, zero dependencies | `Python (stdlib)` `XML-RPC` |

---

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
</p>

---

## How I work with AI agents

I write everything through AI agents — Claude Code daily. A year in, the thing that actually decides the outcome isn't the prompt, it's the context the agent starts with:

- **every repo carries its own context file** — architecture, conventions, gotchas, and a list of mistakes already made, so the agent doesn't re-litigate solved problems;
- **big changes go through a written plan first**, then step by step, each step closed by tests;
- **I verify by hand.** An agent saying "done" is a claim, not evidence — that's why the projects above run in production instead of sitting in a demo folder.

---

## Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Shura4eburek&show_icons=true&hide_border=true&include_all_commits=true&theme=transparent&title_color=3178C6&icon_color=3178C6" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shura4eburek&layout=compact&hide_border=true&langs_count=8&theme=transparent&title_color=3178C6" />
</p>

---

## Reach me

<p>
  <a href="https://t.me/mamoruoff"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://anime.mamoru.fun"><img src="https://img.shields.io/badge/anime.mamoru.fun-FF6B6B?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
</p>
