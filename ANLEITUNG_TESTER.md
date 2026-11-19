# Fahrtenbuch Pro – Anleitung für Tester (Beta 1)

Danke, dass du mittestest. Diese Version ist eine **Testversion**. Sie erkennt Fahrten zuverlässig genug für den Alltag, aber es kann noch Fehler geben. Führe dein offizielles Fahrtenbuch während des Tests deshalb zusätzlich wie bisher weiter.

**Getestet ab Android 14.** Ältere Geräte (Android 13) können funktionieren, sind aber nicht geprüft.

## 1. Installieren

1. Auf dem Handy die Release-Seite öffnen: `https://github.com/Liftkind/fahrtenbuch-pro-releases/releases`
2. Beim neuesten Eintrag unter „Assets“ die Datei `fahrtenbuch-pro-<version>.apk` antippen und herunterladen.
3. Die Datei öffnen. Android fragt, ob der Browser Apps installieren darf: **Einstellungen** → „Aus dieser Quelle zulassen“ einschalten → zurück → **Installieren**.
4. Google Play Protect warnt eventuell, weil die App nicht aus dem Play Store kommt. „Trotzdem installieren“ wählen.

Spätere Updates meldet die App selbst (siehe Abschnitt 6). Du musst die Seite nicht beobachten.

## 2. Einrichtungsassistent

Beim ersten Start führt dich ein Assistent durch die Einrichtung:

- **Fahrzeug** mit Kennzeichen und aktuellem Kilometerstand vom Tacho
- **Fahrer**, **Adressen** (Wohnung, Arbeit, ggf. Familienwohnsitz)
- **Beacon**: Der kleine Sender im Auto (iBeacon). Lege ihn ins Auto, schalte ihn ein und lass die App danach suchen. Ohne Beacon erkennt die App keine Fahrten automatisch; du kannst Fahrten dann nur von Hand eintragen.
- **Berechtigungen** (Abschnitt 3)
- **Sicherung**: Wähle hier einen **Sicherungsordner** (Abschnitt 5). Das ist wichtig.

## 3. Berechtigungen

Die App fragt nacheinander nach diesen Berechtigungen. Bitte alle erlauben, sonst fehlen Fahrten:

| Berechtigung | Auswahl | Wofür |
|---|---|---|
| Standort | „Immer zulassen“, „Genauer Standort“ an | Strecke und Kilometer messen, auch wenn die App nicht offen ist |
| Geräte in der Nähe | Zulassen | Den Beacon im Auto erkennen |
| Benachrichtigungen | Zulassen | Laufende Fahrt, Frage „Beruflich oder privat?“, Warnungen |
| Akku-Optimierung | „Nicht optimiert“ / „Uneingeschränkt“ | Android darf die Erkennung nicht abschalten |

Unter **Mehr → Diagnose** siehst du jederzeit, ob alles passt. Fehlt etwas, gibt es dort einen Knopf zum Beheben.

## 4. Samsung-Handys

Samsung beendet Apps im Hintergrund besonders gern. Zusätzlich einstellen:

1. **Einstellungen → Akku → Hintergrundnutzungslimits → Nie in den Standby-Modus versetzte Apps** → „Fahrtenbuch Pro“ hinzufügen.
2. **Einstellungen → Apps → Fahrtenbuch Pro → Akku** → „Nicht eingeschränkt“.
3. Die App **nicht** aus der Liste der zuletzt verwendeten Apps wegwischen, wenn es nicht nötig ist.

Die Bezeichnungen können je nach One-UI-Version leicht abweichen.

## 5. Datensicherung

Alle Daten liegen nur auf deinem Handy. Geht das Handy verloren oder wird die App gelöscht, sind sie weg. Deshalb:

- **Mehr → Datensicherung → Automatische Sicherung → Ordner wählen.** Am besten ein Ordner in Google Drive, OneDrive oder auf einer SD-Karte, also nicht nur im internen Speicher.
- Die App sichert dann einmal täglich und behält die letzten 14 Sicherungen (einstellbar).
- Gab es 7 Tage keine Sicherung oder schlägt sie fehl, meldet sich die App per Benachrichtigung.
- „Von Hand sichern“ legt jederzeit zusätzlich eine Sicherung an, die du z. B. per Mail an dich selbst schicken kannst.

Wiederherstellen: **Mehr → Datensicherung → Wiederherstellen** und die ZIP-Datei wählen.

## 6. Updates

Die App fragt einmal täglich bei GitHub nach einer neuen Version und meldet sie per Benachrichtigung.

- Antippen öffnet **Mehr → Über die App**. Dort „Herunterladen und installieren“.
- Beim ersten Update fragt Android, ob die App Apps installieren darf. „Installation erlauben“ → Schalter einschalten → zurück.
- Android fragt „App aktualisieren?“. Mit **Aktualisieren** bestätigen. Schlägt Google Play Protect eine Prüfung vor, kannst du „App prüfen“ wählen (die App wird dann an Google geschickt) oder unter „Weitere Details“ „Ohne Prüfung installieren“.
- Vor jeder Installation legt die App eine Sicherung an. Während einer laufenden Fahrt installiert sie nicht. Nach dem Update startet die App neu; deine Daten bleiben erhalten.
- „Jetzt prüfen“ sucht sofort.
- Die Update-Prüfung lässt sich ausschalten. Bitte lass sie während des Tests an.

Dabei sendet die App keine Daten von dir. GitHub sieht nur die übliche Verbindung (IP-Adresse).

## 7. Im Alltag

- Nach jeder Fahrt kommt eine Benachrichtigung mit km und Strecke. Tippe „Beruflich“ oder „Privat“, oder öffne die Fahrt zum Ergänzen.
- Offene Fahrten stehen in der **Prüfliste**. Bitte innerhalb weniger Tage einordnen.
- Einmal im Monat (oder wenn die App erinnert) den **Tachostand** eintragen. So sieht man, wie genau das GPS misst.
- Fahrten werden nie gelöscht, sondern storniert. Das ist für ein ordnungsgemäßes Fahrtenbuch nötig.

## 8. Fehler melden

Fehlt eine Fahrt, ist eine Strecke falsch oder stürzt die App ab:

1. **Mehr → Diagnose → Fehler melden**
2. Zeitraum wählen (z. B. „Heute“) und kurz beschreiben, was passiert ist (Datum, Uhrzeit, was du erwartet hast).
3. Die ZIP-Datei über das Teilen-Menü an mich schicken.

Orte im Bericht sind standardmäßig unkenntlich gemacht. Der Bericht enthält kein Fahrtenbuch, keine Adressen, Namen oder Kennzeichen.

## 9. Bekannte Einschränkungen von Beta 1

- Kein PDF- und Excel-Export (CSV gibt es), kein Periodenabschluss, Sicherung noch unverschlüsselt, keine Karte. Diese Funktionen folgen als Updates.
- Die App zeichnet während der Testphase Erkennungssignale auf (für Fehlerberichte). Das lässt sich unter Mehr → Diagnose abschalten; alte Aufzeichnungen löscht die App nach 30 Tagen.
- Die App ersetzt keine Steuerberatung.
