ROBoter & AUTOMATISIERTE ANLAGEN – DIGITALWERKSTATT V3

Was neu ist
-----------
- Smartphone-first Comicdesign passend zum Plakat
- 8 interaktive Komponenten
- verbesserte Roboter-Ablaufsimulation
- Signalweg-Labor
- virtuelles Multimeter mit Störungsfällen
- 6 Diagnosefälle
- Spiel „Störungsjäger“ (60 Sekunden)
- lokale Top-5-Highscoreliste per localStorage
- lokaler Lernfortschritt
- 8-Fragen-Wissenstest mit gespeichertem Bestwert
- Mini-Lexikon
- als PWA installierbar / offline nutzbar

WICHTIG ZUM HIGHSCORE
---------------------
Die Highscores werden im Browser des jeweiligen Smartphones/Tablets gespeichert.
Sie sind also dauerhaft auf diesem Gerät verfügbar, aber NICHT automatisch
klassenweit zwischen verschiedenen Smartphones synchronisiert.

Wenn später eine gemeinsame Klassen-Bestenliste gewünscht ist, braucht die Seite
eine kleine Online-Datenbank / einen Backend-Dienst.

GITHUB PAGES – UPDATE
---------------------
Im Repository RobUndAutAnlagen die bisherigen Dateien ersetzen bzw. ergänzen:
  index.html
  manifest.webmanifest
  sw.js
  assets/anlage-comic.webp
  assets/icon-192.png
  assets/icon-512.png

Die bisherigen QR-Codes bleiben gültig:
  #erkunden
  #simulation
  #fehlersuche
  #quiz

Neue direkte Ziele:
  #signalweg
  #messen
  #spiel
  #begriffe

Hinweis:
Nach einem Update kann ein bereits installierter Service Worker kurz die alte
Version aus dem Cache anzeigen. Seite einmal neu laden; bei Bedarf Browser-Cache
für die Seite leeren.
