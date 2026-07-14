<p align="center">
  <img src="banner.png" alt="CivicSense — making local government legible" width="100%" />
</p>

<h1 align="center">Hi, I'm Emma 👋</h1>

<p align="center">
  <em>I build civic technology that helps people understand their own government.</em>
</p>

<p align="center">
  Founder & builder at <a href="https://askmytown.org">CivicSense</a> · Massachusetts 501(c)(3) civic-tech nonprofit
</p>

---

### 🏛️ What I'm working on

I run **CivicSense, Inc.**, a Massachusetts nonprofit on a simple mission: make local government legible to the people it serves. Town councils meet, vote, and decide things that shape daily life — but the record of it all is buried in scanned PDFs and archive pages almost nobody reads.

So I'm building tools that change that.

**🔎 [askmytown.org](https://askmytown.org)** — an AI agent you can ask plain-English questions about your local government. *"What did the Council decide about the library budget?"* → a grounded, cited answer that links straight back to the source record. Live in pilot for Amherst, MA, with the framework built to expand town by town.

Everything runs on public records, stays free for residents, and is built to be trustworthy: every answer traces back to an official document, and quality is measured, regression-gated, and auditable — not vibes.

Alongside that, I build **automations** that take the manual work out of running a small nonprofit — daily scrapers, self-updating data pipelines, CI-gated evals — and I care a lot about **AI governance**: shipping AI systems that are documented, accountable, and defensible to a non-technical auditor from day one (I build toward ISO/IEC 42001, not as an afterthought).

---

### 🛠️ How it's built

<p>
  <img src="https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="Postgres" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Braintrust-evals-6E56CF?style=flat" alt="Braintrust evals" />
  <img src="https://img.shields.io/badge/ISO%2FIEC_42001-AI_governance-0A7B3E?style=flat" alt="ISO/IEC 42001" />
</p>

A retrieval-augmented agent over Massachusetts town-government records — minutes, votes, agendas, and executive-session minutes — scraped daily from official feeds so the corpus is always current. Claude for generation, Postgres full-text retrieval, a Braintrust eval pipeline that gates every change, Cloudflare out front, and an ISO/IEC 42001 evidence program so every release is defensible to a non-technical auditor. Built and operated solo, from data pipeline to live user pilot.

---

### 📌 The corpus behind it

**[ecathq/ma-municipal-docs](https://github.com/ecathq/ma-municipal-docs)** — a daily-updated, open markdown archive of Massachusetts town-government meeting records, scraped from official town websites and kept in a format that's friendly to search and retrieval. It's the knowledge base askmytown.org runs on, and it's public record, mirrored for everyone. Amherst is wired up today; the layout is ready for more towns.

---

### 🤝 Get involved

CivicSense is small, mission-first, and always glad to meet people who care about open government.

- **Live near a MA town with online records?** I'm looking for towns to expand to — [open an issue](https://github.com/ecathq/ma-municipal-docs/issues) or reach out.
- **Developer or civic-data nerd?** Contributions to the corpus and scrapers are welcome.
- **Work at a mission-aligned nonprofit?** I build civic-tech tools with and for other orgs advancing government transparency.
- **Just want to try it?** Ask your town something at **[askmytown.org](https://askmytown.org)**.

---

### ✍️ Writing

I blog about civic tech, automations, and AI governance at **[emmaq.blog](https://www.emmaq.blog/)** — notes from building and governing AI systems in the open.

---

### 📫 Reach me

- 🌐 [askmytown.org](https://askmytown.org)
- ✍️ [emmaq.blog](https://www.emmaq.blog/)
- 💻 [github.com/ecathq](https://github.com/ecathq)

---

<div align="center">

![Emma's GitHub stats](https://github-readme-stats.vercel.app/api?username=ecathq&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default)

![GitHub streak](https://streak-stats.demolab.com/?user=ecathq&hide_border=true)

<sub>Independent civic project — not affiliated with any town government. All source documents are public records under Massachusetts public records law.</sub>

</div>
