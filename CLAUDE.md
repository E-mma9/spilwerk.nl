# Spilwerk — project memory voor Claude Code

Dit bestand wordt automatisch geladen bij elke Claude Code-sessie in deze map. Houd 'm bondig.

## Wat dit project is

Werkmap voor **Spilwerk**, opgericht door Emmanuel Tekle en Eren Kongul. **Vriendelijke IT-hulp aan huis** voor particulieren en zelfstandige professionals in heel Overijssel. Heuvelshulp-achtig model — niet een MKB-consultant, wel een laagdrempelige "ik kom langs"-dienst.

## Wat dit project NIET is

- Niet een B2B IT-consultant met vaste-prijs pakketten voor MKB-bedrijven (eerdere positionering, bewust losgelaten)
- Niet specialistisch security- of compliance-werk (NIS2, ISO, pentests)
- Niet enterprise / mid-market detacheringswerk

| Map | Wat |
|---|---|
| `site/` | Single-page website (`index.html` is de hele site behalve `werk/tankstation.html`). Statisch HTML/CSS/JS, geen build-step. |
| `leadgen/` | Python-tool voor outreach-concepten. Minder relevant voor B2C — vooral nuttig voor zelfstandige-professionals tier. |
| `marketing/` | Outreach-plan: Marktplaats, Google Business Profile, lokale Facebook-groepen, buurt-flyers. LinkedIn is **niet** primair kanaal voor B2C. |
| `business/` | Algemene voorwaarden, factuur-template, kostprijs. Discovery-script en offerte-template zijn vooral relevant voor zelfstandige-professionals tier. |

## Diensten — vijf herkenbare categorieën

Bij wijzigingen aan diensten **drie plekken synchroon houden**:

1. `site/index.html` — diensten-grid in `#diensten` sectie
2. `leadgen/prompts/outreach.md` — system prompt voor Claude
3. `business/kostprijs.md` — marge-analyse

| Dienst | Tarief | Voor wie |
|---|---|---|
| Computer-hulp (traag, virus, herinstallatie) | vanaf €55/bezoek | Particulier |
| Wifi & internet | vanaf €55/bezoek | Particulier |
| Telefoon & tablet | vanaf €55/bezoek | Particulier (vaak senioren) |
| Veilig online & backup | vanaf €55/bezoek | Particulier + zelfstandigen |
| Voor zelfstandigen (zakelijk e-mail, backup, onboarding) | €175/halve dag | ZZP / zelfstandige professional |
| Website bouwen (statisch) | €450 incl. hosting-setup | ZZP'er zonder site |
| Website bouwen (WordPress) | €595 incl. domein + hosting | ZZP'er die zelf wil aanpassen |
| Webapplicatie / maatwerk tool | vanaf €950 | Klein bedrijf met Excel-chaos |
| Monitoring & alerts | €25/mnd per dienst | Iedereen met website of server |

Case study webapp: `/werk/tankstation.html` — bewijst dat hij grotere dingen aankan.

## Tariefstructuur (uurbasis, niet pakket-prijs)

- **Bezoek aan huis (1e uur incl. voorrijden binnen Overijssel):** €60
- **Daarna per begonnen kwartier:** €15 (= €60/u)
- **Hulp op afstand:** €45/u
- **Klein klusje <30 min op afstand:** €30
- **Avond/weekend:** +25%
- **Werkt het niet:** €0 (geen kosten als probleem niet opgelost)

## Brand & toon

- **Naam:** Spilwerk (warm, gezellig, persoonlijk — net als Heuvelshulp)
- **Toon:** vriendelijk, jij/je, geen jargon, korte zinnen, "ik" niet "wij"
- **Visueel:** warme crème (#FBF6EE), zacht groen accent (#4A7C59), warm oranje voor CTAs (#E8865B), Manrope sans-serif. Ronde randen (border-radius), shadows zacht. **Niet** meer editorial-industrial.
- **Niet:** zakelijk u-aanspreking, IT-jargon, "wij geloven dat...", consultancy-praat

## Belangrijke contextpunten

- Domein `spilwerk.nl` is **geregistreerd** (april 2026). Nog niet live — site staat klaar voor Cloudflare Pages deploy.
- KvK-inschrijving wordt opgepakt; Emmanuel wil dit voor expense-aftrek + officieel kunnen factureren.
- Telefoonnummer: **06-87433537** (ingevuld in site/assets/script.js en site/index.html).
- Werkgebied: **heel Overijssel** (Hengelo, Enschede, Almelo, Borne, Oldenzaal, Haaksbergen, Zwolle, Deventer, Kampen, Steenwijk, etc.)
- Total Tankstation case study staat live als `werk/tankstation.html` — gebruik 'm voor zelfstandige-professionals doelgroep, niet als hoofdverhaal voor particulieren.
- Emmanuel Tekle (20) en Eren Kongul (20) — beiden 3e jaar HBO ICT (Cloud & Cybersecurity, Saxion). Emmanuel werkt parttime als helpdesk-engineer bij Livio. Eerlijk over student-status op site — geen schande, juist credibility-boost.

## Werkwijze in deze repo

- Bij site-wijzigingen: lokaal openen via `Start-Process site\index.html` (geen Python lokaal beschikbaar).
- Bij CSS-wijzigingen: alle kleuren/typografie via `:root` custom properties in `site/assets/style.css`.
- Geen build-step, geen npm. Bewust simpel gehouden.

## Wat NIET doen zonder vraag

- Geen diensten toevoegen buiten scope: NIS2, M365-migraties, AI-werksessie, enterprise security — te ambitieus voor zijn niveau
- Geen B2B / enterprise-koers voorstellen (dat pad is bewust losgelaten)
- Geen logo / branding-assets genereren (groen rondje + naam is genoeg)
- Geen tracking/analytics toevoegen (bewust geen Google Analytics)
- Geen npm/build-tooling toevoegen aan `site/`
- Geen automatische LinkedIn / e-mail verzending bouwen — TOS-risico

## Geleerde lessen uit eerdere overshoot

Eerder werd Spilwerk gepositioneerd als 8-9 pakketten MKB-consultant (incl. NIS2-readiness). Te ambitieus voor 3e-jaars HBO. Pivot naar B2C IT-hulp aan huis is bewust kleiner, haalbaarder, sneller eerste klant. **Niet terug pivoten zonder expliciete vraag.**
