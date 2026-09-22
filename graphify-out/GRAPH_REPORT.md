# Graph Report - .  (2026-09-22)

## Corpus Check
- Corpus is ~5,405 words - fits in a single context window. You may not need a graph.

## Summary
- 123 nodes · 133 edges · 20 communities (9 shown, 11 thin omitted)
- Extraction: 74% EXTRACTED · 23% INFERRED · 3% AMBIGUOUS · INFERRED: 30 edges (avg confidence: 0.84)
- Token cost: 12,263 input · 27,773 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Design System & Aesthetics|Design System & Aesthetics]]
- [[_COMMUNITY_Brand Identity & Polish Copy|Brand Identity & Polish Copy]]
- [[_COMMUNITY_Business Entity & Contact Info|Business Entity & Contact Info]]
- [[_COMMUNITY_Company Profile & Competitors|Company Profile & Competitors]]
- [[_COMMUNITY_Embroidery Types & Products|Embroidery Types & Products]]
- [[_COMMUNITY_Apparel & DTF Printing|Apparel & DTF Printing]]
- [[_COMMUNITY_Session & Process State|Session & Process State]]
- [[_COMMUNITY_Local Tooling & Config|Local Tooling & Config]]
- [[_COMMUNITY_Apparel Brand Suppliers|Apparel Brand Suppliers]]
- [[_COMMUNITY_Body Typography System|Body Typography System]]
- [[_COMMUNITY_Headlines Typography System|Headlines Typography System]]
- [[_COMMUNITY_Location Geospatial Code|Location Geospatial Code]]
- [[_COMMUNITY_Tajima Machinery Asset|Tajima Machinery Asset]]
- [[_COMMUNITY_Nowak Warzywa Caps Portfolio|Nowak Warzywa Caps Portfolio]]
- [[_COMMUNITY_3D Baseball Caps Portfolio|3D Baseball Caps Portfolio]]
- [[_COMMUNITY_Softshell & Cap Portfolio|Softshell & Cap Portfolio]]
- [[_COMMUNITY_Fleece Cender Portfolio|Fleece Cender Portfolio]]
- [[_COMMUNITY_Raftistrucks Jackets Portfolio|Raftistrucks Jackets Portfolio]]
- [[_COMMUNITY_Stalcore Workwear Portfolio|Stalcore Workwear Portfolio]]
- [[_COMMUNITY_Embroidered Tool Bag Portfolio|Embroidered Tool Bag Portfolio]]

## God Nodes (most connected - your core abstractions)
1. `Bauhaus — Neo-Brutalist Design` - 23 edges
2. `GG Haft Grzegorz Galas (sole proprietorship)` - 21 edges
3. `GGhaft` - 16 edges
4. `Haft Komputerowy` - 10 edges
5. `Druk DTF` - 9 edges
6. `Site Structure Document` - 8 edges
7. `Contact Page` - 7 edges
8. `Dostawa Odzieży` - 6 edges
9. `Home Page` - 6 edges
10. `Client brief (artifacts/brief.md)` - 4 edges

## Surprising Connections (you probably didn't know these)
- `GGhaft` --semantically_similar_to--> `GGhaft`  [INFERRED] [semantically similar]
  /home/jankuchnia/Desktop/gghaft/index.html → /home/jankuchnia/Desktop/gghaft/DOCS/brief.md
- `Krzyszkowice` --semantically_similar_to--> `Krzyszkowice`  [INFERRED] [semantically similar]
  /home/jankuchnia/Desktop/gghaft/index.html → /home/jankuchnia/Desktop/gghaft/DOCS/brief.md
- `GGhaft` --has_contact_number--> `513770517`  [EXTRACTED]
  /home/jankuchnia/Desktop/gghaft/index.html → /home/jankuchnia/Desktop/gghaft/DOCS/brief.md
- `Site Structure Document` --references--> `GG Haft Grzegorz Galas (sole proprietorship)`  [EXTRACTED]
  /home/jankuchnia/Desktop/gghaft/DOCS/SITE-STRUCTURE.md → /home/jankuchnia/Desktop/gghaft/DOCS/research.md
- `Contact Page` --displays_info_for--> `GG Haft Grzegorz Galas (sole proprietorship)`  [EXTRACTED]
  /home/jankuchnia/Desktop/gghaft/DOCS/SITE-STRUCTURE.md → /home/jankuchnia/Desktop/gghaft/DOCS/research.md

## Communities (20 total, 11 thin omitted)

