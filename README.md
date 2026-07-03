# Shivam Kansal

I build backend systems that reason over live data — most recently a RAG layer at Indian Railways that answers natural-language questions against a production database with no hardcoded query mappings. Solo finalist against 32,000+ teams at Meta's OpenEnv hackathon, work reviewed by Meta's engineering team at the 48-hour Bangalore finale.

**Right now:** building the model-intelligence layer for CRIS's RAG middleware, and hunting for an SDE / AI engineering role for late 2026.

## Work

**[AI Engineer Assessment Platform](https://ai-assessment-platform-one.vercel.app)** — live
Most technical hiring tests measure whether you can solve LeetCode puzzles, which has nothing to do with whether you can debug a broken RAG pipeline. This does the second thing: candidates inspect logs, revise prompts, and diagnose failures across 4 modeled failure modes, scored on reasoning quality rather than a pass/fail output check. Multi-tenant, JWT-secured, every action logged with monotonic timestamps for full session replay. Deployed with Docker multi-stage builds and GitHub Actions CI/CD on Vercel + Render.
`React` · `TypeScript` · `FastAPI` · `PostgreSQL` · `Docker`

**[Schema Migration Gym](https://github.com/kansalshivam/schema-migration-gym)** — Top 800 of 32,000+, Meta × Scaler × HuggingFace
A Gymnasium-compatible RL benchmark for SQL schema migration, with adversarial tasks built specifically to break greedy agents — zero-overlap renames, constraint-repair traps, structural ambiguity. Every submission gets its own fresh PostgreSQL container via the Docker SDK, isolated per-run, then diffed across 5 dimensions. Probably overkill for a hackathon deadline, but I wanted the scoring to be trustworthy, not just fast. Result: heuristic agents hit 1.0 on standard tasks and fall to 0.48 the moment the tasks get adversarial — that gap is the whole point of the benchmark.
`Python` · `FastAPI` · `PostgreSQL` · `Docker` · `Gymnasium`

**[Pollution Response Dashboard](https://github.com/kansalshivam/pollution-navigation-system)** — Top 6, Delhi Govt Hackathon
A planning dashboard for municipal pollution-response deployment, built and pitched under hackathon time pressure.
`React` · `TypeScript`

**[FOSSEE Workshop Booking](https://github.com/kansalshivam/fossee-workshop-booking)** — open-source, IIT Bombay
Mobile-first UI/UX rebuild of the FOSSEE workshop booking platform, with progressive enhancement so it holds up on low-end devices, not just on a designer's laptop.
`React` · `Django`

## Stack

Python, FastAPI, Django, LangChain and RAG pipeline design on the backend. React, TypeScript, and Vite on the frontend. PostgreSQL, Docker, and GitHub Actions for everything in between. I reach for FastAPI over Django by default now — async support out of the box matters more to me than Django's batteries-included feel, most of the time.

## Contact

[shivam427kansal@gmail.com](mailto:shivam427kansal@gmail.com) · [LinkedIn](https://www.linkedin.com/in/kansalshivam/) · [X](https://x.com/kansalshivam_)
