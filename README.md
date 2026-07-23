# Salon OS — Super Cut concept demo

En premium, frontend-only salgsdemo, der viser, hvordan Super Cut på Frederiksberg kan samle hjemmeside, booking, kundeoverblik og genbooking i én rolig oplevelse.

[Åbn live-demoen via GitHub Pages](https://glennydam.github.io/Salon-OS/)

> Dette er en konceptdemo. Tider, priser, anmeldelser og kundedata er eksempler. Der sendes ingen beskeder, reserveres ingen tider og behandles ingen betalinger.

## Hvad demoen viser

- Editorial landing page for Super Cut
- Behandlinger og interaktiv før/efter-visning
- Komplet, lokal bookingrejse i otte trin
- Roligt ejer-dashboard
- Ugekalender og kundeliste
- Kundeprofil med behandlingshistorik og farvenoter
- Simuleret personlig genbooking
- En præsentation af mulige fremtidige integrationer

## Afgrænsning

Demoen har bevidst ingen backend, login, database, betaling, SMS, kalenderintegration eller rigtige kundedata. Alt kører lokalt i browseren. Det holder valideringen billig og gør det umuligt at forveksle prototypen med et driftsklart system.

## Kør lokalt

Ingen installation er nødvendig.

```bash
python -m http.server 8080
```

Åbn `http://localhost:8080`.

Du kan også åbne `index.html` direkte, men en lokal webserver giver den mest realistiske test.

## Deploy med GitHub Pages

1. Åbn repositoryets **Settings**.
2. Vælg **Pages**.
3. Under **Build and deployment** vælg **Deploy from a branch**.
4. Vælg branch `main`, mappe `/ (root)`, og tryk **Save**.
5. GitHub viser adressen, når siden er publiceret.

Bemærk: Repositoryet er privat. Kontrollér, at dit GitHub-abonnement understøtter Pages fra private repositories, eller gør repositoryet offentligt, hvis demoen skal deles offentligt.

## Projektstruktur

```text
.
├── index.html
├── styles.css
├── app.js
├── data/demo-data.json
├── assets/README.md
├── docs/
├── prompts/CODEX.md
├── .gitignore
└── LICENSE
```

## Dokumentation

- [Projekt og scope](docs/PROJECT.md)
- [Produktkrav](docs/PRODUCT.md)
- [Designretning](docs/DESIGN.md)
- [UX og flows](docs/UX.md)
- [Arkitektur](docs/ARCHITECTURE.md)
- [Roadmap](docs/ROADMAP.md)
- [Beslutninger](docs/DECISIONS.md)
- [QA](docs/QA.md)
- [Salgsdemo-manuskript](docs/SALES-DEMO.md)
- [Codex-arbejdsinstruktion](prompts/CODEX.md)

## Rettigheder

Kode og dokumentation er udgivet under MIT-licensen. Eksterne billeder tilhører deres respektive rettighedshavere og er ikke omfattet af repositoryets licens.
