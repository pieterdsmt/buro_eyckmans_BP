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

## Structuur bij verhuur en constructie

Verhuur en constructie gebruiken dezelfde ruimteknoppen en optionele groepen.
De opnamepagina vraagt geen verslagtype. Kies verhuur of constructie uitsluitend
in de pc-app die het verslag genereert. Eerder opgeslagen typekeuzes veranderen
de bestaande tekst niet; oude groeperingen worden nog steeds hersteld.
Standaard staat **Toevoegen onder** op **Geen groep**: geschikt voor bijvoorbeeld
een appartement, zonder telkens Gelijkvloers te vermelden. Alleen aangeklikte
ruimtes worden toegevoegd.

Kies een verdieping of maak een eigen groep als u ruimtes wilt bundelen. Ook
**Openbaar domein** is een groep, met snelknoppen voor voetpad, boordsteen, goot
en rijweg en vrije invoer. De gewone ruimteknoppen blijven beschikbaar.

Het structuuroverzicht toont ruimtes per groep. Met de groepkeuze bij een ruimte
kunt u de indeling achteraf wijzigen; de beschrijving blijft behouden.
Groepen kiezen of aanmaken voegt geen lege rubrieken aan de tekst toe.

De tekst gebruikt `--- RUIMTE [Groep] ---`. Een lege groep (`[]`) betekent
expliciet geen bovenliggende groep, ook na een oudere verdiepingsmarker.
De pc-app vanaf versie 9 ondersteunt deze expliciete lege groep, gemengde
groepering, bijbehorende Word-koppen en fotomappen. Oudere versies zijn hier
niet volledig op afgestemd.

Dit is een aanpassing aan de opnamepagina, niet aan de Word-templates of de
documentgenerator. Controleer de verwerking van nieuwe hoofdrubrieken in de
desktop-app voordat u deze opnameversie in productie neemt.
