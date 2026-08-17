<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/end1989/end1989/main/assets/banner-dark.png">
  <img alt="Eldon Dahlin" src="https://raw.githubusercontent.com/end1989/end1989/main/assets/banner-light.png" width="100%">
</picture>

### I build AI tools people can trust.

<sub>Full-stack engineer &nbsp;·&nbsp; RAG pipelines &nbsp;·&nbsp; MCP servers &nbsp;·&nbsp; local-first apps &nbsp;·&nbsp; AI safety tooling</sub>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/eldon-dahlin)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eldondahlin@gmail.com)
[![Résumé (PDF)](https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-475569?style=for-the-badge&logo=readdotcv&logoColor=white)](https://github.com/end1989/end1989/blob/main/assets/Eldon_Dahlin_Resume.pdf)
<br>
[![Location](https://img.shields.io/badge/Denver,_CO-Will_Relocate_for_Anthropic-14B8A6?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Open_to_Work-brightgreen?style=for-the-badge&logo=openstatus&logoColor=white)](#)

</div>

---

Full-stack engineer in Denver, seven-plus years in. I cut my teeth on Java and Spring Boot at Dish and Travelport, building the validation and data-integrity systems that kept millions of hotel records trustworthy — mostly by catching bad signal before it reached anyone downstream. Then I fell hard for AI and never looked back.

These days I build RAG pipelines, MCP servers, and local-first tools — the kind that run on your own machine and show their work. And I build safeguards, because I've watched AI get turned against someone I care about, and it turns out "I love AI" and "I want AI to be safe" are the same sentence. If there's a new model or framework out, I've probably already spun it up to see what it can do — and how it breaks.

---

### Featured: VerifyMyAI

<table>
<tr>
<td width="50%" valign="top">

**[VerifyMyAI](https://github.com/end1989/verifymyai)** &nbsp;·&nbsp; **[verifymyai.org](https://verifymyai.org)**

Someone with two minutes of access to your account can quietly reprogram your AI assistant to work against you. VerifyMyAI is a free, open-source tool that helps people find out whether that has happened to them — a tiered audit (Quick Check → Full Audit → Deep Dig) that surfaces hidden instructions and manipulation patterns in ChatGPT, Claude, Gemini, Copilot and others, then helps build an evidence package. I built it after a bad actor did exactly this to a friend.

Built for people who may be in danger: an emergency exit that swaps the tab for a boring cooking search, a deliberately bland tab title, crisis resources always one tap away — and nothing leaves the browser. No accounts, no analytics, no server; it keeps working offline once loaded.

`React 19` · `Vite` · `Tailwind` · `PWA` · `no backend` · `trauma-informed UX`

</td>
<td width="50%" valign="middle">

[![VerifyMyAI’s Choose Platform step — “Which AI tool do you use?” with cards for ChatGPT, Claude, Gemini, Copilot and Grok, the always-visible help bar, and the emergency exit](https://raw.githubusercontent.com/end1989/end1989/main/assets/verifymyai.png)](https://verifymyai.org)

</td>
</tr>
</table>

### More things I've built

<table>
<tr>
<td width="50%" valign="top">

[![Tailored’s Templates page — two of its eight print-tuned résumé templates, Meridian and Slate, rendered side by side on sample data](https://raw.githubusercontent.com/end1989/end1989/main/assets/cards/tailored.webp)](https://github.com/end1989/tailored)

**[Tailored](https://github.com/end1989/tailored)**

Local AI résumé and cover-letter builder with a truthfulness guard enforced in the data layer, not the prompt: a generated résumé that names an employer, title, date, degree or certification that isn't in your profile is rejected on the write path — whichever model wrote it. Run it on the Anthropic API, or bring your own agent through its 14-tool MCP server. Eight print-tuned templates → PDF (real headless Chromium), HTML and ATS text. ~600 automated tests.

`Python` · `FastAPI` · `React` · `Anthropic API` · `MCP` · `Playwright`

</td>
<td width="50%" valign="top">

[![Diagram: documents flow into BM25 and dense retrieval, get merged and re-ranked, and come out as an answer with [1] [2] citations](https://raw.githubusercontent.com/end1989/end1989/main/assets/cards/docsai.webp)](https://github.com/end1989/docsai)

**[DocsAI](https://github.com/end1989/docsai)**

Local-first hybrid RAG engine. Point it at a docs site, a folder of PDFs, or an OpenAPI spec; it crawls, chunks by document type, and answers with citations — BM25 and dense embeddings merged, prompt mode auto-detected (comprehensive / integration / debugging / learning). React dashboard, pip-installable CLI, and an MCP server so Claude can query it directly.

`Python` · `FastAPI` · `ChromaDB` · `BM25` · `React 19` · `MCP server`

</td>
</tr>
<tr>
<td width="50%" valign="top">

[![Diagram: a manager dispatches to three isolated workers; their results pass a review gate into an audit log](https://raw.githubusercontent.com/end1989/end1989/main/assets/cards/orchestration.webp)](https://github.com/end1989/ai-manager)

**[Task Orchestration Engine](https://github.com/end1989/ai-manager)**

Single-host manager–worker system for AI-executed tasks: process isolation, resource limits, automated review-and-approval gates, secret detection, and a full audit trail of everything that ran.

`FastAPI` · `SQLModel` · `Docker` · `process isolation`

</td>
<td width="50%" valign="top">

[![A lightning bolt over city lights — an actual frame Lightning Finder extracted from a storm video](https://raw.githubusercontent.com/end1989/end1989/main/assets/cards/lightning.webp)](https://github.com/end1989/lightning-finder)

**[Lightning Finder](https://github.com/end1989/lightning-finder)**

Point it at a long storm recording and it finds every flash — even single-frame ones — by watching for brightness spikes above a rolling baseline, so dusk and auto-exposure drift don't fool it. Then it tells the bolt from the glow: temporal differencing cancels the static scene and scores each flash for an actual lightning channel. Scrub to the exact frame in the browser and grab it losslessly at native resolution.

`Python` · `FastAPI` · `OpenCV` · `PyAV` · `NumPy` · `vanilla JS`

<sub>The trace in the banner is this detector's idea in miniature: watch the rise over the baseline, not the level.</sub>

</td>
</tr>
</table>

Also: **[Panes](https://github.com/end1989/panes)** — a multi-stream viewer for YouTube, Twitch, Vimeo and Kick in one dependency-free HTML file, up to a 6×6 wall. [Try it live.](https://end1989.github.io/panes/)

**One that's private:** an offline media-classification and content-moderation pipeline — CLIP zero-shot labels, PaddleOCR text extraction, an NSFW / sensitive-content detector, duplicate and face detection — with a review UI whose corrections train a per-install model, so it gets better the more you disagree with it. Every move it makes is logged and undoable. `PyTorch` · `CLIP` · `PaddleOCR` · `FastAPI` · `Electron`

---

### Toolbox

<table>
  <tr><td width="150"><b>Languages</b></td><td><code>Python</code> &nbsp; <code>TypeScript</code> &nbsp; <code>Java</code></td></tr>
  <tr><td><b>Backend</b></td><td><code>FastAPI</code> &nbsp; <code>Spring Boot</code></td></tr>
  <tr><td><b>Frontend</b></td><td><code>React</code> &nbsp; <code>Vite</code> &nbsp; <code>Tailwind CSS</code></td></tr>
  <tr><td><b>Data &amp; infra</b></td><td><code>PostgreSQL</code> &nbsp; <code>MongoDB</code> &nbsp; <code>ChromaDB</code> &nbsp; <code>Apache Kafka</code> &nbsp; <code>Docker</code></td></tr>
  <tr><td><b>AI</b></td><td><code>Claude / Anthropic API</code> &nbsp; <code>MCP servers</code> &nbsp; <code>RAG pipelines</code> &nbsp; <code>Ollama</code> &nbsp; <code>PyTorch</code> &nbsp; <code>Hugging Face</code> &nbsp; <code>CLIP</code></td></tr>
</table>

### How I build

- **Spec → plan → tests → code.** Tailored shipped with ~600 automated tests, PDF rendering through real headless Chromium included — and its truthfulness guard is a structural check on the write path, not a polite request in a prompt.
- **Local-first by default.** DocsAI, Lightning Finder and Tailored run on your machine; VerifyMyAI never sends anything anywhere. Privacy is a design constraint, not a settings toggle.
- **Adversarial by habit.** I spin up new models and frameworks to see what they can do and where they break. Data integrity, prompt injection, content moderation, even lightning — detection is one skill: find the thing that doesn't belong.
- **The unglamorous safety parts ship.** Audit trails and secret detection in the orchestration engine; an emergency exit, history scrub, and always-on crisis resources in VerifyMyAI.

---

### Off the clock

Galvanize bootcamp grad (2018), writing production code ever since. Lived in Peru for two years and speak Spanish. I do my best thinking with a hard problem and a local model humming — often later than I should.

<div align="center">

*Currently exploring new opportunities — especially AI engineering and trust & safety roles where the job is keeping these systems useful and safe for the people who rely on them.*

*If you're working on something that matters, let's talk.* 🤙

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/eldon-dahlin)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:eldondahlin@gmail.com)
[![Résumé (PDF)](https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-475569?style=flat-square&logo=readdotcv&logoColor=white)](https://github.com/end1989/end1989/blob/main/assets/Eldon_Dahlin_Resume.pdf)

</div>
