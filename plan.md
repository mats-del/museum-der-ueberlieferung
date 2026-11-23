# Museum der Überlieferung – Plan

## Ziel
Die bestehende Three.js-Codebasis von `museum-der-triebev2` wird zu einem interaktiven digitalen Geschichtsmuseum über Anne Franks Tagebuch und die Deportationsliste Westerbork–Auschwitz vom 3. September 1944 erweitert.

## Umsetzung
- Die vorhandene GLB- und Three.js-Basis bleibt als ruhige, begehbare Museumsatmosphäre erhalten.
- Eine zugängliche Ausstellungsebene mit vier Räumen ergänzt den 3D-Raum: Tagebuch, Deportationsliste, Vergleich und Spuren bis in die Gegenwart.
- Die Transportliste wird als echte Archivabbildung eingebunden und per Zoom-Dialog vergrößerbar gemacht; Hervorhebungen liegen nur als separate UI-Ebene über dem Bild.
- Historische Aussagen werden mit den vom Nutzer vorgegebenen Institutionen verlinkt. Nicht belegte Zwischenstationen der Listenüberlieferung werden ausdrücklich als offene Lücke bezeichnet.
- Die responsive Oberfläche ist keyboard- und touch-tauglich: Raum-Navigation, Zeitleiste, Quellenkarten, Vergleichsschalter und Dokument-Zoom funktionieren ohne 3D-Steuerung.

## Gestaltung
- **Mögliche Richtungen:** Archivale Dunkelkammer (0,07), typografischer Lesesaal (0,05), nüchterne Gedenkvitrine (0,08).
- **Gewählt: Archivale Dunkelkammer.** Dunkles Graphit, Papierweiß und ein gedämpftes Rot schaffen Konzentration statt Pathos. Die Räume arbeiten mit asymmetrischen Text- und Objektflächen, dünnen Archivlinien und Vitrinenrahmen.
- **Interaktion:** Jede Bewegung soll Erkenntnis freilegen: ein Raumwechsel öffnet eine Perspektive, ein Klick auf ein Objekt erklärt seine Quellenlage, Zoom trennt Originalbild und redaktionelle Hervorhebung.
- **Typografie:** `Georgia` für historische Überschriften und `Inter`/System Sans für Navigation und Quellenapparat.
- **Marke:** Eine rote Archivklammer `//` als wiederkehrendes Zeichen für die Verbindung zweier Dokumente.

## Projektstruktur
- `index.html`: statische Ausstellung, UI-Logik und Three.js-Raum.
- `freud-reflektierter-engel.glb`: bestehendes 3D-Objekt aus dem Ausgangsrepository, als diskrete Museumsplastik wiederverwendet.
- `assets/lijst03094407.jpg`: echte Abbildung der Transportliste aus der Forschungsdatenbank des Anne Frank House.
- `manus-routes.json`: deklarierte Seite `/`.
- `TODO.md`: nachverfolgbare Umsetzungskriterien.
