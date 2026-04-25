# Hey, I'm Kacper 👋

CS student from Wrocław, Poland. I build automation tools, mess around with AI APIs and generally try to make repetitive stuff disappear. Most of my real projects live at **PrimeAI** — a small AI agency I'm part of.

---

## What I'm working on

### [prime-recap](https://github.com/kjamrozinski/prime-recap)
A bot that reads Mattermost threads every evening, figures out which ones are about a Plane task, and posts an AI-generated summary as a comment directly on the issue. No more "what did we even decide today." Runs at 19:00 via cron, built in TypeScript, deployed in Docker.

`TypeScript` `Node.js` `Docker` `Claude API` `OpenRouter` `Mattermost` `Plane`

---

### Mattermost ↔ Plane automation *(private)*
Two workflows running on n8n:
- `/task` slash command that creates Plane issues from chat with flags for project, assignee, priority, milestone and dates
- Event listener that pushes real-time notifications back to Mattermost on every status/priority/assignee change in Plane

`n8n` `Plane API` `Mattermost Webhooks`

---

### Lead Hunter — `/leads` *(private)*
Slash command in Mattermost that runs a full prospecting pipeline on demand. Give it an industry + city, it queries Google Maps via Apify, enriches results through Apollo (emails, LinkedIn, CEO/CTO contacts) and spits out a ready CSV.

`n8n` `Apify` `Apollo API`

---

### [TimeFlow](https://github.com/kjamrozinski/TimeFlow) — engineering thesis
Full-stack PWA daily planner. Built it as my engineering thesis — offline-capable, with auth and a REST API.

`React` `Node.js` `Express` `SQLite` `PWA`

---

## Stack I actually use

TypeScript · Node.js · Docker · n8n · REST APIs · Git

Learning: more backend, better system design, less spaghetti code

---

## Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kjamrozinski&layout=compact&theme=default)

---

🇵🇱 Wrocław · Open to interesting side projects
