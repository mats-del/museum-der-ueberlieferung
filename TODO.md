# Umsetzungskriterien

## Erledigt

- Die ursprüngliche begehbare Three.js-Museumsszene aus `museum-der-triebev2` ist die Basis des neuen Repositories.
- Die historische Quellenkammer ist als öffnbarer, responsiver Dialog in die 3D-Seite integriert.
- Vier Räume sind vorhanden: Tagebuch, Transportliste, Vergleich und Gegenwart.
- Die echte Transportlistenabbildung vom 3. September 1944 wird lokal geladen, unverändert angezeigt und separat vergrößert.
- Die Archivsignatur, die Nummern 306–309 und die offene Überlieferungslücke werden erklärt.
- Tagebuchfassungen, Auffinden, Übergabe, Veröffentlichung, wissenschaftliche Edition und UNESCO-Registrierung werden in einer kompakten Zeitleiste erläutert.
- Drei eigene prozedurale Three.js-Modelle ergänzen die Szene: Tagebuch, Archivbox und Dokumentvitrine.
- Die Modelle sind ausdrücklich didaktische Objektmodelle und keine künstlich erzeugten historischen Originaldokumente.
- Direkte Links zu Anne Frank House, Nationaal Archief und UNESCO sind enthalten.

## Technische Hinweise

Die Seite bleibt eine statische Einzeldatei mit CDN-Abhängigkeiten für Three.js. Die bestehende Touch-/Joystick- und Tastatursteuerung der 3D-Szene bleibt aktiv; die Quellenkammer liegt als eigenständige UI-Schicht darüber.
