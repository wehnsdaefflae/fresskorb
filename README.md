# Berliner Fresskorb 🧺

An interactive, single-page **gourmet hamper builder** — a wedding gift planner for assembling a curated *Fresskorb* of rare, special culinary items sourced from **physical shops across Berlin** (nothing ordered online).

Built as one self-contained `index.html` (no build step) and published via Plesk on every push.

## What it does

- **21 curated rare items** — from Oscietra caviar and 25-year balsamico to Rogacki's smoked eel, Sawade pralines, Berlin city honey, tree-to-bar chocolate and single-estate olive oil.
- **5 suggested hampers** (Ur-Berliner, Luxus, Weltreise, Handwerk, Klein & fein) — each with a rationale for *why* the combination is interesting. Load one, then freely recombine.
- **Live receipt** — total and per-person split (two givers) recalculate instantly as you add/remove items.
- **Shopping route** — counts the distinct shops and districts a given basket requires.
- **Interactive map** (Leaflet + CARTO) — every source shop is plotted; the ones in your basket light up, and each marker lists the items you've chosen there.
- **Copy basket** — exports a plain-text shopping list to the clipboard.

## Sources

Real Berlin delicatessens, market-hall vendors and artisan producers — KaDeWe Feinschmeckeretage, Rogacki, Maître Philippe & Filles, Goldhahn und Sampson, Sawade, Belyzium, The Barn, Berliner Brandstifter, Preussische Spirituosen Manufaktur, Markthalle Neun (Kumpel & Keule, Sironi, SoulSpice, Käsestände), ausberlin (Stadthonig), MYCONBINI, Paper & Tea, OEL Berlin.

> Prices are realistic 2026 estimates and may vary in store. Check opening hours before visiting — some houses keep special times.

## Tech

Plain HTML/CSS/JS. Fonts: Fraunces · Hanken Grotesk · Space Mono. Map via Leaflet 1.9 with CARTO light tiles. No framework, no build.
