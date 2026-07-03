# Shivam Kansal

Backend and AI systems engineer building the layer between raw databases and people who don't want to write SQL to talk to them.

Currently interning at CRIS (Centre for Railway Information Systems), where I'm putting a RAG middleware layer in front of a live railway operations database — the kind of system where "just hardcode the query mappings" stops being an option after about the third schema. Outside of work: Top 800 of 32,000+ teams, solo, at Meta × Scaler × HuggingFace's OpenEnv hackathon, reviewed by Meta's engineering team at the 48-hour Bangalore finale.

**Currently working on:** schema variability handling for the RAG planning layer at CRIS — separating "the model decides what to ask" from "the model touches the database," which turns out to matter a lot more than it sounds.

**Graduating 2027, open to SDE / AI engineering internships now.** If you're building something involving LLMs, RAG, or backend systems that need to hold up under real load, I'd like to hear about it.

## Work that's shipped

**[AI Engineer Assessment Platform](https://ai-assessment-platform-one.vercel.app)** — *live*
A hiring platform that scores candidates on how they debug a broken RAG pipeline, not whether they can center a div. Multi-tenant, JWT-secured, four distinct simulated failure modes, full session replay via a telemetry engine with monotonic timestamps. Deployed on Vercel + Render with Docker multi-stage builds and GitHub Actions CI/CD. Built solo.
`React` `TypeScript` `FastAPI` `PostgreSQL` `Docker` `JWT`

**[Schema Migration Gym](https://github.com/kansalshivam/schema-migration-gym)** — *OpenEnv AI Hackathon, Top 800 / 32,000+*
A Gymnasium-compatible RL benchmark for SQL schema migration. Six task types, three difficulty tiers, and adversarial cases specifically designed to break greedy agents (zero-overlap renames, constraint repair traps). Each submission gets its own fresh Postgres container via the Docker SDK, diffed across five dimensions. The heuristic baseline scores a perfect 1.0 on standard tasks and drops to 0.48 on the adversarial set — showing exactly where rule-based logic stops working and reasoning has to take over.
`Python` `FastAPI` `PostgreSQL` `Docker` `OpenEnv` `Gymnasium`

**[Pollution Response Dashboard](https://github.com/kansalshivam/pollution-navigation-system)** — *Delhi Govt Hackathon, Top 6 Finalist*
A planning dashboard for municipal pollution-response deployment, built from idea to finalist pitch.
`React` `TypeScript`

**[FOSSEE Workshop Booking](https://github.com/kansalshivam/fossee-workshop-booking)** — *open-source, IIT Bombay*
Mobile-first UI/UX overhaul of the FOSSEE workshop booking platform, built to degrade gracefully across devices.
`React` `Django`

## Skills

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend** | FastAPI, Django, REST/OpenAPI 3.0, LangChain, RAG pipeline design |
| **AI/ML** | LLM API integration, prompt engineering, HuggingFace Transformers, OpenEnv, Gymnasium |
| **Data** | PostgreSQL, SQLite, schema design & migration |
| **Infra** | Docker, GitHub Actions, Vercel, Render |

Also shipped applied ML work — a dynamic pricing model — through IIT Guwahati's Summer Analytics 2025. Currently deep in DSA fundamentals (trees, graphs, DP) alongside the systems work above.

<br/>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kansalshivam&show_icons=true&theme=default&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kansalshivam&layout=compact&hide_border=true" height="165"/>
</p>

## Get in touch

[LinkedIn](https://linkedin.com/in/kansalshivam) · [Email](mailto:shivam427kansal@gmail.com) · [X](https://x.com/kansalshivam_)
