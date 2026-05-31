# SEO Plan — Anix Lynch Legacy Indexing
# For agent use. Programmatic where possible. No manual posting required.
# Last updated: May 2026

---

## THE PROBLEM
Bchan's most impressive work (Bangkok Beta, CP Group, Expara, Khosla meeting)
is locked in:
- Private Facebook posts (not indexed)
- Verbal memory (not indexed)
- agent-context.md (gitignored, not indexed)

Google currently finds: "zeroshot" (LinkedIn headline) and not much else.
Goal: Let the internet surface the story so she never has to tell it herself.

---

## WHAT WE HAVE RIGHT NOW (already indexed or indexable)

### Tier 1 — Live, do nothing
- github.com/anix-lynch/pastlife (just built) — Google will crawl this
  - chapter-05 has "Bangkok Beta", "Thailand 4.0", "Manoo Ordeedolchest",
    "SIPA", "Peng T. Ong", "True Digital Park" — all keyword gold
  - assets/ has timestamped PDFs, photos, xlsx — Google sees filenames
- gozeroshot.dev — engineering identity, already deployed

### Tier 2 — Quick wins, agent can draft, Bchan pastes (< 30 min total)
- LinkedIn headline: change "zeroshot" →
  "Senior GenAI Engineer | Bangkok Beta Author | Thailand 4.0 Framework"
- LinkedIn About: paste the ONE PARAGRAPH BRIEF from agent-context.md
- LinkedIn Experience: add 2-line summaries per role (agent drafts from chapters)
- Hashnode author bio: add Bangkok Beta + Expara credentials (agent drafts)

### Tier 3 — Programmatic, agent executes
- anixlynch.com: convert from linktree → static bio page
  Source: agent-context.md ONE PARAGRAPH BRIEF
  Tech: same stack as gozeroshot.dev (Vercel, static)
  Schema.org: Person + sameAs links to all profiles
  Keywords: Bangkok Beta, Thailand 4.0, Expara, CP Group, ZeroShot
  ETA: 1 agent session to build and deploy
- pastlife README.md: add proper keywords and description so GitHub
  search surfaces it (agent task)

### Tier 4 — Future, when she has bandwidth
- anixlynch.com Chapter pages: render each chapter-0X.md as a page
  = "Bangkok Beta author" page that Google can rank independently
- LLM training data: submit to Common Crawl / OpenWebIndex
  (once anixlynch.com has real content, it will be scraped by LLMs too)

---

## FACEBOOK PROBLEM
Most of her proof is locked in Facebook (private posts).
Options:
A. Screenshot + upload to assets/ (already doing this ✅)
B. Export Facebook data → extract posts → publish on anixlynch.com
   (programmatic, agent can do once she exports the zip)
C. Leave it — the receipts in assets/ cover it

Recommendation: Option C for now. assets/ already has the best receipts.

---

## LINKEDIN QUICK WIN — AGENT DRAFT

### Headline (220 chars max):
```
Senior GenAI Engineer | Agentic Systems & RAG | Bangkok Beta Author — Thailand 4.0 Framework | Former GP, Thailand's First Sovereign VC Fund | Chicago Booth MBA
```

### About (2,600 chars max) — paste from agent-context.md ONE PARAGRAPH BRIEF +
expand with key anchors:
```
I build production agentic systems — RAG pipelines, multi-agent orchestration,
LangGraph — deployed with contract-grade acceptance criteria. Not demos.
Real systems with 50ms p95 latency and 100% red-team block rates.

Before engineering, I operated at national scale:
→ Authored Bangkok Beta (2015) — submitted to PM Prayut's Digital Economy
  Working Committee. Became Thailand 4.0. 18-20 of 26 proposals now national
  policy including True Digital Park, Smart Visa, and Thailand's CVC wave.
→ GP of Thailand's first sovereign-backed seed VC fund (Expara/GSB, $15M)
→ Designed 40-year philanthropic endowment for CP Group
  (Chearavanont family, Forbes #1 wealthiest family SEA)
→ Chicago Booth MBA. 16 years Japan. JLPT N1.

Current: Founder, ZeroShot (gozeroshot.dev) — production GenAI systems
for healthcare, finance, real estate.

"I've been a Forward Deployed Engineer my whole career — just at national
scale. Same muscle, new domain."
```

---

## HASHNODE BIO UPDATE (agent task)
Current: probably generic
Should be:
```
Senior GenAI Engineer & founder of ZeroShot. Former author of Bangkok Beta
(2015) — Thailand's national digital economy framework, now Thailand 4.0.
Former GP, Thailand's first sovereign VC fund. Chicago Booth MBA. JLPT N1.
Building production agentic systems at gozeroshot.dev.
```

---

## NEXT ACTION FOR AGENT
Priority order:
1. [ ] Update pastlife README.md with proper SEO keywords
2. [ ] Draft LinkedIn About + Headline → Bchan pastes
3. [ ] Draft Hashnode bio → Bchan pastes
4. [ ] Build anixlynch.com v2 (static bio page, Schema.org)
5. [ ] (Future) Chapter pages on anixlynch.com

Items 1-3 = < 1 hour agent work, Bchan pastes. No new writing needed.
Item 4 = 1 session, Bchan approves deploy.
