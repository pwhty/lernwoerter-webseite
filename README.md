# Lernwörter Website

Statische Marketing-Webseite für die Lernwörter-App.

## Lokal testen

```bash
python3 -m http.server 4000
# → http://localhost:4000
```

## Veröffentlichen via GitHub Pages

1. Repository auf GitHub pushen.
2. **Settings → Pages → Source = `Deploy from a branch`**, Branch `main`,
   Folder `/website`.
3. Nach 1–2 Minuten erreichbar unter
   `https://<dein-account>.github.io/Lernwörter/`.
4. (Optional) Eigene Domain via `CNAME`-Datei und DNS.

## Anpassen

- Texte & Inhalte: `index.html`, `datenschutz.html`, `impressum.html`.
- Design: `styles.css` – Akzentfarbe `--accent` ändern für Re-Branding.
- Screenshots ergänzen: in `assets/` ablegen und in `index.html` einbinden.
