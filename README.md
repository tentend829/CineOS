# DanTe-OS

## Roadmap

### Bugs (alle gefixt)
1. ~~`handleSend()` fehlt – Ciri AI kann keine Nachrichten senden~~ ✅
2. ~~`toggleFaq()` fehlt – FAQ-Button im Settings tot~~ ✅
3. ~~PS5 Emu: `CDN_COVER`/`CDN_HTML` undefiniert~~ ✅
4. ~~FPS-Optimierung schaltet nicht zurück~~ ✅
5. ~~`Monday.png`–`Sunday.png` existieren, werden aber nicht genutzt~~ ✅

### Neue Apps (alle umgesetzt)
6. ~~**Pomodoro-Timer** – Produktivitäts-Timer mit Countdown + Notification~~ ✅
7. ~~**QR-Code-Generator** – Text/URL → QR (via API oder Canvas)~~ ✅
8. ~~**Notizblock** – Editor mit localStorage-Speicherung~~ ✅
9. ~~**Paint/Draw** – Zeichen-App mit Canvas, Farbauswahl, Pinselgröße~~ ✅
10. ~~**Snake, Tetris, TicTacToe, Memory** – Klassische Spiele als Canvas~~ ✅
11. ~~**PDF-Viewer** – PDF.js / Google Docs Viewer einbinden~~ ✅
12. ~~**Countdown-Timer** – Für Events mit Hintergrund~~ ✅
13. ~~**Wetter-App** – Open-Meteo (kostenlos, kein Key), Live-Daten im Sidebar~~ ✅
14. ~~**Taschenrechner** – Wissenschaftlicher Rechner~~ ✅
15. ~~**Kalender** – Monatsansicht, Termine per localStorage~~ ✅
16. ~~**Notizen (Sticky Notes)** – Kleine Notizen auf dem Desktop~~ ✅
17. ~~**Terminal/Console** – JavaScript-Repl~~ ✅
18. ~~**Datei-Manager** – Browse durch lokale Projekt-Ressourcen~~ ✅
19. ~~**Audio-Recorder** – Mikrofon-Aufnahme via Web Audio API~~ ✅
20. ~~**Stopwatch** – Stoppuhr mit Rundenzeiten~~ ✅

### System-Features (alle umgesetzt)
21. ~~**Wallpaper-Zufallsmodus** – Alle N Minuten wechseln~~ ✅
22. ~~**Farb-Themes** – Blau, Grün, Lila, Orange (CSS-Variablen)~~ ✅
23. ~~**System-Sounds** – Boot, Fenster öffnen/schließen, Notification (Web Audio API)~~ ✅
24. ~~**Taskbar-Uhr** – Live-Uhr rechts unten~~ ✅
25. ~~**Minimize-Animation** – Fenster fliegt in die Taskbar~~ ✅
26. ~~**Screensaver** – After X Minuten Inaktivität~~ ✅
27. ~~**Mehrere Desktops** – 3 virtuelle Desktops zum Switchen~~ ✅
28. ~~**Lade-Spinner pro App** – Eigene Lade-Animation während iframe lädt~~ ✅
29. ~~**Lesezeichen im Browser** – URL speichern, Ordner anlegen~~ ✅
30. ~~**Error-Seite für Apps** – Wenn iframe fehlschlägt: anständige Meldung + Retry~~ ✅
31. ~~**App-Kategorien im Drawer** – Gaming, Musik, Tools, etc.~~ ✅
32. ~~**Suchverlauf im Startmenü** – Letzte 5 Suchbegriffe merken~~ ✅

### Erweiterungen bestehender Features (teilweise umgesetzt)
33. ~~**Ciri AI: Nachrichten senden** – `handleSend()` implementieren (Gemini API)~~ ✅
34. ~~**Ciri AI: Sprachmodus** – Mikrofon-Input → Speech-to-Text~~ ✅
35. ~~**Media Player: Equalizer**~~ ❌
36. ~~**Media Player: Playlist**~~ ❌
37. ~~**Media Player: Volume-Slider**~~ ❌
38. ~~**Wallpaper-Engine: Video-Upload** – Drag & Drop → neues Wallpaper~~ ✅
39. ~~**Wallpaper-Menü: Suche** – Nach Namen filtern~~ ✅
40. ~~**PS5 Emu: Favoriten**~~ ❌
41. ~~**Spotify: eigener Player**~~ ❌
42. ~~**Discord: eingebauter Chat**~~ ❌

### Performance & Code-Qualität (teilweise umgesetzt)
43. `var` → `let`/`const` im ganzen Projekt ❌
44. `onclick` in HTML → `addEventListener` im JS ❌
45. `applyCloak()`-Intervall durch Event ersetzen ❌
46. `drag-proxy`-CSS-Variablen statt Hardcoded-Werte ❌
47. try/catch für Cross-Origin iframe-Zugriffe (Media Player) ❌
48. `window.*` Globals reduzieren ❌

### Vercel / Deployment (alle umgesetzt)
49. ~~**`.vercelignore`** – Große Videos aus Deployment ausschließen~~ ✅
50. ~~**Custom 404-Seite** – Falls Route nicht gefunden~~ ✅
51. ~~**`vercel.json` Headers** – Cache-Control für Videos/Assets~~ ✅
52. ~~**GitHub Actions** – Auto-Deploy bei Push~~ ✅
