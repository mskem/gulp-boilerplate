# einführung in scss und gulp+ browsersync

# Intro
1. Neuen Ordner erstellen
2. Terminal öffnen und in den Ordner "switchen" (`cd`)
3. Gib `npm init` ein und drücke enter, enter, enter etc
4. Installiere `gulp`, `gulp-sass`, `gulp-autoprefixer` und `browser-sync` mit `npm install --save-dev gulp-autoprefixer gulp-sass gulp browser-sync`

## Tasks
Wir haben verschiedene "tasks".
- `sass`: Kompeliert `scss/style.scss` --> `dist/css/style.css`
- `browserSync`: Browser und netzwerk übergreifender sync
- `watch` : Überwacht alle Dateien und bei Änderungen werden auch `sass` und `browserSync` gelaufen
