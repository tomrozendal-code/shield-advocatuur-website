# Shield Advocatuur — website

Statische website voor Shield Advocatuur, een onafhankelijk boutique advocatenkantoor in Amsterdam en 't Gooi.

## Talen
De site is volledig drietalig:

- **Nederlands** — hoofdmap (`/`)
- **Engels** — `/en/`
- **Spaans** — `/es/`

Een taalschakelaar (NL · EN · ES) staat in de topbalk van elke pagina. Per pagina zijn `hreflang`-tags en taal-specifieke canonical/Open Graph-URL's ingesteld voor SEO.

## Structuur
- `index.html` en de overige pagina's — 13 pagina's per taal (39 totaal)
- `styles.css` — alle styling (één bestand, gedeeld door alle talen)
- `assets/` — logo's

## Lokaal bekijken
Open `index.html` rechtstreeks in de browser, of serveer de map met een statische server.

## Functionaliteit
- Responsive ontwerp met mobiel hamburgermenu
- Contactformulier dat via `mailto:` de mailclient van de bezoeker opent
- Klikbare locatiekaarten (Google Maps) op de contactpagina
- Favicon, Open Graph- en Twitter-metadata

## Aandachtspunten vóór livegang
- De juridische pagina's (algemene voorwaarden, privacybeleid, cookiebeleid) bevatten een placeholder; de definitieve juridische teksten moeten nog in alle drie talen worden geplaatst.
- De EN/ES-vertalingen zijn van goede kwaliteit, maar een menselijke revisie wordt aangeraden vóór publicatie.
- Het contactformulier vereist een mailclient bij de bezoeker; voor serverloze verzending kan later een dienst als Formspree worden gekoppeld.
