# Project: Groundtruth

## What It Is
Automated B2B physical security intelligence newsletter. Practitioner analyst takes targeting enterprise CSOs/Security Directors. Ghost + Stripe. Railway cron. Fully automated: scrape → Claude pipeline → Ghost publish → LinkedIn post generation.

## Current Status
Railway deploy fixed (2026-06-22). 2 issues published. 0 subscribers. Pre-launch.

## Repo
`/Users/damonwillis/Groundtruth/`

## Stack
- Scraper: RSS/HTML from SecurityInfoWatch, Security Sales, Loss Prevention, Campus Safety, Dark Reading, OODA Loop, Red Analysis Group, Verkada
- Pipeline: Claude Opus 4.8 → digest JSON with analyst takes (sections: threat, tech, incidents, compliance, quick hits)
- Publisher: Ghost Admin API → draft post with formatted HTML
- LinkedIn: Claude generates post → emails to Damon for manual paste (Buffer automation pending)
- Card image: Pillow-generated branded image for LinkedIn

## Growth Roadmap
Full plan: `/Users/damonwillis/Groundtruth/docs/growth-roadmap.md`

### Phase 1 (next 2 weeks) — Fix Automation
- Add CISA + FBI RSS to scraper
- Buffer API auto-queue (replace email → manual paste)
- Reddit post generator with Telegram approval prompt

### Phase 2 (Month 2) — Brand Presence
- Custom domain (~$12/yr)
- LinkedIn Company Page
- Ghost welcome email

### Phase 3 (Month 3, ~500 subs) — Monetization
- Sponsor page (Carrd, $19/yr)
- Job board (Pallet free tier)
- Sponsor outreach to Genetec, Lenel, Milestone, Axis, ZeroEyes, Evolv, Verkada

## Cost
- Current: ~$8-20/mo (Railway + Ghost + Anthropic API ~$3-5/mo)
- Phase 1 additions: ~$0 (Buffer free, Reddit free, CISA free)
- Domain: ~$12/yr when ready
- Break-even: first sponsor issue at ~1,000 subs

## LinkedIn Strategy
Post from personal profile (Damon Willis) until 500+ subs — 10x algorithm advantage over company page. Stand up Groundtruth company page at Phase 2 as brand destination. Never abandon personal posting.

## Website
Ghost IS the website. Custom domain at Phase 2. Carrd sponsor page at Phase 3. No custom dev.

## Revenue Model
1. Sponsorships: $2,500-4,000/issue at 1,000+ subs
2. Job board: $500-1,500/post at 2,000+ subs
3. Consulting pipeline: inbound leads from visibility (starts immediately)

## Subscriber Targets
- 60 days: 100 subs
- 6 months: 500 subs
- Sponsor-ready: 1,000 subs

## Next Actions (in order)
1. Post issue 2 today
2. DM 20 security peers directly asking for read
3. Build Buffer integration (Phase 1, Task 2)
4. Add CISA/FBI sources (Phase 1, Task 1)

## Goal Alignment
→ goals.md: "Grow Groundtruth to sustainable revenue" (18mo horizon)
→ priorities.md: #1 this quarter

## Last Updated
2026-06-22
