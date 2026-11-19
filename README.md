# 🎲 Minispiele

Klassische Spiele für zwei – jeder spielt auf seinem eigenen Gerät, verbunden über einen Raum-Code.

**Spielen:** https://paulus1899.github.io/minispiele/

## Spiele
Tic-Tac-Toe · Ultimate Tic-Tac-Toe · Vier gewinnt · Fünf gewinnt · Stadt-Land-Fluss · Schiffe versenken · Code knacken (Mastermind) · Zahlenraten · Memory

## So funktioniert's
1. Namen eingeben und **Raum erstellen** – du bekommst einen 4-stelligen Code.
2. Code oder Einladungslink an deinen Mitspieler schicken, er tippt auf **Beitreten**.
3. Spiel auswählen und loslegen.

## Technik
- Alles steckt in einer einzigen Datei: `index.html`
- Online-Verbindung über **Firebase Realtime Database** (Spark-Tarif, kostenlos); jedes Gerät meldet sich im Hintergrund anonym an
- Sicherheitsregeln der Datenbank: `database.rules.json` (in der Firebase-Konsole unter Realtime Database → Regeln einfügen)
- Räume ohne Aktivität werden nach 24 Stunden automatisch aufgeräumt
