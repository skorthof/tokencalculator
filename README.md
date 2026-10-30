# Byner Recruitment Journey Calculator v3.0

- `index.html`: interactieve recruitment journey met 5 fases, 10 AI-usecases, menselijke stappen en twee batches.
- `pricing.json`: bestaande prijsinstellingen uit v2.7 ongewijzigd overgenomen.
- `admin.html`: bestaande lokale beheerconfiguratie ongewijzigd overgenomen.
- `byner-logo.png`: bestaande Byner-branding.

## Hoe de berekening werkt
Automations: aantal uitvoeren per maand per medewerker x medewerkers x 12 x geschatte kosten per uitvoering.
Batches: aantal cv's x gemeten kosten per cv, eenmalig per organisatie per jaar (optioneel Batch API-voordeel).

## Voorlopige voorbeeldmetingen
De volgende vijf usecases zijn **niet gemeten**; de waarden zijn fictief en duidelijk als 'Voorbeeld' gemarkeerd:
- Assign customer request: 1800 input, 450 output
- Schedule intake meeting: 1250 input, 250 output
- Client intake questions: 4200 input, 1750 output
- Search candidates & outreach: 8200 input, 2850 output
- Constructive rejection feedback: 3000 input, 1400 output

Bestaande gemeten automations en batchmetingen zijn gelijk aan v2.7 gebleven.

## Publiceren
Upload `index.html` en, indien nog niet aanwezig, `byner-logo.png` naar root van GitHub-repository `tokencalculator`.
Laat bestaande `pricing.json` staan om eigen prijzen te behouden.
De admin-pagina op GitHub Pages is publiek bereikbaar: behandel haar niet als beveiligd prijsbeheer.


## v3.1
De maximaal instelbare maandelijkse uitvoeringen verschillen nu per automation, van 12 tot 50 per medewerker. Alle tokenmetingen en prijzen zijn ongewijzigd. Batches blijven 0-100.000.

Typografie: Montserrat via Google Fonts als tijdelijke benadering; het exacte lettertype van byner.com kon niet worden bevestigd. Pas voor een officieel font de CSS-variabele `--byner-font` aan en configureer de geschikte gelicentieerde webfont-bron. Er worden geen fontbestanden meegeleverd.
