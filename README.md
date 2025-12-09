# Akvarie Projekt - Optimeringer

## Billedoptimering

### GIF-filer optimeret

- Alle fisk-animationer (orange, blå, pufferfisk, damsel, søhest)
- Nemo maskot animation
- Reduceret filstørrelse uden tab af kvalitet

### PNG til SVG konvertering

- Muslingeskal (`mus.svg`, `mus-aben.svg`)
- Tang (`tang.svg`, `tang-aben.svg`)
- Skrald (`skrald.svg`)
- Dykker (`scubi-dreng.svg`)
- Vægge/forhindringer (`wall.svg`, `wall2.svg`)

## HTML/CSS Optimeringer

### Semantisk struktur (index.html)

- Tilføjet skjult `<h1>` for SEO og tilgængelighed
- `<aside>` til intro-skærm med Nemo
- `<header>` med `<nav>` til spil-menu
- `<main>` til hovedindhold
- `<section>` til at organisere fisk og baggrundselementer
- `<figure>` til alle fisk-billeder

### Semantisk struktur (game-2.html)

- `<header>` med `<nav>` til navigation
- `<main>` til hovedindhold
- `<section>` til spilområde
- `<aside>` til info-bokse
- `<figure>` og `<figcaption>` til billeder med beskrivelser
- Ændret `<h1>` til `<h2>` i game-title for korrekt heading-hierarki

### CSS forbedringer

- Fjernet inline styling fra game-2.html
- Tilføjet `display: none` i CSS i stedet
- Opdateret kommentarer i koden
- CSS variable overvejet til fremtidig refaktorering

## UX Forbedringer

- Spil-knap flyttet til bunden/midten for bedre brugervenlighed
- Større tilbage-knap med bedre synlighed
- Tydeligt markeret at spil 3 ikke er optimeret

## Navnekonventioner

- Først ændret til camelCase (3. dec)
- Senere opdateret til kebab-case (8. dec) for bedre læsbarhed og fordi murat nævnte det var den koreekte måde
- Alle billedfiler bruger nu kebab-case (`nemo-fish.png`, `blaa-fisk.gif`)
- Konsistent navngivning gennem hele projektet
- Opdateret alle referencer i HTML, CSS og JavaScript

## JavaScript Optimeringer

- Givet fisk mere sigende ID'er og class navne
- Opdateret variabelnavne til at matche nye billednavne
- Rettet fejl ved pufferfisk 3
- Gjort fisk mindre efter nye GIF-filer

## Oprydning

- Fjernet gamle/ubrugte billedfiler
- Slettet gamle PNG'er efter SVG konvertering
- Organiseret projekt-struktur
- Tilføjet Storcenter Nord logo og fonts
- Opdateret titel til at matche Storcenter Nord
- Små rettelser i vector grafik samt favicon
