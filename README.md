# Hi, I'm Asheesh 👋

**Vibe coder automating business processes. Not tied to one language, I pick whatever gets the job done.**

I find the manual, repetitive parts of how a business runs (spreadsheets, hand-built reports, copy-paste between tools) and replace them with automations and apps people use every day.
I use AI as my pair programmer to explore technologies, build applications, automate workflows, and solve practical business problems.
What I care about most is understanding the process, defining clear rules, maintaining audit trails, and building solutions that produce reliable results teams can trust.

📍 India &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/trippyash) &nbsp;·&nbsp; ✉️ [asheesh25asm@gmail.com](mailto:asheesh25asm@gmail.com)

---

## What I work on

- **Internal dashboards** - role-based web apps (FastAPI + vanilla JS) for performance
  scorecards, staff rosters, meeting tracking and review monitoring, used daily by
  operations teams.
- **Data pipelines** - nightly jobs that pull from CRMs, APIs and scrapers into Postgres,
  then derive the reporting tables the dashboards read.
- **Automation & alerts** - Slack bots and digests, Google Sheets sync, webhook
  workflows (n8n), and scheduled jobs on GitHub Actions.
- **Business rules as data** - KPI weights, month-end locks, approval flows and audit
  logs designed so a rule can change without a code change.

## Tools I've built with

**Languages (so far):** Python · SQL · JavaScript · PowerShell
**Back end:** FastAPI · Streamlit · REST APIs · Playwright (scraping)
**Data:** PostgreSQL · Supabase (RLS) · SQLite · Google Sheets API
**Automation:** GitHub Actions · n8n · Slack API · cron / systemd
**Infra:** Linux (EC2) · nginx · Git
**AI:** OpenAI / Claude APIs with structured (JSON-schema) outputs

## Featured projects

| Project | What it shows |
|---|---|
| [content-review-tool](https://github.com/TrippyAsh/content-review-tool) | AI screens marketing content against a rulebook; regional reviewers approve or reject. Postgres RLS enforces every access rule, n8n runs the AI step, and code (not the AI) decides the status. |
| [review-monitor](https://github.com/TrippyAsh/review-monitor) · [live report](https://trippyash.github.io/review-monitor/) | Turns "someone checks app reviews once a week" into a daily process: new App Store reviews are flagged by rules kept in config, sent to Slack with the reason, and published as a report. Runs on GitHub Actions + Pages, no server. |
| _more coming soon_ | Team scorecard · shift roster app |

## How I like to build

- Deterministic code decides anything that moves money or status; AI only does the
  language work.
- Every important change leaves an audit trail.
- Test against real-looking data before it ships, and write down what was decided and why.

---

<sub>Most of my day-to-day work lives in private company repositories, so this profile
shows personal projects built from scratch with sample data.</sub>
