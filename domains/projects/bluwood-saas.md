# Project: Bluwood Order Management SaaS

## What It Is
Custom order management SaaS built for Bluwood, a local custom door manufacturer in NW Arkansas. Live in production, actively used today with reported success.

## Stack
- Frontend: Next.js 14 + Tailwind + shadcn/ui (repo: `damonwillis-ops/supa-suite`)
- Backend: Supabase (PostgreSQL)
- Auth: Supabase Auth
- Hosting: Vercel (frontend) + Supabase (DB)
- Local project: `/Users/damonwillis/projects/bluwood/`

## Data Model
- Customers (id, name, email, phone, address, notes)
- Orders (customer_id, title, description, status, due_date, price)
  - Status flow: quote → in_production → ready → delivered → cancelled
- comms_log (customer communications history)

## Strategic Importance — READ THIS

Damon has already shipped a SaaS product to a real customer. It works. This is proof, not a pitch.

This matters for three reasons:

1. **Consulting credibility:** "I built and deployed a custom SaaS for a local manufacturer currently in production" is a stronger closer than any credential. Shows he ships, not just advises.

2. **Expansion play:** Every small manufacturer, custom fabricator, millwork shop, and trade business in NW Arkansas has the same order-tracking problem Bluwood had. This could be a vertical SaaS (local/regional first, then national). Not Damon's primary focus but worth noting.

3. **Portfolio anchor:** The portfolio site should reference this as a live deployed product.

## Current Status
Live and in use. No known active development work.

## What to Surface in Advisory/Consulting Conversations
"I've built and deployed software that's running in production today for a local manufacturer." This reframes Damon from security consultant to builder-advisor — a different and more valuable category.

## Last Updated
2026-06-22
