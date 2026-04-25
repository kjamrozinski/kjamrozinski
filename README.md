# Kacper Jamroziński                                                                                                                                                                                                     
   
  **Full-Stack Developer · AI Automation · Wrocław, Poland**                                                                                                                                                               
                       
  ![Profile views](https://komarev.com/ghpvc/?username=kjamrozinski&label=Profile%20views&color=0e75b6&style=flat)

  ---

  ## What I'm building

  At **PrimeAI** — an AI-focused agency — I design and ship internal automation tools that connect project management, team communication, and AI APIs into one coherent workflow.

  ### prime-recap
  Daily AI digest bot for development teams.
  Every evening it reads Mattermost channel threads, detects Plane task references (`PROJ-42` or issue URLs), sends them to Claude via OpenRouter, and posts structured AI summaries directly as comments on the relevant
  Plane issues. Threads without a task reference go to a digest channel.

  `TypeScript` `Node.js` `Docker` `OpenRouter` `Claude` `Mattermost API` `Plane API`

  ### Lead Hunter (`/leads`)
  Slash command in Mattermost that runs a full prospecting pipeline on demand.
  Takes an industry + city, queries Google Maps via Apify, enriches results through Apollo (emails, LinkedIn, CEO/CTO contacts), and delivers a ready-to-use CSV.

  `n8n` `Apify` `Apollo API` `Mattermost Webhooks`

  ### Mattermost ↔ Plane integration
  Two-way sync between chat and project management:
  - `/task` slash command to create Plane issues from Mattermost with flags for project, assignee, priority, milestone and dates
  - Real-time event notifications back to Mattermost on every status/priority/assignee change in Plane

  `n8n` `Plane API` `Mattermost API` `Webhooks`

  ---

  ## Other projects

  ### TimeFlow — Daily Planner *(engineering thesis)*
  Full-stack PWA built as an engineering project. Offline-capable daily planner with authentication and REST API.

  `React` `Node.js` `Express` `SQLite` `PWA`

  🔗 [github.com/kjamrozinski/TimeFlow](https://github.com/kjamrozinski/TimeFlow)

  ---

  ## Tech

  **Languages**
  TypeScript · JavaScript (ES6+) · HTML/CSS

  **Frontend**
  React · PWA

  **Backend**
  Node.js · Express · REST APIs

  **Automation & AI**
  n8n · OpenRouter · LLM tool calling · Webhooks

  **DevOps**
  Docker · docker-compose · Linux (Ubuntu) · Microsoft Azure (basics)

  **Tools**
  Zod · pino · node-cron · Vitest · Git

  ---

  ## GitHub Stats

  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kjamrozinski&layout=compact&show_icons=true&theme=default)

  ---

  ## Languages
  - Polish — native
  - English — B2
  - German — A2/B1
