# Walmart Internal Tools (Active)

These are Damon's internal Walmart projects. Not commercial products. They demonstrate enterprise-scale AI/automation capability and feed the SAIP/career narrative.

## HORIZON
Layered agent system for CCTV/CX Design Program data.
- Repo: `/Users/damonwillis/projects/horizon/`
- 6-layer architecture: Raw → Canonical → Semantic → Metric → Agents → UI
- 20 agents orchestrated, QuickBase as data source
- Answers business questions about CCTV program with traceable definitions
- Partners: Joel (stakeholder), Chase Womack (QB ingestion)
- Status: Phase 1 scaffold complete, first 3 metrics live

## FATHOM Dashboard
Operational cockpit for HORIZON's agent orchestration.
- Repo: `/Users/damonwillis/projects/fathom-dashboard/`
- Two views: Team View (stakeholders) + Builder View (Damon/operators)
- FastAPI backend + React UI + SQLite (r/o fathom.db)
- Stack: Python 3.13+, Node 20+, uv

## APERTURE
CCTV camera design assurance system.
- Repo: `/Users/damonwillis/projects/aperture/`
- Ingests Axis Site Designer exports (.asdpx), validates against ROC store-space truth
- Gates install sign-off — design review before truck rolls
- NOT a camera-event platform. Upstream of GSOC.

## SOAR — Site Owl Automated Repository
Generates SiteOwl bulk-import CSVs for store camera deployments.
- Repo: `/Users/damonwillis/projects/soar/`
- Two modes: QuickBase mode (Chase) + .asdpx mode (Damon)
- Walmart gecgithub: `gecgithub01.walmart.com:d0w0nju/SOAR`
- Partners: Chase Womack

## OVERWATCH
Personal AI co-pilot for navigating Walmart political landscape.
- Repo: `/Users/damonwillis/projects/overwatch/`
- 5 force multipliers: briefing engine, war room, political ledger, decompression, resilience tracker
- Private data in `private/` (gitignored). Sidearm to HORIZON.

## Overdue Report Agent
Consolidates CCTV Project Daily Digest emails into one leadership report.
- Repo: `/Users/damonwillis/projects/overdue-report-agent/`
- Parses .eml files, extracts specialist counts + action items, renders Outlook-safe HTML

## CCTV Design Modernization
Executive strategy package for Richard Ivey meeting.
- Repo: `/Users/damonwillis/projects/cctv-design-modernization/`
- Lead artifact: 2-slide signal deck (PPTX)
- One-time deliverable, not an ongoing system

## Last Updated
2026-06-22
