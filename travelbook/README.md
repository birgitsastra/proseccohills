# 🥂 Prosecco Mädelstrip – Travelbook

Interaktives Reise-Travelbook als GitHub Pages Website.

## Deployment auf GitHub Pages

1. Diesen Ordner als neues GitHub Repository anlegen
2. Repository auf GitHub pushen:
   ```bash
   git init
   git add .
   git commit -m "Initial travelbook"
   git branch -M main
   git remote add origin https://github.com/DEIN-USERNAME/prosecco-travelbook.git
   git push -u origin main
   ```
3. Im Repository → **Settings → Pages → Source: main / root** aktivieren
4. Nach ~1 Minute ist das Travelbook unter `https://DEIN-USERNAME.github.io/prosecco-travelbook` erreichbar

## Struktur

```
/
├── index.html        ← Das Travelbook
├── img/              ← Platzhalter (Bilder laden von Unsplash)
│   └── .gitkeep
└── README.md
```

## Fotos

Die Fotos werden direkt von Unsplash geladen (kostenlos, keine API-Key nötig).
Für eigene Fotos: Bilder in `/img/` ablegen und die `src`-Attribute in `index.html` anpassen.
