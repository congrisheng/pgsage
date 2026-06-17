# pgsage
AI-powered Postgres performance doctor
# pgsage 🐘 🩺 

  > AI-powered Postgres performance doctor for indie hackers and small teams.

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Status](https://img.shields.io/badge/Status-Building_in_public-blue.svg)](https://github.com/pgsage/pgsage)
  [![Go](https://img.shields.io/badge/Go-1.22+-00ADD8.svg)](https://go.dev/)

  ## What pgsage is (and isn't)

  ✅ **pgsage is**: An open-source CLI + Cloud service that gives you a
     diagnostic report for your Postgres database. You read it, you decide.

  ❌ **pgsage isn't**: An autonomous agent that runs DDL on your production DB.
     We trust the human in the loop.

  ## Why pgsage?

  Tools like pganalyze are great — but they cost $200+/month.
  Most indie hackers and small teams just need:

  - 🔍 Find the slowest queries
  - 🤖  Understand WHY they're slow (in plain English)
  - 💡  Get actionable index / rewrite suggestions
  - 📊  Generate a clean report you can share

  That's exactly what pgsage does. **Free CLI. Cloud version coming.**

  ## Quickstart (coming soon)

  ```bash
  go install github.com/pgsage/pgsage@latest
  pgsage analyze --conn $DATABASE_URL

  Roadmap

  - [x] Project kickoff (W0)
  - [ ] CLI scaffold (W1)
  - [ ] pg_stat_statements collector (W2)
  - [ ] SQL parser & query classifier (W3)
  - [ ] LLM-powered diagnosis (W4)
  - [ ] Index advisor (W5)
  - [ ] Markdown / HTML reports (W6)
  - [ ] Landing page (W7)
  - [ ] Public launch (W8)
  - [ ] Cloud version (Q4 2026)

  Building in public

  This project is being built in public. Follow along:
  - 🌐  https://pgsage.dev (coming soon)
  - 🐦 hX: @pgsageHQ (https://x.com/pgsageHQ)

  License

  MIT © 2026 pgsage

  提交 commit message：`docs: project vision and roadmap`

  ---
