# einführung in scss und gulp+ browsersync

# Anfang

## Schritt 1
1. Neuen Ordner erstellen
2. Terminal öffnen und in den Ordner "switchen" (`cd`)
3. Gib `npm init` ein und drücke enter, enter, enter etc
4. Gib `npm install gulp --save-dev` ein und drücke enter um gulp zu installieren
5. Wiederhole den vorgang nur diesesmal für `gulp-sass` und `browser-sync`

## Tasks

Wir haben verschiedene "tasks".

- `sass`: Kompeliert `scss/style.scss` --> `dist/css/style.css`
- `browserSync`: Browser und netzwerk übergreifender sync
- `watch` : Überwacht alle Dateien und bei Änderungen werden auch `sass` und `browserSync` gelaufen