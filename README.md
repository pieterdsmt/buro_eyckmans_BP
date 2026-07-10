# PB Opname – GitHub Pages

Deze map is klaar om als offline webapp via GitHub Pages te publiceren.

## Publiceren op GitHub

1. Maak op GitHub een nieuwe repository, bijvoorbeeld `pb-opname`.
2. Upload **de bestanden uit deze map** naar de hoofdmap van de repository.
3. Open in GitHub: **Settings → Pages**.
4. Kies bij *Build and deployment*: **Deploy from a branch**.
5. Selecteer branch **main** en map **/(root)** en klik op **Save**.
6. Wacht enkele minuten en open de GitHub Pages-link die GitHub toont.

## Installeren en offline gebruiken op iPad

1. Open de GitHub Pages-link in **Safari** terwijl de iPad online is.
2. Wacht tot bovenaan **“Online — offline klaar”** verschijnt.
3. Tik op **Delen → Zet op beginscherm**.
4. Open de app één keer via het beginscherm terwijl er internet is.
5. Test daarna in vliegtuigmodus. De tekst, structuurknoppen en lokale opslag blijven werken.

Dicteren via het iPad-toetsenbord kan afhankelijk zijn van de iPad-, iPadOS- en taalinstellingen. Handmatig typen werkt altijd offline.

## Bestanden

- `index.html`: de toepassing
- `manifest.webmanifest`: instellingen voor de webapp
- `sw.js`: offlinecache
- `icon-180.png`, `icon-192.png`, `icon-512.png`: app-iconen

## E-mailadres

De knop **E-mail naar kantoor** is ingesteld op:

`pieter@buro-eyckmans.be`

Dit kan in `index.html` worden aangepast bij de regel `const MAIL = ...`.

## Back-up

De toepassing bewaart automatisch één lopend dossier op de iPad. Gebruik regelmatig **Bewaar als tekstbestand** om een afzonderlijke kopie in de Bestanden-app te bewaren.
