# Berliner Fresskorb 🧺

An interactive, single-page **gourmet hamper builder** — a wedding gift planner for assembling a curated *Fresskorb* of rare, special culinary items sourced from **physical shops across Berlin** (nothing ordered online).

Built as one self-contained `index.html` (no build step) and published via Plesk on every push.

## What it does

- **70 curated rare items** across 46 walk-in shops — from Oscietra caviar and 25-year balsamico to Rogacki's smoked eel, natural wine, craft beer, German rye whisky & sake, artisan sourdough, destination chocolate, Syrian baklava, Alpine cheese, jamón ibérico, Korean gochujang and Phú-Quốc fish sauce — plus a deep bench of **non-perishable** goods (truffle honey, bottarga, Christine Ferber confiture, conservas, Gragnano pasta, Berlin amaro, Baumkuchen, marzipan, François Pralus chocolate …).
- **Tailored to the couple** — Cornelius & Lisa actually *run* the 8th-generation **Hotel Brauerei Gasthof Höhn** near Bamberg (their own wood-fired Kellerbier, schnapps and Schäuferla), so the baskets deliberately bring them the cosmopolitan things they *can't* pour or cook at home, plus personal in-jokes from years of chat history (a home-sushi night, döner "mit allem", the "Cpt. Spliffhook" hemp wink) — and skip harsh schnaps and stodgy desserts they dislike.
  - **Three price tiers:** **"Für Cornelius & Lisa · klein / mittel / groß"** (≈ €76 / €141 / €197, up to €200).
  - **Five themed baskets for them:** *Bier für die Brauer* (world beer styles they don't brew), *Heim-Sushi-Abend*, *Döner & Mezze daheim*, *Welt-Speisekammer*, *Sonntags-Brunch zu zweit*.
- **"Haltbar ∞" filter** — isolate only the shelf-stable, travel-proof items (53 of 70); every card is badged *∞ haltbar* or *❄ frisch*.
- **Shareable links** — your selection lives in the URL (`#k=…`). Hit **🔗 Teilen-Link** to copy it; opening that link restores the exact basket, lights up the matching preset, and shows a "shared basket" banner.
- **11 suggested hampers** — 3 personal tiers + 5 themed baskets for the couple + 3 Berlin classics (Ur-Berliner, Luxus-Körbchen, Vorratskorb) — each with a rationale for *why* the combination is interesting. Load one, then freely recombine.
- **Live receipt** — total and per-person split (two givers) recalculate instantly as you add/remove items.
- **Shopping route** — counts the distinct shops and districts a given basket requires.
- **Interactive map** (Leaflet + CARTO) — every source shop is plotted; the ones in your basket light up, and each marker lists the items you've chosen there.
- **Copy basket** — exports a plain-text shopping list to the clipboard.

## Sources

Real Berlin delicatessens, market-hall vendors and artisan producers — KaDeWe Feinschmeckeretage, Rogacki, Maître Philippe & Filles, Goldhahn und Sampson, Sawade, Belyzium, The Barn, Berliner Brandstifter, Preussische Spirituosen Manufaktur, Markthalle Neun (Kumpel & Keule, Sironi, SoulSpice, Käsestände), ausberlin (Stadthonig), MYCONBINI, Paper & Tea, OEL Berlin, Trüffel Company, Sardinen.Bar, SenfSalon, Viani Alimentari, Dr. Kochan Schnapskultur, Konditorei Buchwald (Baumkuchen since 1852), Viniculture, Weinhandlung Suff, Planet Wein, The Muted Horn, Hops & Barley, BRLO, Stork Club House of Rye, Sake Kontor, Vom Fass, Domberger Brot-Werk, Sofi Bakery, Zeit für Brot, Rausch Schokoladenhaus, Goldhelm, Du Bonheur, Damaskus Konditorei, Wald Königsberger Marzipan, Peppi Käse Lager, Salumeria Lamuri, Salumeria da Pino, Palacios & Palacios, Chili & Paprika, Asia Market Lee and Dong Xuan Center.

> Prices are realistic 2026 estimates and may vary in store. Check opening hours before visiting — some houses keep special times.

## Tech

Plain HTML/CSS/JS. Fonts: Fraunces · Hanken Grotesk · Space Mono. Map via Leaflet 1.9 with CARTO light tiles. No framework, no build.
