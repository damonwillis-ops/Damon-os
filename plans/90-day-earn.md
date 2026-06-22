# 90-Day Earn Plan
**Created:** 2026-06-22
**Strategy:** Consulting → SAIP flywheel. Walmart funds runway. Consulting opens revenue in 60-90 days. SAIP converts consulting clients to SaaS ARR. Groundtruth builds the audience that feeds both.

**North star:** First consulting dollar by Day 60. First SAIP pilot conversation by Day 90. Bluwood on paid subscription by Day 7.

---

## THE MACHINE

```
Groundtruth (public credibility + audience)
    ↓
Consulting opens (warm network, no cold outreach)
    ↓  $10-25K per engagement, 3 weeks, Walmart still paying
Consulting clients describe what they need
    ↓
SAIP features built against real requirements
    ↓
Consulting client → SAIP pilot customer
    ↓
Consulting ARR + SaaS ARR + Groundtruth sponsorship = real options on Walmart
```

---

## PHASE 1 — Launch Consulting (Days 1-30)

### Week 1: Plant flags
- [ ] **CALL BLUWOOD OWNER TODAY** — "I'm turning this into a product. Founder rate $49/mo. You stay on it, I use you as reference customer." 5 minutes. First recurring SaaS revenue.
- [ ] Post Groundtruth issue 2 (ready now — send it)
- [ ] LinkedIn post 1: "Here's what we built at Walmart — APERTURE, an AI design assurance system for CCTV deployments before the truck rolls." Show the work. No pitch. Tag 2-3 relevant people.
- [ ] DM 20 physical security peers directly. Personal, not blast. "I'm opening 2 advisory slots for Q3 — enterprise security programs navigating PSIM modernization or AI-CV deployment. Know anyone who'd benefit?" Former Walmart colleagues now at Director/VP roles elsewhere are the priority list.
- [ ] Add to email signature: "I advise enterprise physical security programs on AI-CV and PSIM modernization. 2 slots open Q3."

### Week 2: Qualify leads
- [ ] Follow up on any DM responses — schedule 30-min discovery calls
- [ ] Discovery call goal: understand their problem, not sell. "What's your biggest PSIM/CCTV headache right now?"
- [ ] LinkedIn post 2: "I'm taking 2 advisory engagements for enterprise physical security programs in Q3. DM me if your team is navigating PSIM modernization, AI-CV deployment, or SiteOwl limitations at scale."
- [ ] Post in ASIS LinkedIn groups (practitioner, not promotional tone)

### Week 3-4: Close first engagement
- [ ] Scope engagement using template below
- [ ] Send SOW (Statement of Work)
- [ ] Collect 50% deposit before work starts

**Engagement template: Physical Security AI Readiness Assessment**
- Scope: 3 weeks, part-time (10-15 hrs/week)
- Deliverables: Current stack audit, AI-CV readiness score by location tier, vendor recommendation matrix, modernization roadmap, 1 executive presentation
- Price: $10,000 fixed (first client discount from $15K rack rate)
- Format: Remote. Weekly check-in calls + async Slack/email.

---

## PHASE 2 — Execute + Build (Days 30-60)

### Consulting execution
- [ ] Week 1 of engagement: stack audit (interviews + documentation review)
- [ ] Week 2: gap analysis, scoring, vendor map
- [ ] Week 3: roadmap + executive deck
- [ ] Debrief: plant seed — "There's a platform I'm building that automates what we just did manually..."

### SAIP Sprint 1+2 (parallel, ~10 hrs/week)
- [ ] Confirm with CISSP partner: PostGIS + pgvector on Supabase dev instance? (BLOCKING)
- [ ] Once confirmed: run Sprint 1 scaffold (FastAPI skeleton, SQLAlchemy models, Alembic init, JWT auth endpoints)
- [ ] Sprint 2: RBAC, org scoping, pytest suite green
- [ ] Goal: `/docs` accessible, uvicorn starts, all auth tests pass

### Groundtruth automation (Phase 1 tasks)
- [ ] Task 1: Add CISA + FBI RSS to scraper
- [ ] Task 2: Buffer API replaces email send (LinkedIn auto-queue)
- [ ] Task 3: Reddit post generator + Telegram approval

### Subscriber push
- [ ] Post weekly without fail (issue 3, 4)
- [ ] Reddit posts on publish day (r/physicalsecurity, r/corporatesecurity)
- [ ] Target: 100 subscribers by Day 60

---

## PHASE 3 — Convert + Scale (Days 60-90)

