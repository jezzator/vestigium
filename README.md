# ⚗ Vestigium

> *Volg het spoor · Bouw je deck · Vind de schat*

Vestigium is een strategisch bordspel dat **El Dorado** (race over hexagonen) combineert met **Dominion** (deck-building). Bouw een steeds sterker kaartendeck terwijl je over een hexagonaal bord racet naar de gouden stad.

🎮 **[Speel nu](https://jouwgebruikersnaam.github.io/vestigium/)** &nbsp;·&nbsp; 📖 **[Speluitleg](https://jouwgebruikersnaam.github.io/vestigium/uitleg.html)**

---

## 🗺 Wat is Vestigium?

Je speelt als ontdekkingsreiziger **Elena Vásquez** die op zoek gaat naar de legendarische gouden stad Vestigium. Je rivaal Torres zit je op de hielen.

Elke beurt speel je kaarten voor bewegingspunten, verdien je munten, en koop je sterkere kaarten. Wie als eerste de eindtegel bereikt, wint.

---

## ✨ Features

- **Hexagonaal bord** — versleepbaar, automatisch gegenereerd per spel
- **Deck-building** — start met 10 basiskaarten, koop steeds betere kaarten
- **7 kaarttypes** — Actie ⚡, Schat 💰, Aanval ⚔, Reactie 🛡, Duurte ⏳, Buit 💎, Vloek 💀
- **50+ unieke kaarten** — elk met eigen effect en strategie
- **AI tegenstander** — 3 moeilijkheidsgraden (makkelijk / gemiddeld / moeilijk)
- **Campaign mode** — 6 hoofdstukken × 8-10 levels met een visuele kaart
  - Persistent deck tussen levels
  - Rust-, winkel- en verhaalnodes
  - 3 levens per hoofdstuk
- **Aanval & verdediging** — val de tegenstander aan, blokkeer met reactiekaarten
- **Loot-triggers** — verdien buitkaarten via speciale acties
- **Twee-spelers modus** — speel lokaal tegen elkaar
- **Voorgemaakte marktsets** — 9 sets van beginner tot gevorderd

---

## 🎯 Spelregels (kort)

| Fase | Actie |
|------|-------|
| ⚡ **Actiefase** | Speel actie-, aanvals- en duurtekaarten (2 acties per beurt) |
| 💰 **Koopfase** | Speel schatten voor munten, koop kaarten uit de markt |
| ↷ **Opruimen** | Alles naar aflegstapel, trek 5 nieuwe kaarten |

**Doel:** als eerste de eindtegel 🏛 bereiken. Terrein kost bewegingspunten:
- 🌿 Jungle — vereist jungle-punten
- 🚣 Water — vereist water-punten  
- 🪙 Markt — vereist markt-punten
- 🌍 Universeel — werkt overal

---

## 📖 Campaign

Reis door **6 hoofdstukken** op zoek naar Vestigium:

| # | Hoofdstuk | Sfeer |
|---|-----------|-------|
| 1 | Het Vertrek | San Cristóbal — de eerste stappen |
| 2 | De Jungle | Ondoordringbaar oerwoud |
| 3 | De Rivieroversteek | Wilde stromen |
| 4 | De Ruïnes van Akabal | Oude geheimen |
| 5 | Het Hoogland | IJle lucht en gevaar |
| 6 | Vestigium | De gouden stad |

Elk hoofdstuk heeft een map met **8-10 nodes**: gevechten ⚔, elites 💀, rustplaatsen 🔥, winkels 🏪, verhaal 📖 en een eindbaas 👑.

Je **deck blijft bewaard** tussen levels — elke aankoop telt.

---

## 🃏 Kaarttypes

| Type | Badge | Effect |
|------|-------|--------|
| Actie | ⚡ | Beweging, kaarten trekken, economie |
| Schat | 💰 | Zilver, Goud, Platina — munten voor de koopfase |
| Aanval | ⚔ | Hindert de tegenstander |
| Reactie | 🛡 | Blokkeer aanvallen vanuit je hand |
| Duurte | ⏳ | Effect deze beurt én de volgende |
| Buit | 💎 | Krachtige kaarten verdiend via triggers (altijd ≥+3💰) |
| Vloek | 💀 | Nutteloze kaart in je deck gestopt door aanvallen |

---

## 🚀 Lokaal draaien

```bash
# Clone de repository
git clone https://github.com/jouwgebruikersnaam/vestigium.git
cd vestigium

# Start een lokale server
python3 -m http.server 8080

# Open in browser
# http://localhost:8080
```

Of gebruik **VS Code Live Server**: klik rechts op `index.html` → *Open with Live Server*.

> ⚠️ Dubbelklikken op `index.html` werkt niet — de browser blokkeert dan externe scripts. Gebruik altijd een lokale server of GitHub Pages.

---

## 🛠 Technisch

- **Pure HTML + JavaScript** — geen build-stap nodig
- **React 18** — voor de UI (geladen via CDN)
- **JSX vooraf gecompileerd** — geen Babel in de browser
- **~230KB** — alles-in-één bestand
- **Mobiel-vriendelijk** — versleepbaar bord, touch-ondersteuning

---

## 📁 Bestanden

| Bestand | Omschrijving |
|---------|-------------|
| `index.html` | Het spel — volledig zelfstandig |
| `uitleg.html` | Volledige speluitleg |
| `Vestigium.jsx` | Broncode (React JSX) |

---

*Gebouwd met ❤️ en veel ⚗*
