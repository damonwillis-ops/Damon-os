# Project: ShopFlow — Custom Order Management SaaS

## What It Is
Vertical SaaS for small custom manufacturers and trade businesses. Order lifecycle tracking (quote → in_production → ready → delivered), customer management, comms log. Built on Next.js + Supabase. Already live with one customer (Bluwood, NW Arkansas custom door manufacturer).

## Origin
Built pro bono for Bluwood in exchange for a table. Works in production today. Converting to paid subscription model and expanding to multi-tenant universal product.

## Repos
- `damonwillis-ops/supa-suite` — main codebase (Next.js 14 + Tailwind + Supabase)
- Local: `/Users/damonwillis/projects/bluwood/`

## Current Stack
- Frontend: Next.js 14 + Tailwind + shadcn/ui
- Backend/DB: Supabase (PostgreSQL + Auth)
- Hosting: Vercel (frontend) + Supabase (DB)

## Status
- Bluwood instance: LIVE, in active use
- Multi-tenant: NOT BUILT
- Billing: NOT BUILT
- Product name: ShopFlow (placeholder until confirmed)

## Target Market
Small custom manufacturers and trade businesses with order-tracking problems:
- Custom door/window manufacturers
- Cabinet shops, millwork
- Metal fabricators
- Upholstery/custom furniture
- Any shop running quote-to-delivery workflows on spreadsheets

NW Arkansas first (warm network), then regional/national.

## Pricing Model
- Founder rate (Bluwood): $49/mo
- Standard: $99/mo per business
- 10 customers = ~$990/mo MRR
- 50 customers = ~$4,950/mo MRR

## What Universal Build Needs
- Multi-tenant data isolation
- Stripe billing + subscription management
- Customer-facing order status portal (link-based, no login required)
- Quote-to-invoice PDF generation
- Photo/document attachments per order
- Configurable order statuses per business type
- Onboarding flow for new tenants
- Estimated build: 3-4 weeks on top of existing MVP

## Strategic Position
Fastest path to recurring SaaS revenue. Product already works. First customer already using it. Incremental effort vs. SAIP (greenfield build). Competes for time not customers.

## Decision Rule
Convert Bluwood to paid first (this week, zero build). Hold universal build until SAIP Sprint 1 scaffolded. Then decide allocation.

## Immediate Next Action
Call/text Bluwood owner: "I'm turning this into a product. Founder rate — $49/mo. You stay on it, I use you as a reference customer." 5-minute conversation.

## Last Updated
2026-06-22