### Convert consulting to SAIP
- [ ] Post-engagement debrief with client: "Here's what SAIP automates permanently"
- [ ] If interest: offer 6-month pilot at reduced rate ($500-1,000/mo) in exchange for feedback and reference
- [ ] This becomes Session 2 of SAIP — build what they actually need

### Second consulting engagement
- [ ] Pipeline should have 2-3 qualified leads from Phase 1 outreach
- [ ] Close second engagement: $12,500-15,000 (rack rate)
- [ ] Apply learnings from first engagement to scope faster

### ShopFlow — convert + expand
- [ ] Bluwood confirmed on paid plan → add Stripe billing to supa-suite
- [ ] Identify 2-3 other NW Arkansas custom manufacturers (cabinet shops, metal fab, millwork) — warm intro through Bluwood owner or local chamber
- [ ] Pitch same founder rate: $49/mo, "product that Bluwood runs their business on"
- [ ] Hold universal multi-tenant build until SAIP Sprint 1 done — don't split build focus

### Groundtruth milestone check
- [ ] At 100+ subscribers: reach out to first potential sponsor (Genetec, ZeroEyes, or Verkada — start with smallest/most responsive)
- [ ] Video pipeline: if Buffer + Reddit running smoothly, build Phase 2 video automation

---

## FINANCIAL TARGETS

| Milestone | Timeline | Revenue |
|-----------|----------|---------|
| Bluwood paid subscription | Day 7 | $49/mo recurring |
| First consulting deposit (50%) | Day 30-45 | $5,000 |
| First engagement complete | Day 60 | $5,000 (balance) |
| Second engagement signed | Day 75 | $6,250 (50% deposit) |
| ShopFlow customer 2-3 (local outreach) | Day 60-90 | $99-198/mo recurring |
| SAIP pilot conversation | Day 90 | $0 yet, but pipeline |
| Groundtruth first sponsor | Month 6 | $1,000-2,500 |
| **90-day total** | | **~$16,500 + $300-400/mo MRR** |

---

## CONSULTING POSITIONING

**Title to use:** Independent Advisor — Enterprise Physical Security Modernization

**One-line pitch:** "I help enterprise physical security programs modernize PSIM, deploy AI-CV, and eliminate SiteOwl limitations — built on what I designed at Walmart's 4,600-location scale."

**Credibility anchors (use these, in this order):**
1. Managed SiteOwl at 4,600 Walmart locations
2. Built APERTURE — AI design assurance that gates CCTV installs before truck rolls
3. Built SOAR — automated SiteOwl bulk-import generation
4. CPP certified
5. Currently building SAIP to productize this for mid-enterprise market

**Never lead with:** freelancer, consultant-for-hire, side business. Lead with advisor, practitioner, and specific outcomes.

---

## WEEKLY REVIEW CHECKLIST

Every Monday, check:
- [ ] Consulting: any open proposals? Any stalled conversations?
- [ ] Groundtruth: issue sent? Subscriber count? Any sponsor interest?
- [ ] SAIP: any sprint progress? CISSP partner status?
- [ ] LinkedIn: any inbound from posts?

---

## DECISION LOG

**2026-06-22 — Consulting-first strategy adopted**
- Rationale: fastest path to income (60-90 days vs 12-18 months for Groundtruth/SAIP alone)
- Groundtruth and SAIP continue in parallel — consulting validates both
- Walmart income = zero-risk runway during build
- First target: 2 consulting engagements in Q3 2026

---

## STATUS TRACKING

Update this section each session.

| Item | Status | Last Updated | Next Action |
|------|--------|-------------|-------------|
| **Bluwood paid conversion** | **NOT DONE** | 2026-06-22 | **Call owner TODAY** |
| Groundtruth issue 2 | Ready to send | 2026-06-22 | Send today |
| Ghost hosting | BROKEN (503, expired) | 2026-06-22 | Self-host on Railway (in progress) |
| Portfolio site | Built, deploying | 2026-06-22 | Live at portfolio-production-b0ec7.up.railway.app |
| Consulting launch posts | Not written | 2026-06-22 | Write LinkedIn post 1 |
| DM outreach list | Not started | 2026-06-22 | Build list of 20 |
| SAIP Sprint 1 | Blocked (Supabase) | 2026-06-22 | Ping CISSP partner |
| ShopFlow Stripe billing | Not built | 2026-06-22 | After Bluwood confirms paid |
| Buffer automation | Not built | 2026-06-22 | Build week 2 |
| CISA/FBI sources | Not added | 2026-06-22 | Build week 2 |
| First consulting lead | None | 2026-06-22 | Outreach week 1 |
