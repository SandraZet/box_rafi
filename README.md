# 🎯 Wortschuss – Englisch lernen macht Spaß!

Ein webbasiertes Lernspiel für Englisch-Vokabeln.  
Entwickelt von [Kind & Elternteil] mit Unterstützung von GitHub Copilot.

## 🎮 So wird gespielt

1. Ein **deutsches Wort** erscheint oben auf dem Bildschirm
2. Mehrere Boxen mit **englischen Übersetzungen** bewegen sich auf dem Spielfeld
3. Ziel mit der Maus auf die **richtige Box** und klicke, um den Ball abzuschießen!
4. **Richtige Box** = 10 Punkte (mehr im höheren Level) ✅
5. **Falsche Box** = Herz verloren ❌
6. Bei 0 Herzen ist das Spiel vorbei

## ▶️ Spiel starten

Einfach die Datei `index.html` im Browser öffnen – fertig!  
Kein Internet, keine Installation nötig.

**Online spielen:** https://[dein-benutzername].github.io/box_rafi/

## ✏️ Neue Wörter hinzufügen

In der Datei `index.html` die Liste `vocabulary` suchen und ergänzen:

```js
const vocabulary = [
  { de: "Hund",   en: "dog" },
  { de: "Katze",  en: "cat" },
  // → Hier neue Wörter einfügen:
  { de: "Schule", en: "school" },
];
```

## 🚀 Auf GitHub veröffentlichen

1. Ein GitHub-Konto erstellen (falls noch nicht vorhanden)
2. Neues Repository erstellen: `box_rafi`
3. Diese Dateien hochladen (oder per Git pushen)
4. Unter **Settings → Pages → Source: main branch** aktivieren
5. Fertig! Der Lehrer kann das Spiel über den Link spielen

## 📜 Lizenz

Frei nutzbar für Bildungszwecke.
