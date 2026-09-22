# GGhaft — site structure

Local service business, single location, near-zero existing web presence (see research.md). This is a from-scratch build, not a migration — no legacy URLs to preserve.

Site is small on purpose: one location, two core services, no e-commerce cart, no need for a service hub of 20 pages. Fewer pages done well beats a deep tree for a business this size.

## URL tree

```
/                           Home
/uslugi/haft-komputerowy/   Computer embroidery
/uslugi/nadruki/            Printing on clothing
/uslugi/odziez-firmowa/     Corporate & workwear branding (B2B bundle)
/realizacje/                Portfolio / past work
/o-nas/                     About
/kontakt/                   Contact
```

No `/blog/` at launch — nothing to write about yet (no case studies, no verified expertise angle beyond the name). Add later if the client wants ongoing content; don't scaffold it now.

No `/uslugi/` hub page — with only 3 service pages, a hub is a pointless extra click. Link them directly from the home page and nav.

## Page-by-page

### `/` — Home
- H1 with primary service + location: "Haft i nadruki na odzieży — Krzyszkowice"
- Short intro (2-3 sentences): what they do, who for (private customers + firms)
- 3 service cards linking to the service pages
- Portfolio teaser (4-6 images) linking to `/realizacje/`
- NAP block + map embed (address, phone, hours) — footer or dedicated section
- LocalBusiness schema
- CTA: phone number + contact form link

### `/uslugi/haft-komputerowy/` — Computer embroidery
- What computer embroidery is, in plain language (competitors like nadrukihaft.pl do this well — explain the process, not just sell it)
- What it's applied to: t-shirts, hoodies, workwear, patches/naszywki
- Turnaround expectations — **TBD, no data, ask client**
- Pricing — **TBD, none found anywhere, ask client**
- Gallery of embroidered pieces (subset of `/realizacje/`)
- CTA to contact

### `/uslugi/nadruki/` — Printing on clothing
- Same structure as embroidery page: what it is, techniques used (DTF/sublimation/screen — **unconfirmed, ask client which methods they actually use**), what it's applied to
- Gallery
- CTA to contact

### `/uslugi/odziez-firmowa/` — Corporate & workwear branding
- Targets the B2B intent explicitly (bulk orders, company logos, uniforms) — this is the page competitors (Sakohaft, Haft-Print) lead with for business customers
- Combines embroidery + print as options for company branding
- Minimum order quantities, lead times — **TBD, ask client**
- CTA: quote request (not just generic contact — B2B buyers want a quote flow)

### `/realizacje/` — Portfolio
- Photo gallery of completed work, filterable/grouped by embroidery vs. print if there's enough volume
- **Blocker: no photos currently available from any source checked.** This page can't be built with real content until the client supplies images — flag this at the checkpoint, don't fill with stock photos (kills trust for a business that's already invisible online)

### `/o-nas/` — About
- Owner: Grzegorz Galas (inferred from registered name, not confirmed — verify at checkpoint)
- How long in business — **founding year unverified, ask client**
- Why embroidery + print, what makes them different locally
- This page carries the E-E-A-T weight for a business with zero other online signals — worth getting right once real input exists

### `/kontakt/` — Contact
- NAP matching CEIDG exactly: GG Haft Grzegorz Galas, Krzyszkowice 388, 32-445 Krzyszkowice
- Phone: 513770517 — **unverified beyond client brief, confirm before publishing**
- Hours: Mon–Fri 08:00–17:00, closed Sat/Sun — **unverified beyond client brief, confirm before publishing**
- Google Plus Code VWQC+JP — **unverified, confirm or replace with a real Maps pin once the client confirms/creates a Google Business Profile**
- Map embed, contact form, direct phone/email links

## Content blockers to resolve before build

Everything below is missing and needs the checkpoint conversation (per research.md) before the corresponding page can ship with real content, not placeholders:
- Service list with confirmed offerings (embroidery/print/workwear split)
- Any pricing or "starting from" figures
- Photos of actual work — required for `/realizacje/` and service page galleries
- Phone, hours, Plus Code confirmation
- Owner name/background confirmation for `/o-nas/`
- Whether the Facebook page is real/current — if so, cross-link it

Until these land, build the pages with structure + schema in place and clearly marked placeholder copy, not fake specifics.
