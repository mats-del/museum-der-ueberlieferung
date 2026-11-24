# Museum der Überlieferung

Dieses Repository enthält ein eigenständiges begehbares Three.js-Museum zu Anne Franks Tagebuch und der Deportationsliste Westerbork–Auschwitz vom 3. September 1944. Das getrennte Repository `museum-der-triebev2` bleibt das Museum der Triebe/Liebe; seine inhaltlichen Skulpturen und Texte werden hier nicht verwendet.

## Nutzung

Die Seite ist eine statische Website. `index.html` enthält eine neue Archivarchitektur mit drei begehbaren Räumen sowie die Quellenkammer. Die Schaltfläche **Quellenkammer** öffnet vier inhaltliche Ansichten: Tagebuch, Transportliste, Vergleich und Gegenwart. Die Originalabbildung der Transportliste liegt unter `assets/lijst03094407.jpg` und wird unverändert angezeigt; der Zoom öffnet eine separate Ansicht.

Die Szene verwendet keine Freud-/Triebe-Skulpturen und kein altes GLB-Modell. Stattdessen stehen drei prozedural in Three.js erzeugte, ausdrücklich didaktische 3D-Objekte in der Szene: ein Tagebuchmodell, eine Archivbox und eine Dokumentvitrine. Sie sind keine Reproduktionen historischer Originale.

Zum lokalen Testen genügt beispielsweise:

```bash
python3 -m http.server 4173
```

Danach `http://localhost:4173/` öffnen. Die externe Three.js-Bibliothek wird über CDN geladen.

## Quellen

Die Ausstellung verlinkt vorrangig auf das Anne Frank House Research Portal, das Nationaal Archief und UNESCO. Die nicht vollständig belegte Überlieferungsgeschichte des konkreten Transportlistenblatts wird im Interface ausdrücklich als offen markiert.
