# Project: SAIP — Security Asset Intelligence Platform

## What It Is
Enterprise SaaS replacing SiteOwl for large-enterprise physical security programs. Device registry with 4-level hierarchy (Org → Site → Floor → Device), floorplan canvas, GPS mapping, AI layer, multi-export. Damon's insider bet: he managed SiteOwl at 4,600 Walmart locations — he knows exactly what it can't do.

## Strategic Position
This is the big play. Groundtruth builds the audience and brand trust. SAIP is the enterprise product that audience would buy. The newsletter readers ARE the target SAIP customers.

## Repos
- `/Users/damonwillis/Developer/SAIP/` — main build (has backend + frontend scaffolded)
- `/Users/damonwillis/projects/saip/` — session log and docs

## Stack (locked, no debate for MVP)
- Frontend: React 18 + Vite + Tailwind + React Konva (canvas) + Mapbox GL JS
- Backend: FastAPI + SQLAlchemy v2 async + Alembic + Celery + Redis
- DB: PostgreSQL 15 + PostGIS + pgvector (Supabase)
- Hosting: Railway (backend) + Vercel (frontend)
- AI layer: claude-sonnet-4-6 primary, claude-haiku-4-5 routing, RAG via pgvector

## Current Build State (as of 2026-06-11 Session 1)
- Session system initialized, CLAUDE.md created
- Backend: NOT YET SCAFFOLDED (Sprint 1 pending)
- Frontend: NOT YET SCAFFOLDED
- DB: Supabase provisioned but PostGIS + pgvector status unknown — needs CISSP partner to confirm
- Next session: Sprint 1+2 scaffold (FastAPI skeleton, SQLAlchemy models, Alembic migrations, JWT auth, RBAC)

## Partners
- CISSP partner owns infrastructure (Supabase, Railway, AWS) — name not documented

## North Star
One paying pilot customer with real data by Month 6 (Sprint 5 complete).

## Sprint Plan
- Sprint 1: Backend scaffold, models, Alembic, JWT auth
- Sprint 2: RBAC, org scoping
- Sprint 3: Device CRUD API + frontend scaffold
- Sprint 4: Celery pipeline, exports (S3/ADLS2/Parquet)
- Sprint 5: AI/RAG layer, prompt caching

## Revenue Model
Enterprise SaaS. Pricing TBD. Target: large-enterprise physical security programs ($50K-200K ACV likely).

## Groundtruth Connection
Groundtruth newsletter builds credibility with security directors → warm inbound for SAIP pilots. This is intentional funnel design, not coincidence.

## Last Updated
2026-06-22
