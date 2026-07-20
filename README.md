# 🕌📖 Quran Scientific Miracles — Video Queue App

> A human-in-the-loop control panel for producing إعجاز علمي (scientific miracle) short-form videos from the Quran — fully automated pipeline, human-curated content. ✨🎬

🔗 **Live app:** [eajaz.stellarapp.cc](https://eajaz.stellarapp.cc)

---

## ⚠️ Personal Project — Not Open for Public Use

This is a **private, personal project** — not a public tool or open template. 🔐

- The live app is passcode-protected and used only by me and my content collaborator.
- The backend (n8n workflows, Langflow agents, API keys) is **not included** in this repo and isn't publicly reachable — any request sent to it without proper authentication will simply fail.
- This code is shared here purely as a **portfolio showcase** of what I can build.

**Want something like this for yourself?** 💼 I build custom n8n + Langflow automation pipelines (RAG bots, content pipelines, multi-agent systems, and more) for hire. Reach out and I can scope a custom build with pricing tailored to your use case.

---

## 🌟 What is this?

This is the front-end control room for an end-to-end **automated video pipeline** 🎞️ that transforms an ayah + its scientific explanation into a short, shareable video — while keeping a human firmly in the loop at every key step. 🙋

- ➕ **Add ayahs to the queue** — submit a Quranic reference along with its scientific theme, explanation, and source 🔬📚
- 👀 **Live ayah preview** — instantly fetches the authentic Quranic text & audio (Mishary Alafasy recitation 🎙️) before you submit
- 📋 **Manage the queue** — track every entry's status, from "pending" to "approved" to "published" ✅
- 🎬 **Review generated videos** — watch AI-generated videos right in the browser and approve or reject them ❌✅
- 🗂️ **Browse the video library** — every published video, previewable and downloadable in one place 📥

---

## 🧠 How It Works (Behind the Scenes)

| Stage | What Happens |
|---|---|
| 📝 Human curation | Ideas start in a human-reviewed Google Sheet — the ultimate source of truth |
| 📖 Ayah retrieval | Al Quran Cloud API pulls authentic ayah text & audio |
| 🎨 Scene planning | Gemini 2.5 Flash designs the visual scenes (science & nature only — **never** touching Quranic text or interpretation) |
| 🎥 Video generation | Seedance 1.0 Pro Fast renders the AI visuals |
| ✂️ Final assembly | Rendi.dev (cloud FFmpeg) stitches everything together |
| ✅ Human approval | **This web app** — no more Telegram back-and-forth, just approve/reject right in the browser |

> ⚠️ A hard rule baked into the whole pipeline: **AI never generates or interprets the Quranic text itself** — only the surrounding scientific/nature visuals. The ayah stays 100% authentic. 🕋

---

## 🎨 Design Highlights

- 🔐 Passcode-gated access — simple, private auth for the team
- 🇸🇦 Fully Arabic RTL interface
- 📊 Real-time queue stats and status badges
- 🎞️ Native in-browser video review — no downloads needed to approve/reject
- 📱 Clean, responsive layout for reviewing on the go

---

## 📦 What's Included Here

Just the **frontend web app** (`index.html`). The backend automation (n8n workflows, Langflow scene-planning agent, and other `.json` pipeline configs) stays private on my own infrastructure. 🔐

---

## 🛠️ Tech Stack

- ⚡ Vanilla JS frontend (deployed via **Cloudflare Pages**)
- 🤖 n8n for workflow automation & orchestration
- 🧩 Langflow for AI scene-planning agent
- 📖 Al Quran Cloud API for authentic ayah text & audio
- 🎥 Seedance 1.0 Pro Fast for AI video generation
- 🎬 Rendi.dev (cloud FFmpeg) for final video assembly
- 📊 Google Sheets as the human-curated source of truth

---

## 🗺️ Roadmap

- [ ] 🔢 Dynamic clip-count logic based on content length
- [ ] 📝 Auto-update Google Sheet on rejection
- [ ] 💾 Persistent volume mount for n8n temp files

---

## 🤝 Feedback

This is a solo-built project 👨‍💻 — feedback and ideas are always welcome, but the repo itself isn't open for external contributions since core pipeline logic lives outside it.

---

## 📜 License

Personal project — all rights reserved unless otherwise noted.

---

<p align="center">Built with 🤲 niyyah, ☕ coffee, and a lot of late-night debugging.</p>
