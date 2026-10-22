# Drone Academy 2.4 – Flight Lab

## Starten en publiceren
Pak de ZIP uit. Upload **de inhoud van de map** naar de hoofdmap van een GitHub-repository. Kies bij Settings → Pages: Deploy from a branch → main / root. Open daarna `index.html` via je GitHub Pages-adres. Theorie en oefenexamens staan in `academy.html`; de klassieke simulator in `classic.html`.

## Wat is nieuw
- AI-gecreëerde visuele trainingsassets: dronebeelden voor Mavic 2 Zoom, Mini 4 Pro en Neo; twee fotografisch vormgegeven achtergronden. Dit zijn **illustraties**, geen officiële DJI-productfoto's of werkelijk luchtruim.
- Volgcamera met drone midden in beeld, centrale navigatiepijl, 5 routepunten, live kaart en wisselende objecten.
- Herstart vernieuwt routepunten en obstakels.
- Toestelafhankelijke vluchtsituaties: A3 voor de legacy Mavic 2 Zoom zonder Cx-label; C0-configuratie voor Mini 4 Pro en Neo; mensenmenigte en luchthavenverbod gelden voor alle drie.
- Directe feedback met GOED/FOUT, eigen antwoord, juist antwoord en uitleg.
- Regels en toetsomgeving van de vorige versie zijn behouden.

## Bediening
W/S stijgen/dalen; A/D draaien; pijlen vliegen. Werkt ook via de schermknoppen (ingedrukt houden). Gebruik de knop Camera voor volg-/pilootstand. RTH is in dit onderwijsmodel een vereenvoudigde terugkeer, geen werkelijke automatisch navigerende failsafe. Kies eerst het toestel en de missie en geef de vluchtbeslissing. De simulator blokkeert een afgekeurde missie.

## Didactiek en veiligheidsgrenzen
Beelden en zones zijn fictief. De achtergrond is een AI-gecreëerde compositie; de besturing is een lichte 2,5D-oefensimulatie, **geen volwaardige natuurkundig correcte 3D-vluchtsimulator**. Gebruik de app niet om echte vluchttoestemming, bekwaamheid of examenresultaat vast te stellen. Controleer voor een echte vlucht de actuele officiële geozones, droneconfiguratie, exploitantregistratie, leeftijd, begeleiding en fabrikantinstructies. Bij de Mini 4 Pro kunnen accukeuze en C0-status relevant zijn. De Mavic 2 Zoom zonder Cx-label van 905 g valt in de Open categorie doorgaans onder A3. Wettelijke rechten hangen niet alleen van het gewicht af.

## Testpunten voor docent
1. Kies elke drone en lees gewicht/klasse.
2. Test landelijke route met een goed en een fout antwoord.
3. Test een verboden luchthavenmissie: opstijgen moet geblokkeerd blijven.
4. Kies Mavic in de industriecasus: afgekeurd; kies Mini/Neo: in de fictieve casus in beginsel toegestaan.
5. Houd pijltjestoetsen of schermknoppen ingedrukt en controleer routepijl/kaart.
6. Gebruik Nieuwe route om andere vijf punten te zien.
7. Open `academy.html` en test bij A1/A3 en A2 de rode/groene antwoordfeedback.

De syntax en ZIP-integriteit zijn gecontroleerd; test voor klassikaal gebruik in jullie actuele browser en op jullie apparaten.

## Versie 2.6 — foto-editie
- Teruggebouwd op de beeldrijke 2.4-simulator, niet op de schetsachtergronden van 2.5.
- Stadkeuze: Deventer, Zutphen, Doetinchem, Doesburg. De foto’s komen online van Wikimedia Commons, zie PHOTO-CREDITS.md.
- Offline blijft de 2.4-achtergrond beschikbaar. Echte stadsfoto’s zijn niet offline meegeleverd vanwege een beperking bij het binnenhalen van de mediabestanden.
- Route en kaart blijven fictief. De app toont nadrukkelijk geen werkelijke geozones boven een stadsfoto; controleer de officiële kaart vóór echte vluchten.
- Accu-leeg-fout verholpen: de oefenvlucht krijgt expliciet de status niet gehaald.


## Versie 2.7 – smartphone + laptop
- Responsive simulator: stads- en missiekeuze, dronekaarten, kaart en vluchtbesturing passen op telefoon.
- Drie mobiele snelkoppelingen: vlucht beoordelen, vliegscherm en besturen.
- Knoppen geschikt voor aanraken en vasthouden; twee stuurvlakken naast elkaar.
- Examens met grotere antwoordknoppen en leesbare feedback op smalle schermen.
- Landscape-ondersteuning. Voor prettige besturing bij voorkeur telefoon liggend gebruiken.
- Geen extra app nodig: open de GitHub Pages-site op mobiel. Installatie via browser als PWA waar ondersteund.
- Externe echte stadsfoto's vereisen internet; de lokale achtergrond werkt offline na het cachen van de app.


## Nieuwe 3D-proef
Open `world3d.html`. Zie `3D-README.md` voor bediening en beperkingen.
