# Museum der Überlieferung

Dieses Repository erweitert das ursprüngliche begehbare Three.js-Museum um eine historische Quellenkammer zu Anne Franks Tagebuch und der Deportationsliste Westerbork–Auschwitz vom 3. September 1944.

## Nutzung

Die Seite ist eine statische Website. `index.html` enthält die ursprüngliche begehbare 3D-Szene sowie den neuen historischen Ausstellungsdialog. Die Schaltfläche **Historische Ausstellung** öffnet vier Räume: Tagebuch, Transportliste, Vergleich und Gegenwart. Die Originalabbildung der Transportliste liegt unter `assets/lijst03094407.jpg` und wird unverändert angezeigt; der Zoom öffnet eine separate Ansicht.

Zusätzlich stehen drei prozedural in Three.js erzeugte, ausdrücklich didaktische 3D-Objekte in der Szene: ein Tagebuchmodell, eine Archivbox und eine Dokumentvitrine. Sie sind keine Reproduktionen historischer Originale.

Zum lokalen Testen genügt beispielsweise:

```bash
python3 -m http.server 4173
```

Danach `http://localhost:4173/` öffnen. Die externe Three.js-Bibliothek wird über CDN geladen.

## Quellen

Die Ausstellung verlinkt vorrangig auf das Anne Frank House Research Portal, das Nationaal Archief und UNESCO. Die nicht vollständig belegte Überlieferungsgeschichte des konkreten Transportlistenblatts wird im Interface ausdrücklich als offen markiert.
