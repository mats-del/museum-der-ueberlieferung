# Museum der Überlieferung

Dieses Repository enthält ein eigenständiges begehbares Three.js-Museum zu Anne Franks Tagebuch und der Deportationsliste Westerbork–Auschwitz vom 3. September 1944. Das getrennte Repository `museum-der-triebev2` bleibt das Museum der Triebe/Liebe; seine inhaltlichen Skulpturen und Texte werden hier nicht verwendet.

## Nutzung

Die Seite ist eine statische Website. `index.html` enthält eine einzige offene, begehbare Museumshalle ohne externe Inhalts-Buttons. Die schematische Wegkarte mit dem Tagebuchweg steht als zentrales Exponat in der Mitte; Tagebuch und Transportlistenobjekt flankieren sie an den Seiten. Eine geprüfte Wandzeitleiste erläutert die Überlieferung des Tagebuchs; die Originalabbildung der Transportliste liegt unter `assets/lijst03094407.jpg` und bleibt unverändert.

Die Szene verwendet keine Freud-/Triebe-Skulpturen und kein altes GLB-Modell. Stattdessen stehen drei hochwertige GLB-Modelle in der Szene: ein Tagebuchmodell, eine schematische Reliefkarte und eine Transportlisten-Vitrine. Sie sind keine Reproduktionen historischer Originale. Die Wandtafeln machen Datum, Quellenstatus und offene Präzisierungen sichtbar.

Zum lokalen Testen genügt beispielsweise:

```bash
python3 -m http.server 4173
```

Danach `http://localhost:4173/` öffnen. Die externe Three.js-Bibliothek wird über CDN geladen.

## Quellen

Die Ausstellung verlinkt vorrangig auf das Anne Frank House Research Portal, das Nationaal Archief und UNESCO. Die nicht vollständig belegte Überlieferungsgeschichte des konkreten Transportlistenblatts wird im Interface ausdrücklich als offen markiert.
