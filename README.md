# Spilwerk — VEROUDERD, niet meer gebruiken

> ⛔ **Deze repo is vervangen door [`E-mma9/spilwerk`](https://github.com/E-mma9/spilwerk).**
>
> Dat is de enige actuele bron: daar staat de live website (spilwerk.nl wordt vanuit
> die repo gedeployed), de actuele tarieven, het drukwerk en alle marketing-teksten.
>
> Alles van waarde uit deze repo is overgezet: de Google Business Profile-handleiding,
> de Marktplaats-notities, het PDF-generatiescript en de logo-bestanden.
>
> Niet meer in werken. De CNAME en de Pages-workflow zijn hier verwijderd zodat deze
> repo het domein niet kan overnemen.

---

> *Vriendelijke IT-hulp aan huis voor heel Overijssel.*

Dit is de werkmap voor **Spilwerk**, de handelsnaam waaronder Emmanuel Tekle als ZZP'er laagdrempelige IT-hulp levert aan particulieren en zelfstandige professionals in heel Overijssel.

```
spilwerk/
├── site/         # Statische marketing-site (HTML/CSS/JS, geen build-step)
├── leadgen/      # Python-tool die per lead een persoonlijk concept-mail schrijft
├── marketing/    # 30-dagen-plan, kanalen, LinkedIn-posts en outreach-templates
├── business/     # Sales-to-payment cyclus: discovery, offerte, AV, factuur, kostprijs
├── offertes/     # Per-klant offertes (uit git, blijft lokaal)
├── boekhouding/  # Verstuurde facturen + bewijsstukken (uit git, blijft lokaal)
└── CLAUDE.md     # Project-context voor Claude Code-sessies
```

## Waarom Spilwerk en niet emmanueltekle.nl?

`emmanueltekle.nl` is je portfolio — het laat zien wie je bent als techneut. **Spilwerk** is je *bedrijf* — een ding dat klanten kunnen huren, factureren, en aanbevelen. Twee verschillende lezers, twee sites. De portfolio mag rommelig en persoonlijk zijn ("kijk wat ik heb gemaakt"); een bedrijfssite moet één duidelijke vraag beantwoorden: "wat koop ik, voor hoeveel, en waarom werkt dat."

## De brand

- **Naam** Spilwerk — "spil" = pivot/as, "werk" = werk/handwerk. De spil is wat alles bij elkaar houdt; weghalen ervan en het apparaat valt uiteen.
- **Toon** Vriendelijk, jij/je, geen jargon. Zie `CLAUDE.md` in de actuele repo.
- **Domein** `spilwerk.nl` — geregistreerd.

## Leadgen

Lees `leadgen/README.md`. Workflow:

1. Vul `leadgen/seed_leads.csv` met bedrijven uit jouw regio.
2. Run `python leadgen.py` — krijgt per bedrijf een fit-score + concept-mail.
3. **Jij** kiest 5–10, past aan, stuurt handmatig.

## Wat dit *niet* is

- Geen vervanging voor `emmanueltekle.nl`. Houd die. Twee sites, twee doelen.
- Geen ZZP-juridisch advies. Praat met een MKB-accountant voor btw-status (KOR ja/nee), AOV, beroepsaansprakelijkheid.
- Geen garantie op klanten. Outreach werkt op herhaling.

---

© 2026 Emmanuel Tekle. Spilwerk is een handelsnaam in voorbereiding.
