# Architecture

## Nuværende demo

```text
Browser
├── index.html     struktur og tilgængelighed
├── styles.css     tokens, layout og responsive regler
├── app.js         lokal state, rendering og interaktioner
└── demo-data.json dokumenteret eksempeldata
```

Der er ingen buildproces, serverkode, cookies, lokal lagring eller tredjeparts-API'er. Google Fonts og Unsplash-billeder indlæses eksternt; resten er statisk.

## Hvorfor vanilla HTML/CSS/JS

- Gratis GitHub Pages-deployment.
- Ingen installation eller afhængighedsrisiko.
- Lavt vedligeholdelsesbehov i valideringsfasen.
- Kan vises og tilpasses hurtigt.

## Mulig produktionsarkitektur — ikke besluttet

Hvis piloten valideres, kan en ny teknisk beslutning overveje:

- Frontend: Next.js/TypeScript
- Auth og database: administreret EU-hostet løsning
- Betaling: PSP med understøttelse af depositum
- Beskeder: dansk/EU-kompatibel SMS- og e-mailudbyder
- Kalender: integration frem for hjemmelavet kalenderkerne

Produktionsvalg kræver datakortlægning, databehandleraftaler, sikkerhedsreview, backup, logging, samtykkedesign og juridisk vurdering.

## Dataetik

Farveformler, noter og fotos kan være personhenførbare. En rigtig løsning skal minimere data, skelne servicebeskeder fra markedsføring og give ejeren klare slette- og eksportmuligheder.
