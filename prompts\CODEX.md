# Codex working agreement

Brug denne fil som arbejdsinstruktion ved fremtidige ændringer.

## Før ændringer

1. Læs `README.md`, `docs/PROJECT.md`, `docs/PRODUCT.md`, `docs/DESIGN.md`, `docs/UX.md` og `docs/DECISIONS.md`.
2. Bevar demoens frontend-only afgrænsning, medmindre en ny accepteret beslutning ændrer den.
3. Kontrollér, at ingen rigtige kundedata eller secrets tilføjes.

## Implementeringsregler

- Brug eksisterende HTML/CSS/JS uden buildværktøj.
- Genbrug tokens og komponentmønstre.
- UI-copy skal være dansk, kort og varm.
- Alle nye hovedhandlinger skal fungere lokalt.
- Simulerede funktioner skal aldrig foretage netværkskald.
- Markér uvurderede priser og data som demo.
- Bevar GitHub Pages-kompatible relative stier.

## Afslutning

1. Start en lokal statisk server.
2. Test kunde- og salonflow på 390, 768 og 1440 px.
3. Kontrollér konsollen.
4. Opdatér relevant dokumentation og QA.
5. Saml rettelser i én commit med en konkret besked.

## Prompt til en samlet rettelsesrunde

```text
Read the repository documentation before changing code.
Fix the following observed issues in one focused pass:

[ISSUES]

Preserve the frontend-only scope and existing creative direction.
Run the static demo, test the affected customer and salon flows at
390px and 1440px, check the console, and update documentation only
where behavior or decisions changed.
```
