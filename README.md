# Abhay Bansal

**Backend engineer.** Go, TypeScript, PostgreSQL, Redis, Docker.
Currently building AI workflow infrastructure at Adaptware Solutions.

[Resume](RESUME_URL) · [LinkedIn](https://www.linkedin.com/in/abhay-bansal-44474a263) · [LeetCode](https://leetcode.com/u/abhaybansal_/) · [CodeChef](https://www.codechef.com/users/bansal03) · abhaybansalwork@gmail.com

---

### What I work on

I build backend services and developer tooling. Most of my time goes to service
boundaries, workflow execution, and making systems observable when they fail.

At Adaptware I built the integration layer between our product backend and an AI
service — Socket.IO transport with JWT auto-refresh, request correlation, and
concurrency throttling for up to 50 parallel executions per instance, with
LangGraph checkpoints in Redis for multi-turn conversational flows.

---

### Selected work

**[AE-Brand-User-Invitation](https://github.com/abhaybansal0322/AE-Brand-User-Invitation)** — Go · REST · OpenAPI · Docker · CI
Multi-persona user onboarding service. Persona-gated authorization, idempotent
duplicate-email handling, and a one-year queryable audit trail. Storage sits
behind a repository interface so the backing store swaps without touching handlers.

**[smart-expense-splitter](https://github.com/abhaybansal0322/smart-expense-splitter)** — Next.js · TypeScript · PostgreSQL · Drizzle · Docker
Group expense platform. Remainder-distribution split math so totals never drift
by a paisa, and a greedy min-cash-flow algorithm that collapses a debt graph into
the fewest settlement transactions. Thin API routes, Zod validation at the
boundary, services own behavior, repositories own persistence.

**[devsquad-mcp](https://github.com/abhaybansal0322/Devsquad)** — TypeScript · MCP · npm
MCP server that gates AI coding agents behind a workflow: classify prompt clarity,
route to implementation / discovery-first / investigation-only, enforce rule-based
review before expansion. Deliberately capability-free — no shell, no file writes,
no network, no `.env` reads.

**[github-remote-migrator](https://github.com/abhaybansal0322/github-remote-migrator)** — TypeScript · CLI
Rewrites local Git remotes after a GitHub owner rename. Dry-run by default,
timestamped backups, verified rollback, HTTPS/SSH/Enterprise URL forms.

---

### Open source

- [hoppscotch#6387](https://github.com/hoppscotch/hoppscotch/pull/6387) — merged (js-sandbox development docs), shipped in release 2026.6.0
- [files-community/Files#18539](https://github.com/files-community/Files/pull/18539) — merged

---

### Problem solving

LeetCode **2140** contest rating (top ~1%) · Global Rank 136 and 176 in Weekly Contests
CodeChef **4★** (1916) · Global Rank 25 in Starters 216 · 800+ problems solved

<a href="https://leetcode.com/u/abhaybansal_/">
  <img src="https://leetcard.jacoblin.cool/abhaybansal_?theme=dark&font=JetBrains%20Mono&ext=contest" alt="LeetCode stats" />
</a>

---

B.E. Computer Science and Engineering, Thapar Institute of Engineering and Technology — 2026 · CGPA 8.2/10