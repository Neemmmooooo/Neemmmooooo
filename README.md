<p align="center">
  <img src="assets/readme/banner.svg" width="100%" alt="Alexandre Pierre. France, EDHEC work-study student. I build applied AI and data products end to end, and I document what I stop.">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alexandre-pierre-8334aa259/"><img src="assets/readme/btn-linkedin.svg" height="38" alt="LinkedIn"></a>
  <a href="mailto:alexandre.gf.pierre@gmail.com"><img src="assets/readme/btn-email.svg" height="38" alt="Email me"></a>
  <a href="https://daemon-tech.fr"><img src="assets/readme/btn-daemon.svg" height="38" alt="daemon-tech.fr"></a>
</p>

I am a work-study student at EDHEC building **applied AI, data and product systems end to end**: framing the problem, designing the architecture, writing the code, shipping it, and writing an honest review when a project should stop. My current focus is **Kalk**, a real-estate analysis platform I build with a partner who leads the financial models. Everything else on this page either runs today or ended with a documented decision.

## 🛠️ What I'm building

<p align="center">
  <img src="assets/readme/card-kalk.svg" width="49%" alt="Kalk: professional-grade deal analysis for real-estate investors. In progress.">
  <a href="https://github.com/Neemmmooooo/second-brain"><img src="assets/readme/card-daemon.svg" width="49%" alt="Daemon: a self-organising second brain. Live."></a>
  <a href="https://github.com/Neemmmooooo/ai-workspace"><img src="assets/readme/card-ai-workspace.svg" width="49%" alt="AI Workspace: one workspace for any model, with automatic provider failover. Live."></a>
  <img src="assets/readme/card-meme-alpha.svg" width="49%" alt="Meme Alpha: quantitative research on Solana memecoins. On hold.">
</p>

<p align="center">
  Explore: <a href="https://github.com/Neemmmooooo/second-brain">Daemon</a> · <a href="https://github.com/Neemmmooooo/ai-workspace">AI Workspace</a> · more repositories coming soon
</p>

## 📊 By the numbers

<p align="center">
  <img src="assets/readme/stats.svg" width="100%" alt="6 projects built end to end · 13 model providers behind one adapter · 3,000 curve states matched to the official SDK · 26.5K on-chain trades collected and decoded · 2 of 2 stopped projects with a written post-mortem">
</p>

> [!IMPORTANT]
> **How I work.** I start from a concrete problem and build the smallest system that genuinely solves it. I de-risk the hardest assumptions first (willingness to pay, data access, barriers to entry) before polishing anything. And I document what I stop: a project ended deliberately is worth more than one left to drift.

<details>
<summary><b>Context, goals and status for each project</b></summary>
<br>

<table>
  <tr>
    <td width="84" align="center"><img src="assets/logos/kalk.svg" width="64" alt="Kalk"></td>
    <td>
      <h3>Kalk &nbsp;🟢 <sub>In progress</sub></h3>
      <b>Context:</b> real-estate deal analysis still relies on hand-built spreadsheets that are hard to audit and share, while professional tools are either complex or reserved for large firms.<br>
      <b>Goal:</b> give investors professional-grade analysis tools that are simpler to use and more accurate.<br>
      <b>Status:</b> final stage of development, with a waitlist launch in preparation. I build the full stack on my own; a partner with real-estate expertise leads the financial models. Private codebase, public showcase coming soon.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/daemon.svg" width="64" alt="Daemon"></td>
    <td>
      <h3><a href="https://github.com/Neemmmooooo/second-brain">Daemon</a> &nbsp;🟡 <sub>Live · no longer actively developed</sub></h3>
      <b>Context:</b> what I learn (courses, projects, reading) ends up scattered, and I struggle to retrieve what I already know.<br>
      <b>Goal:</b> a second brain that organises itself and surfaces the right information when I ask a question.<br>
      <b>What I built:</b> an AI knowledge architect that files notes into a fixed taxonomy, tags them, flags contradictions with existing knowledge and compresses older notes. It fails over between model providers during outages (Groq → Cerebras). Notes remain plain Markdown in GitHub, readable by Obsidian, Claude and the web app.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/ai-workspace.svg" width="64" alt="AI Workspace"></td>
    <td>
      <h3><a href="https://github.com/Neemmmooooo/ai-workspace">AI Workspace</a> &nbsp;🟡 <sub>Live · no longer actively developed</sub></h3>
      <b>Context:</b> every model provider has its own interface, quotas and outages, and switching tools mid-task breaks the flow.<br>
      <b>Goal:</b> work with any model without worrying about which provider is available.<br>
      <b>What I built:</b> a streaming chat workspace with 13 providers behind a single adapter layer, automatic failover on outages or rate limits, task-based model routing and encrypted API keys. Built with Next.js and Postgres.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/meme-alpha.svg" width="64" alt="Meme Alpha"></td>
    <td>
      <h3>Meme Alpha &nbsp;⏸️ <sub>Research on hold</sub></h3>
      <b>Context:</b> public memecoin analyses assume unrealistic entries at the launch price, leak future information into their indicators and ignore trading costs.<br>
      <b>Goal:</b> determine what can honestly be said about price continuation in Solana memecoins, using rigorous data and a realistic execution model.<br>
      <b>What I built:</b> an on-chain data collector, momentum indicators, labelling free of look-ahead bias and an execution simulator validated against the official SDK. The dataset is still too small to draw conclusions, so the project documents its limitations and what it would take to go further. <i>Research project, not financial advice.</i> Public repository coming soon.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/reelhook.png" width="64" alt="ReelHook"></td>
    <td>
      <h3>ReelHook &nbsp;⚫ <sub>Discontinued · public post-mortem coming soon</sub></h3>
      <b>Context:</b> Instagram tools schedule or generate content, but none of them shows which content actually drives revenue.<br>
      <b>Goal:</b> attribute every piece of content to the messages, calls, sales and revenue it generates.<br>
      <b>Why it stopped:</b> not feasible. The required data was unreliable, small accounts had limited ability to pay, and large brands were not interested. <b>Lesson:</b> validate willingness to pay and data access before building.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/synaptic-ia.svg" width="64" alt="Synaptic IA"></td>
    <td>
      <h3>Synaptic IA &nbsp;⚫ <sub>Discontinued · public post-mortem coming soon</sub></h3>
      <b>Context:</b> brands judge content on intuition, through focus groups, or with fMRI studies costing tens of thousands of euros.<br>
      <b>Goal:</b> predict how the brain responds to a piece of content across audiences (for example, by generation) before any media spend.<br>
      <b>Why it stopped:</b> insufficient resources (capital, technology, specialised team), and a major player released an equivalent model. <b>Lesson:</b> assess barriers to entry and the competitive landscape early.
    </td>
  </tr>
</table>

</details>

## 🧰 Tools & technologies

**AI & agents**<br>
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claudecode&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?style=flat-square)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-333333?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Cerebras](https://img.shields.io/badge/Cerebras-1B8A6F?style=flat-square)

**Development**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-333333?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black)

**Data & quality**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)

**Deployment & product**<br>
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Creative & knowledge management**<br>
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

<sub>Focus areas: applied AI · data · full-stack development · product</sub>
