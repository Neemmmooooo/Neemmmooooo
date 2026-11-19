### Bonjour, je suis Alexandre 👋

Étudiant à l'EDHEC en alternance, je construis des projets en IA appliquée, data et produit.
Je développe seul, de bout en bout, avec l'ambition de fonder des startups.
Ici : tout ce que j'ai lancé, ce qui est en cours, ce qui fonctionne, et ce que j'ai arrêté, avec les raisons.

> **Summary (EN):** EDHEC work-study student building projects in applied AI, data and product. I build alone, end to end, aiming to found startups. Below: everything I started, what is in progress, what works, and what I stopped and why, followed by the tools I use.

## Ce qui relie mes projets

- **Je pars d'un problème concret**, puis je construis le plus petit système qui le résout vraiment.
- **Je teste ce qui me fait peur en premier** (volonté de payer, accès aux données, barrières à l'entrée) avant de perfectionner.
- **Je documente aussi ce que j'arrête.** Un projet abandonné en connaissance de cause vaut mieux qu'un projet qui traîne.

## Mes projets

<table>
  <tr>
    <td width="84" align="center"><img src="assets/logos/kalk.svg" width="64" alt="Kalk"></td>
    <td>
      <h3>Kalk &nbsp;🟢 <sub>en cours</sub></h3>
      <b>Contexte :</b> analyser une opération immobilière se fait encore dans des tableurs faits main, difficiles à vérifier et à partager. Les outils professionnels sont complexes ou réservés aux grandes structures.<br>
      <b>Objectif :</b> donner aux investisseurs des outils d'analyse de niveau professionnel, plus simples à utiliser et plus précis.<br>
      <b>Où j'en suis :</b> en finalisation, lancement d'une liste d'attente en préparation. Je développe seul le front et le back, avec un associé expert immobilier qui pilote les modèles financiers. Code privé, vitrine publique à venir.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/daemon.svg" width="64" alt="Daemon"></td>
    <td>
      <h3><a href="https://github.com/Neemmmooooo/second-brain">Daemon</a> &nbsp;🟡 <sub>fonctionne, je ne travaille plus dessus</sub></h3>
      <b>Contexte :</b> ce que j'apprends (cours, projets, lectures) se disperse, et je retrouve mal ce que je sais déjà.<br>
      <b>Objectif :</b> un second cerveau qui range tout seul et me restitue l'information quand je pose une question.<br>
      <b>Ce que j'ai construit :</b> un architecte de connaissances qui classe les notes dans une taxonomie fixe, les étiquette, signale les contradictions avec ce que je sais déjà et compresse les notes anciennes. Il bascule de fournisseur de modèle en cas de panne (Groq → Cerebras). Les notes restent du markdown dans GitHub, lisible par Obsidian, Claude et l'application web.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/ai-workspace.svg" width="64" alt="AI Workspace"></td>
    <td>
      <h3><a href="https://github.com/Neemmmooooo/ai-workspace">AI Workspace</a> &nbsp;🟡 <sub>fonctionne, je ne travaille plus dessus</sub></h3>
      <b>Contexte :</b> chaque fournisseur de modèles a son interface, ses quotas et ses pannes. Changer d'outil en pleine tâche casse le fil.<br>
      <b>Objectif :</b> parler à n'importe quel modèle sans me soucier de quel fournisseur est disponible.<br>
      <b>Ce que j'ai construit :</b> un espace de chat en streaming avec 13 fournisseurs derrière une seule couche d'adaptation, une bascule automatique quand l'un tombe ou limite le débit, un routage du modèle selon la tâche et des clés chiffrées. Next.js et Postgres.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/meme-alpha.svg" width="64" alt="Meme Alpha"></td>
    <td>
      <h3>Meme Alpha &nbsp;⏸️ <sub>recherche en pause</sub></h3>
      <b>Contexte :</b> les analyses publiques de memecoins supposent des entrées irréalistes au prix du lancement, utilisent de l'information future et ignorent les coûts.<br>
      <b>Objectif :</b> savoir ce que l'on peut affirmer honnêtement sur la continuation des prix des memecoins Solana, avec des données et un modèle d'exécution rigoureux.<br>
      <b>Ce que j'ai construit :</b> une collecte de données on-chain, des indicateurs de momentum, un étiquetage sans biais d'anticipation et un simulateur d'exécution validé contre le SDK officiel. Les données collectées sont trop peu nombreuses pour conclure : le projet documente ses limites et ce qu'il faudrait pour aller plus loin. <i>Projet de recherche, pas un conseil financier.</i> Dépôt public à venir.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/reelhook.png" width="64" alt="ReelHook"></td>
    <td>
      <h3>ReelHook &nbsp;⚫ <sub>arrêté, post-mortem à venir en public</sub></h3>
      <b>Contexte :</b> les outils Instagram planifient ou génèrent du contenu, mais aucun ne dit quel contenu a rapporté de l'argent.<br>
      <b>Objectif :</b> relier chaque contenu à ses messages, ses appels, ses ventes et son chiffre d'affaires.<br>
      <b>Pourquoi arrêté :</b> manque de faisabilité. Les données nécessaires étaient peu fiables, les petits comptes avaient peu de capacité à payer et les grandes marques n'étaient pas intéressées. <b>Enseignement :</b> valider la volonté de payer et l'accès aux données avant de construire.
    </td>
  </tr>
  <tr>
    <td width="84" align="center"><img src="assets/logos/synaptic-ia.svg" width="64" alt="Synaptic IA"></td>
    <td>
      <h3>Synaptic IA &nbsp;⚫ <sub>arrêté, post-mortem à venir en public</sub></h3>
      <b>Contexte :</b> les marques jugent un contenu à l'intuition, en focus group ou par des études d'IRM à plusieurs dizaines de milliers d'euros.<br>
      <b>Objectif :</b> prédire comment le cerveau réagit à un contenu, selon le public (par exemple selon les générations), avant de dépenser en média.<br>
      <b>Pourquoi arrêté :</b> manque de ressources (capital, technologie, équipe spécialisée), et un acteur majeur a publié un modèle équivalent. <b>Enseignement :</b> évaluer tôt les barrières à l'entrée et le paysage concurrentiel.
    </td>
  </tr>
</table>

## Domaines

IA appliquée · Data · Développement full-stack · Produit

## Les outils que j'utilise

**IA et agents**
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claudecode&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?style=flat-square)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-333333?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Cerebras](https://img.shields.io/badge/Cerebras-1B8A6F?style=flat-square)

**Développement**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-333333?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black)

**Data et qualité**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)

**Déploiement et produit**
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Création et connaissances**
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexandre-pierre-8334aa259/)
[![Email](https://img.shields.io/badge/Email-1B8A6F?style=flat-square&logo=gmail&logoColor=white)](mailto:alexandre.gf.pierre@gmail.com)
