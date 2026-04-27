# Visitekaartje — bestellen in 2 stappen

Alle gegevens staan er al in (06 87 43 35 37 · admin@spilwerk.nl · Emmanuel + Eren als IT-consultant). **`visitekaartje.pdf`** is direct stuurklaar — 2 pagina's (voor + achter), 91×61mm incl. 3mm bleed.

## 1. Preview bekijken (30 sec, optioneel)

Open `preview.html` in je browser om beide kanten op werkelijke grootte te zien. Of open `visitekaartje.pdf` direct.

> **Tekst gewijzigd?** Run `marketing/generate-pdfs.ps1` (dubbelklikken) om de PDF te regenereren.

## 2. Uploaden bij drukker (5 min)

Twee opties — beide werken met SVG of PDF:

### Optie A — Drukwerkdeal (aanbevolen, NL, snel)
- Ga naar [drukwerkdeal.nl/visitekaartjes](https://www.drukwerkdeal.nl/nl/visitekaartjes/visitekaartjes-standaard)
- Kies: **Standaard 85×55mm** · **dubbelzijdig** · **350 gr** · **mat-laminaat**
- Aantal: **250 stuks** (~€25, levering 2-4 dagen)
- Upload **`visitekaartje.pdf`** — Drukwerkdeal pakt automatisch page 1 als voorzijde en page 2 als achterzijde

### Optie B — Vistaprint (goedkoper, maar 5-7 dagen)
- Ga naar [vistaprint.nl/visitekaartjes](https://www.vistaprint.nl/visitekaartjes)
- Kies: **Standaard 85×54mm** · dubbelzijdig
- Upload **`visitekaartje.pdf`** — Vistaprint splitst de twee pagina's automatisch over voor- en achterzijde

## 3. Klaar

Levering 2-7 dagen. Rondbrengen volgens `marketing/tracker.md` § "Flyers + visitekaartjes — waar ze ophangen".

---

## Bestanden in deze map

| Bestand | Wat |
|---|---|
| **`visitekaartje.pdf`** | **Print-ready PDF — direct uploaden bij drukker (2 pagina's: voor + achter)** |
| `voorzijde.svg` | Source vector — voorkant kaartje (paper-crème met spil-logo) |
| `achterzijde.svg` | Source vector — achterkant (groen met contact-info) |
| `preview.html` | Visuele preview op werkelijke grootte — bron voor de PDF |

## Specificaties (voor bij druk)

- **Formaat**: 85×55 mm (NL standaard)
- **Bleed**: 3mm rondom (bestand is 91×61mm = 85×55 + 3mm bleed)
- **Veilige zone**: 6mm vanaf rand
- **Kleuren**: paper-crème #FBF6EE · groen #4A7C59 · ink #2A2A28
- **Lettertype**: Manrope (in SVG met fallback naar Helvetica)
- **Resolutie**: vector (oneindig schalen)

## Troubleshooting

**Tekst aanpassen** (kleur, lay-out, andere tekst): bewerk `preview.html` of de SVG's in een tekst-editor (VS Code / Notepad). Run daarna `marketing/generate-pdfs.ps1` om de PDF opnieuw te genereren.

**Drukker meldt issue met PDF**: regenereer met `generate-pdfs.ps1` om een verse versie te krijgen, of upload de SVG-bronbestanden als alternatief (Drukwerkdeal accepteert beide).
