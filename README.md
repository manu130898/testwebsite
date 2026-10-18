# testwebsite

Eine einfache statische Website (HTML + CSS), die über GitHub Pages bereitgestellt wird.

## Dateien

- `index.html` – Inhalt der Seite
- `style.css` – Gestaltung (inkl. automatischem Dark Mode)
- `.nojekyll` – sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert

## Lokal ansehen

`index.html` einfach im Browser öffnen – oder einen kleinen lokalen Server starten:

```bash
python3 -m http.server 8000
```

Danach http://localhost:8000 aufrufen.

## Über GitHub Pages veröffentlichen

1. Im Repository auf **Settings → Pages** gehen.
2. Unter **Build and deployment** bei **Source** „Deploy from a branch“ wählen.
3. Als Branch `main` und als Ordner `/ (root)` auswählen und speichern.
4. Nach ein bis zwei Minuten ist die Seite erreichbar unter:
   https://manu130898.github.io/testwebsite/
