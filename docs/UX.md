# UX specification

## Guided sales journey

### 1. Kunden opdager Super Cut

Heroen forklarer på få sekunder: personlig frisør, klip/farve/extensions, Frederiksberg og tydelig booking.

### 2. Kunden ser kvalitet

Tre redaktionelle behandlingskort, før/efter-interaktion, filosofi og demoanmeldelser bygger tillid.

### 3. Kunden booker

Flow:

1. Kategori
2. Behandling
3. Ny eller eksisterende kunde
4. Konsultationsdata
5. Dato
6. Tid
7. Kontaktoplysninger
8. Opsummering og eksempelvilkår
9. Bekræftelse

Tilbageknappen bevarer state. Ingen data forlader browseren.

### 4. Ejeren ser dagen

Dashboardet prioriterer næste kunde, dagens tider, en ledig tid og handlinger, der kræver opmærksomhed.

### 5. Ejeren åbner kunden

Maria-profilen viser rytme, farvepræferencer, hensyn, produkter og behandlingshistorik som én fortælling.

### 6. Systemet foreslår genbooking

Ejeren får en kort årsag og en redigerbar personlig tekst. Klik på send ændrer kun lokal UI-status.

## Fejl- og tomtilstande i demoen

- Booking kan kun bekræftes efter accept af eksempelvilkår.
- Kundesøgning kan give en tom liste uden fejl.
- Eksterne integrationer er markeret som mulige, ikke aktive.
- Simulerede handlinger giver en toast i stedet for netværkskald.

## Responsive regler

- 390 px: enkelt kolonne, mobilnavigation og kompakte bookingvalg.
- 768 px: to kolonner, reduceret sidebar.
- 1280–1440 px: fuldt editorial layout og dashboard med sidepanel.
