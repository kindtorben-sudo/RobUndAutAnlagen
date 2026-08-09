ROBOTER & AUTOMATISIERTE ANLAGEN – DIGITALWERKSTATT V4

NEU
- Roboteroids – Störungsjagd
- aktive Asteroids-ähnliche Steuerung
- Touchsteuerung fürs Smartphone
- 12 wechselnde elektrotechnische Missionen
- Leben, Level, Combos, Werkzeug-Boni und Zeitdruck
- gemeinsame Server-Highscoreliste (Top 15)

SUPABASE – NOCH 2 SCHRITTE
1. Anonymous Sign-Ins einschalten:
   Supabase Dashboard -> Authentication -> Einstellungen/Providers
   -> „Allow anonymous sign-ins“ aktivieren.

2. SUPABASE_SETUP.sql ausführen:
   SQL Editor -> New query -> Datei komplett einfügen -> Run.

Danach V4 in GitHub hochladen/ersetzen.

Hauptseite:
https://kindtorben-sudo.github.io/RobUndAutAnlagen/

Roboteroids:
https://kindtorben-sudo.github.io/RobUndAutAnlagen/roboteroids.html

DATENSCHUTZ
Im Spiel bewusst nur Vorname/Kürzel verwenden.
Gespeichert werden Nickname/Kürzel, Punktzahl, Level, Spieldauer und eine anonyme technische Supabase-Benutzer-ID.

SICHERHEIT
Der Publishable Key ist für Browser-Anwendungen vorgesehen. Kein Secret- oder service_role-Key ist eingebaut.
Direkter Schreibzugriff auf die Tabelle ist entzogen. Speichern erfolgt nur über eine freigegebene Datenbankfunktion mit Plausibilitätsprüfung und kurzer Rate-Limit-Sperre.

HINWEIS
Ein rein browserbasiertes Spiel ist nicht vollständig manipulationssicher. Die Serverprüfungen verhindern offensichtliche Fehlwerte, ersetzen aber keine serverseitige Spielsimulation.
