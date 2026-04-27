# Flyer A6 — bestellen in 2 stappen

Print-ready flyer voor brievenbussen, prikborden (supermarkt, bibliotheek, buurthuis), wasserettes en seniorencafé. Zelfde visuele taal als het visitekaartje. **`flyer.pdf`** is direct stuurklaar — A6 staand, 111×154mm incl. 3mm bleed.

## 1. Preview bekijken (30 sec, optioneel)

Open `preview.html` in je browser om de flyer op werkelijke grootte (A6, 105×148mm) te zien. Of open `flyer.pdf` direct.

> **Tekst gewijzigd?** Run `marketing/generate-pdfs.ps1` (dubbelklikken) om de PDF te regenereren.

## 2. Uploaden bij drukker (5 min)

### Optie A — Drukwerkdeal (aanbevolen, NL, snel)
- Ga naar [drukwerkdeal.nl/flyers](https://www.drukwerkdeal.nl/nl/flyers)
- Kies: **A6 (105×148mm)** · **enkelzijdig** · **170 gr/m² gesatineerd MC**
- Aantal: **500 stuks** (~€25-30, levering 2-4 dagen) of **1000 stuks** (~€40-50)
- Upload **`flyer.pdf`**

### Optie B — Vistaprint (goedkoper, maar 5-7 dagen)
- Ga naar [vistaprint.nl/flyers-folders/flyers](https://www.vistaprint.nl/flyers-folders/flyers)
- Kies: **A6** · enkelzijdig · 170 gr
- Upload **`flyer.pdf`**

## 3. Verspreiden

**Geen post NEE/JA stickers negeren** — boete-risico. Wel toegestane plekken:

| Plek | Hoe |
|---|---|
| Brievenbussen zonder NEE-sticker | Eigen straat + omliggende straten in jouw woonplaats. Loop 1-2 uur per weekend, dek 100-200 brievenbussen. |
| Supermarkt-prikborden | Vraag bij service-balie — meestal mag het gratis. Albert Heijn, Jumbo, Plus hebben vaak een mededelingenbord. |
| Bibliotheek | Hengelo / Enschede / Almelo / Borne — prikbord bij ingang. Vraag bij balie. |
| Buurthuis & wijkcentra | Goede mix bewoners / senioren. Loop binnen, vraag personeel. |
| Wasserettes | Vooral senioren komen er. Vraag bij eigenaar. |
| Seniorencafé / open inloop | Sleutel-doelgroep. Vraag de coördinator. |
| Fysiotherapeut / huisarts wachtkamer | Vraag of ze er één bij de andere folders mogen leggen. |

**Niet doen:**
- Op auto's onder ruitenwissers — irriteert, schaadt reputatie
- Bij bedrijfspanden (geen B2C-doelgroep)
- Bij scholen (verkeerde demografie)

## Bestanden in deze map

| Bestand | Wat |
|---|---|
| **`flyer.pdf`** | **Print-ready PDF — direct uploaden bij drukker** |
| `flyer.svg` | Source vector — A6 staand met 3mm bleed |
| `preview.html` | Visuele preview op werkelijke grootte — bron voor de PDF |

## Specificaties (voor bij druk)

- **Formaat**: A6 (105×148mm) staand
- **Bleed**: 3mm rondom (bestand is 111×154mm)
- **Veilige zone**: 5mm vanaf zichtbare rand
- **Kleuren**: paper-crème #FBF6EE · groen #4A7C59 · ink #2A2A28
- **Lettertype**: Manrope (in SVG met fallback naar Helvetica)
- **Resolutie**: vector (oneindig schalen)

## Troubleshooting

**Tekst aanpassen** (andere actie, bepaalde doelgroep): bewerk `preview.html` of `flyer.svg` in een tekst-editor (VS Code / Notepad). Run daarna `marketing/generate-pdfs.ps1` om de PDF te regenereren.

**Drukker meldt issue met PDF**: regenereer met `generate-pdfs.ps1` om een verse versie te krijgen, of upload de SVG als alternatief.
