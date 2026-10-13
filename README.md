# Block Master

Juwelen-Block-Puzzle als installierbare Web-App (Deutsch / Thai).

- `index.html` – das ganze Spiel (eine Datei, keine Build-Schritte)
- `sw.js` – Offline-Betrieb nach dem ersten Öffnen
- `manifest.webmanifest`, `icons/` – Installation auf dem Startbildschirm
- Rangliste: Supabase-Projekt `block-master` (Funktionen `submit_score`, `get_leaderboard`, `get_my_rank`).
  Kein Login: jedes Handy bekommt eine zufällige Geräte-ID im Browser-Speicher und wählt einen Spielernamen.

## Deploy

Auf vercel.com „Add New → Project“, dieses Repo wählen, Framework „Other“, ohne Build-Befehl – fertig.

## Hinweis Sounds

Die Ansagen (Monster Kill, Ultra Kill) stammen ursprünglich aus Unreal Tournament.
Vor einer öffentlichen Veröffentlichung durch eigene oder lizenzfreie Sounds ersetzen.
