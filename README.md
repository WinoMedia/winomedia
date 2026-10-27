# winomedia – Light & Elegant

Astro One-Page-Website, inspiriert von der Data-Flow-Markenidentität.

## Lokal starten

1. Node.js 20+ installieren.
2. `npm install`
3. `npm run dev`
4. `http://localhost:4321` öffnen.

## Auf GitHub Pages veröffentlichen

1. Neues öffentliches GitHub-Repository erstellen, z.B. `winomedia-website`.
2. Dateien in das Repository hochladen und auf den Branch `main` pushen.
3. In `astro.config.mjs` `USERNAME` durch deinen GitHub-Benutzernamen und `REPOSITORY` durch den Repository-Namen ersetzen. Bei einer eigenen Domain ist eine andere `site`/`base`-Konfiguration nötig.
4. GitHub → Settings → Pages → Build and deployment → Source: **GitHub Actions**.
5. Die enthaltene Workflow-Datei `.github/workflows/deploy.yml` veröffentlicht die Website bei jedem Push auf `main`.

## Vor der Veröffentlichung

- `DEINE-EMAIL@BEISPIEL.CH` im Kontaktbutton ersetzen.
- Texte, Leistungen und persönliche Vorstellung prüfen und ergänzen.
- Rechtlich erforderliches Impressum und Datenschutzhinweise für die Schweiz erstellen.
- Original-Logo technisch als transparente, freigestellte Vektordatei nachzeichnen und einbauen. Das Referenzbild `public/assets/logo-reference.png` ist **nur** eine Bildvorlage mit Hintergrund, keine nutzbare transparente SVG-Datei.
- Fonts werden aktuell über Google Fonts geladen. Für mehr Datenschutz Fonts später lokal hosten und Datenschutzerklärung entsprechend anpassen.

## Gestaltung

- Offwhite: `#F8F7F4`
- Schwarz: `#171717`
- Champagnergold: `#C9A477`
- Schrift: Montserrat

Die Data-Flow-Wellen auf der Seite sind eigenständige SVG-Dekorationen und **keine exakte Vektorisierung des final ausgewählten WM-Monogramms**.
