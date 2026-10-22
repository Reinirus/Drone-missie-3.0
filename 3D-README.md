# Drone Academy – echte 3D-proef

Deze proef staat via `world3d.html` naast de bestaande versie 2.7, zodat theorie, examens, scores en foto-simulator behouden blijven.

## Wat werkt
- Vrije wereldruimte met perspectiefcamera (WebGL/Three.js), woningen, daken, tuinen, bomen, bos, rivier, brug, verkeer, wandelende figuren, industrie en een vliegtuig in een luchthaven-oefenscenario.
- Drie gestileerde 3D-dronevarianten en bijbehorende toestelregels; geen officiële CAD-modellen van DJI.
- Besturing met toetsenbord en touch, volgcamera, FPV en vrij draaien door slepen over het vliegscherm; vijf 3D-ringen en herstart met nieuwe routeposities.
- Botsing met 3D-objecten, personen, verkeer en grond beëindigt vlucht. Laag overvliegen van mensen is in werkelijkheid risicovol en niet als oefendoel bedoeld.
- Fictieve regelbeoordeling. De luchthaven-oefencasus blokkeert opstijgen; alle overige fysieke objecten zijn simulatieobjecten, geen actuele geozones.

## Belangrijkste beperking
Voor de nieuwe 3D-scène wordt Three.js v0.180 via jsDelivr geladen; **internet is vereist om world3d.html te starten**. De bestaande 2.7-app blijft beschikbaar en de reguliere 2.7-cachebestanden zijn behouden. Voor betrouwbare offline inzet moet de school deze bibliotheek later als lokaal beheerd bestand toevoegen, na licentie-/IT-controle.

Dit is een functioneel geometrisch 3D-prototype, geen fotorealistische replica van Deventer, geen natuurkundig exacte DJI-simulator en geen officiële vliegopleiding. Een geloofwaardige volgende stap is een Blender/glTF-assetpipeline met gelicentieerde modellen, echte geodata waar toegestaan, performance-tests op schoollaptops en inhoudelijke validatie door een erkende droneopleider.

## Publiceren
Pak de ZIP uit, upload de **inhoud** van de projectmap naar de root van je GitHub-repository, activeer GitHub Pages. Open `/world3d.html` en test eerst op een laptop met internet en hardwareversnelling. Ga via de navigatie terug naar versie 2.7 of de theorielessen.
