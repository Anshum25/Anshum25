<a href="https://theanshumdev.site">
  <img src="assets/banner.svg" width="100%" alt="Anshum Dev, AI Engineer and Software Engineer, Ahmedabad, India">
</a>

<p align="center">
  I build AI products and the dependable software around them:<br>
  RAG assistants, FastAPI backends, offline-first apps and ERPNext automation.<br>
  <sub>Currently <b>AI Intern @ NivaSync Infotech</b> &nbsp;·&nbsp; B.Tech CS&amp;T, L.J. Institute, class of 2027 &nbsp;·&nbsp; <b>open to internships and full-time roles</b></sub>
</p>

<p align="center">
  <a href="https://theanshumdev.site"><img alt="Portfolio: theanshumdev.site" src="https://img.shields.io/badge/Portfolio-theanshumdev.site-1c1b19?style=flat-square&labelColor=0c0c0b&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmY0ZDFjIiBzdHJva2Utd2lkdGg9IjIiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjkuNSIvPjxwYXRoIGQ9Ik0yLjUgMTJoMTlNMTIgMi41YzIuNiAyLjcgMy45IDUuOSAzLjkgOS41cy0xLjMgNi44LTMuOSA5LjVjLTIuNi0yLjctMy45LTUuOS0zLjktOS41czEuMy02LjggMy45LTkuNXoiLz48L3N2Zz4%3D"></a>
  <a href="https://www.linkedin.com/in/anshum25/"><img alt="LinkedIn: anshum25" src="https://img.shields.io/badge/LinkedIn-anshum25-1c1b19?style=flat-square&labelColor=0c0c0b&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmNGQxYyIgZD0iTTQgMi42YTIuMSAyLjEgMCAxIDEgMCA0LjIgMi4xIDIuMSAwIDAgMSAwLTQuMnpNMi4yIDguOGgzLjZWMjFIMi4yek04LjkgOC44aDMuNHYxLjdjLjUtLjkgMS43LTIgMy42LTIgMy44IDAgNC41IDIuNSA0LjUgNS43VjIxaC0zLjZ2LTUuOWMwLTEuNCAwLTMuMi0yLTMuMnMtMi4zIDEuNS0yLjMgMy4xdjZIOC45eiIvPjwvc3ZnPg%3D%3D"></a>
  <a href="https://x.com/TheAnshumDev"><img alt="X: @TheAnshumDev" src="https://img.shields.io/badge/X-@TheAnshumDev-1c1b19?style=flat-square&labelColor=0c0c0b&logo=x&logoColor=ff4d1c"></a>
  <a href="mailto:anshum25506@gmail.com"><img alt="Email: anshum25506@gmail.com" src="https://img.shields.io/badge/Email-anshum25506@gmail.com-1c1b19?style=flat-square&labelColor=0c0c0b&logo=gmail&logoColor=ff4d1c"></a>
</p>

<img src="assets/divider.svg" width="100%" alt="">

### `01` &nbsp;Featured: Swachh Safar 2.0

<p>
  <a href="https://ehk.itfarmer.in"><img src="assets/swachh-showcase.png" width="100%" alt="Swachh Safar 2.0: offline-first railway cleanliness operations, shown on three phone screens"></a>
</p>

An offline-first cleanliness-operations platform for Indian Railways divisions. Staff work inside moving coaches, in tunnels and in yards with no network, so every write is local-first.

- **One React codebase, two targets.** It ships as an installable PWA and a signed Android APK (Capacitor 8). SQLite WASM on OPFS is the source of truth on the phone until the FastAPI + PostgreSQL server acknowledges each record, and fixes reach phones over the air.
- **Attendance on the device.** A live-camera face match and USB-OTG fingerprint capture through a Kotlin Capacitor plugin. It stores templates only, never face or fingerprint images.
- **Tested before it ships.** Every push to main runs 300 device tests on real SQLite and 193 backend tests on a throwaway PostgreSQL in GitHub Actions before a release goes out. 11 offline end-to-end Playwright specs cover the browser flows.

<sub>Team project; I am the primary contributor.</sub>

