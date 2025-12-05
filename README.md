# Pflanzenschutz-Aufzeichnung (Lite)

Eine **schlanke Version** der Pflanzenschutz-Web-App, optimiert für ältere und leistungsschwächere Geräte.

## 🚀 Was ist anders in der Lite-Version?

| Feature                    | Full-Version | Lite-Version |
| -------------------------- | ------------ | ------------ |
| Berechnungs-Modul          | ✅           | ✅           |
| Historie                   | ✅           | ✅           |
| Dokumentation              | ✅           | ✅           |
| GPS-Verwaltung             | ✅           | ✅           |
| Import/Merge               | ✅           | ✅           |
| Einstellungen              | ✅           | ✅           |
| Auswertung                 | ✅           | ✅           |
| **Zulassungs-Suche (BVL)** | ✅           | ❌           |
| **EPPO/BBCH-Lookup**       | ✅           | ❌           |
| **BVL-Sync**               | ✅           | ❌           |
| **Starfield-Animation**    | ❌           | ❌           |

### Performance-Vorteile

- **~6.000 Zeilen weniger Code** geladen
- **~47 MB weniger Daten** (keine EPPO/BBCH-Datenbanken)
- **Keine Hintergrund-Animationen** (kein Canvas-Rendering)
- **Schnellerer Start** auf älteren Geräten

## 💡 Wann sollte ich die Lite-Version nutzen?

- Ältere Tablets oder Smartphones
- Geräte mit wenig RAM (< 2 GB)
- Langsame Internetverbindungen
- Wenn du die BVL-Zulassungssuche nicht benötigst

## 🔧 Entwicklung

```bash
cd ps
npm install
npm run dev    # Startet auf Port 4322
```

## 📦 Build

```bash
npm run build
```

Der Build liegt unter `dist/` und kann auf GitHub Pages oder einem beliebigen Webserver deployed werden.

## 🔗 Full-Version

Die vollständige Version mit allen Features findest du unter:
https://github.com/Abbas-Hoseiny/pestalozzi

## Lizenz

MIT – Nutzung, Anpassung und Weitergabe sind ausdrücklich erlaubt.