### Community 0 - "Design System & Aesthetics"
Cohesion: 0.08
Nodes (24): Accent Blue (#0055ff), Accent Red (#e63b2e), Accent Yellow (#ffcc00), Asymmetric Layouts, Background Color (#f5f0e8), Bauhaus Architecture, Bauhaus — Neo-Brutalist Design, Brutalist Architecture (+16 more)

### Community 1 - "Brand Identity & Polish Copy"
Cohesion: 0.12
Nodes (19): GGhaft, Krzyszkowice, 513770517, VWQC+JP Krzyszkowice, Darmowa próba przedprodukcyjna, Figtree Font, GGhaft, Krzyszkowice (+11 more)

### Community 2 - "Business Entity & Contact Info"
Cohesion: 0.18
Nodes (18): Address: Krzyszkowice 388, 32-445 Krzyszkowice, Client brief (artifacts/brief.md), Embroidery (haft) service, Facebook page 'GGHaft | Krzyszkowice', Founding year, GG Haft Grzegorz Galas (sole proprietorship), Google Plus Code: VWQC+JP Krzyszkowice, Gowork.pl business directory contact page (+10 more)

### Community 3 - "Company Profile & Competitors"
Cohesion: 0.31
Nodes (11): Grzegorz Galas (owner), Haft-Print (Hafciarnia Haft-Print) (competitor), Nadrukihaft (Wrocław) (competitor), Sakohaft (competitor), About Page, Computer Embroidery Service Page, Corporate & Workwear Branding Service Page, Site Structure Document (+3 more)

### Community 4 - "Embroidery Types & Products"
Cohesion: 0.20
Nodes (10): Czapki z daszkiem, Haft Bezpośredni, Haft Komputerowy, Kurtki zimowe, Naszywki 3D, Naszywki firmowe, Naszywki mundurowe, Polary (+2 more)

### Community 5 - "Apparel & DTF Printing"
Cohesion: 0.22
Nodes (9): Bluzy z kapturem, CMYK, Druk DTF, Koszulki bawełniane, Odzież sportowa, Odzież streetwear, Sitodruk, Torby bawełniane (+1 more)

### Community 6 - "Session & Process State"
Cohesion: 0.29
Nodes (6): key, pid, port, previous, start_src, start_time

### Community 7 - "Local Tooling & Config"
Cohesion: 0.33
Nodes (5): env, ANTHROPIC_BASE_URL, ENABLE_TOOL_SEARCH, hooks, SessionStart

### Community 8 - "Apparel Brand Suppliers"
Cohesion: 0.33
Nodes (6): Dostawa Odzieży, JHK, Malfini, Portwest, Promostars, Stedman

## Ambiguous Edges - Review These
- `GG Haft Grzegorz Galas (sole proprietorship)` → `Phone: 513770517`  [AMBIGUOUS]
  /home/jankuchnia/Desktop/gghaft/DOCS/research.md · relation: has_phone
- `GG Haft Grzegorz Galas (sole proprietorship)` → `Google Plus Code: VWQC+JP Krzyszkowice`  [AMBIGUOUS]
  /home/jankuchnia/Desktop/gghaft/DOCS/research.md · relation: has_plus_code
- `GG Haft Grzegorz Galas (sole proprietorship)` → `Opening hours (Mon–Fri 08:00–17:00, closed Sat/Sun)`  [AMBIGUOUS]
  /home/jankuchnia/Desktop/gghaft/DOCS/research.md · relation: has_hours
- `GG Haft Grzegorz Galas (sole proprietorship)` → `Founding year`  [AMBIGUOUS]
  /home/jankuchnia/Desktop/gghaft/DOCS/research.md · relation: has_attribute

## Knowledge Gaps
- **84 isolated node(s):** `pid`, `start_src`, `start_time`, `port`, `key` (+79 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **11 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `GG Haft Grzegorz Galas (sole proprietorship)` and `Phone: 513770517`?**
  _Edge tagged AMBIGUOUS (relation: has_phone) - confidence is low._
- **What is the exact relationship between `GG Haft Grzegorz Galas (sole proprietorship)` and `Google Plus Code: VWQC+JP Krzyszkowice`?**
  _Edge tagged AMBIGUOUS (relation: has_plus_code) - confidence is low._
- **What is the exact relationship between `GG Haft Grzegorz Galas (sole proprietorship)` and `Opening hours (Mon–Fri 08:00–17:00, closed Sat/Sun)`?**
  _Edge tagged AMBIGUOUS (relation: has_hours) - confidence is low._
- **What is the exact relationship between `GG Haft Grzegorz Galas (sole proprietorship)` and `Founding year`?**
  _Edge tagged AMBIGUOUS (relation: has_attribute) - confidence is low._
- **Why does `GGhaft` connect `Brand Identity & Polish Copy` to `Apparel Brand Suppliers`, `Embroidery Types & Products`, `Apparel & DTF Printing`?**
  _High betweenness centrality (0.107) - this node is a cross-community bridge._
- **Why does `Haft Komputerowy` connect `Embroidery Types & Products` to `Brand Identity & Polish Copy`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._
- **Why does `Druk DTF` connect `Apparel & DTF Printing` to `Brand Identity & Polish Copy`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._