**[Live app](https://ehk.itfarmer.in)** &nbsp;·&nbsp; **[Download the APK](https://ehk.itfarmer.in/download)** <sub>(Android 8.0+)</sub> &nbsp;·&nbsp; **[Repository](https://github.com/Anshum25/swachhsafar)**

### `02` &nbsp;Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/ai_erpnext">ai_erpnext</a></b><br>
      An AI assistant inside ERPNext v16 Desk. It looks up records with the user's own permissions and builds Draft documents from a chat or from invoice and order images. It never submits, cancels or pays.<br>
      <sub>Python · Frappe v16 · OpenAI / Gemini / Groq · pypdfium2 · CI</sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/ChessMentor">ChessMentor</a></b><br>
      A chess coach. Stockfish evaluates every move, an LLM explains it, and a learning engine turns your weaknesses into missions.<br>
      <sub>FastAPI · PostgreSQL · python-chess · LiteLLM · Next.js 15 · TypeScript</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/cbt-system">cbt-system</a></b><br>
      Grades handwritten Hindi exam answers. Gemini OCR reads the sheets, an LLM scores them against rubrics on a Celery queue, and teachers review, calibrate and override.<br>
      <sub>FastAPI · Celery · Redis · PostgreSQL · Gemini · React · TypeScript</sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/agrismart-ai">agrismart-ai</a></b> &nbsp;<sub><a href="https://agrismart-ai-wheat.vercel.app">live</a></sub><br>
      An offline crop doctor, built as a team for Smart India Hackathon 2026. It diagnoses 38 diseases across 14 crops on the phone with ONNX, shows a Grad-CAM heatmap and gives advice in 9 languages.<br>
      <sub>React · PWA · onnxruntime-web · FastAPI · Groq · Leaflet</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/churn-platform">churn-platform</a></b> &nbsp;<sub><a href="https://churn-dashboard-three.vercel.app">live</a></sub><br>
      Upload a customer CSV and get churn scores with per-customer SHAP reasons, recommended actions and a Gemini agent that answers questions about at-risk revenue.<br>
      <sub>scikit-learn · XGBoost · SHAP · FastAPI · Gemini · React · Recharts</sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/Anshum25/business_health_checkup">business_&#8203;health_&#8203;checkup</a></b><br>
      A manufacturing health-check spreadsheet turned into a Frappe app: 150-question assessments over 10 departments, scoring, gap analysis, a 90-day plan and management reports.<br>
      <sub>Python · Frappe v16 · MariaDB · Jinja print formats</sub>
    </td>
  </tr>
</table>

### `03` &nbsp;Stack

<img height="36" src="https://skillicons.dev/icons?i=py,tensorflow,sklearn" alt="Python, TensorFlow, scikit-learn"><br>
<sub><b>AI &amp; ML</b> &nbsp;·&nbsp; LLMs · RAG · embeddings · semantic search · Qdrant · LangChain · Ollama · XGBoost · SHAP · OCR · Gemini, OpenAI and Groq APIs</sub>

<img height="36" src="https://skillicons.dev/icons?i=fastapi,nodejs,postgres,mysql,mongodb,sqlite,redis" alt="FastAPI, Node.js, PostgreSQL, MySQL, MongoDB, SQLite, Redis"><br>
<sub><b>Backend</b> &nbsp;·&nbsp; REST APIs · JWT / RBAC · SQLAlchemy · Alembic · Celery · ERPNext and Frappe (workflows, reports, server and client scripts)</sub>

<img height="36" src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,vite,kotlin" alt="TypeScript, JavaScript, React, Next.js, Tailwind CSS, Vite, Kotlin"><br>
<sub><b>Frontend &amp; mobile</b> &nbsp;·&nbsp; PWA · Capacitor · SQLite WASM on OPFS · Vitest · Playwright</sub>

<img height="36" src="https://skillicons.dev/icons?i=docker,linux,nginx,aws,vercel,githubactions,git,postman" alt="Docker, Linux, nginx, AWS, Vercel, GitHub Actions, Git, Postman"><br>
<sub><b>Infra</b> &nbsp;·&nbsp; Docker · Linux · nginx · AWS · Vercel · GitHub Actions · Git · Postman</sub>

### `04` &nbsp;Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Anshum25/Anshum25/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Anshum25/Anshum25/output/github-snake.svg">
  <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/Anshum25/Anshum25/output/github-snake.svg" width="100%">
</picture>

<img src="assets/divider.svg" width="100%" alt="">

<p align="center"><i>There is so much left to build.</i></p>

<p align="center"><sub><a href="https://theanshumdev.site">theanshumdev.site</a> &nbsp;·&nbsp; Ahmedabad, India</sub></p>
