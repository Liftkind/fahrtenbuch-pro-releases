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

Ob alles passt, zeigt der schmale **Statusbalken** oben auf der Übersicht: zwei Leuchten für die Erkennung und den Beacon. Grün heißt alles in Ordnung, rot nennt kurz den Grund (z. B. „Bluetooth aus“). Antippen führt direkt zum Beheben. Genauere Angaben stehen unter **Mehr → Diagnose**.

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
- **Verschlüsseln (empfohlen bei Cloud-Ordnern):** Schalter **Sicherungen verschlüsseln**, Passwort zweimal eingeben. Die Dateien enden dann auf `.fbsich`. **Ohne das Passwort lässt sich eine verschlüsselte Sicherung nicht wiederherstellen.** Niemand kann es zurücksetzen, auch ich nicht.

Wiederherstellen: **Mehr → Datensicherung → Wiederherstellen** und die Sicherung (`.zip` oder `.fbsich`) wählen. Bei einer verschlüsselten Sicherung fragt die App nach dem Passwort. Auf einem neuen Handy schaltest du die Verschlüsselung danach wieder ein.

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
- Offene Fahrten stehen in der **Prüfliste** (Hinweis auf der Übersicht, „… Einträge prüfen“). Bitte innerhalb weniger Tage einordnen.
- **Schnell einordnen per Wischen:** In der Fahrtenliste und der Prüfliste eine Fahrt nach rechts wischen = beruflich, nach links = privat. Fehlt danach nichts, ist die Fahrt bestätigt. Vertan? In die andere Richtung wischen. Seltene Aktionen wie Stornieren findest du in der Fahrt oben rechts im Menü ⋮.
- **Tank- und Ladestopps:** Speichere Tankstellen und Ladesäulen, die du öfter nutzt, als Adresse mit dem Typ „Tank- oder Ladestopp“. Eine Pause dort teilt die Fahrt nicht, sie erscheint als Zwischenstopp „Laden“ bzw. „Tanken“. Hast du eine Fahrt doch in zwei Teilen, kannst du sie in der Fahrtenliste zusammenführen.
- **Fahrt von Hand:** Hat das Auto keinen Beacon (Mietwagen, zweites Auto) oder erkennt die App eine Fahrt nicht, tippe auf der Übersicht oben rechts in der blauen Leiste auf **▶ Start** und bestätige mit **Fahrt starten**. Die App zeichnet dann mit GPS auf. Beenden mit **■ Stopp** oben rechts oder mit „Beenden“ in der Benachrichtigung; die App fragt vorher immer nach. Eine von Hand gestartete Fahrt endet nie von selbst; steht das Auto 30 Minuten, erinnert die App.
- **Tachostand:** Einmal im Monat (oder wenn die App erinnert) den Tachostand eintragen: **Mehr → Kilometerabgleich**. Kleine Abweichungen (bis 1 %, mindestens 2 km) sind normale Messabweichungen. Mit **Verteilen** rechnet die App sie anteilig auf die erkannten Fahrten seit dem letzten Abgleich um.
- **Berichte:** Unter **Export** gibt es PDF, Excel und CSV, wählbar nach Zeitraum, Fahrzeug, Kategorien und Fahrern. Name und Anschrift für das Deckblatt trägst du unter **Mehr → Angaben für Berichte** ein.
- **Karte:** In der Fahrt siehst du über „Weitere Angaben“ die gefahrene Strecke (antippen für groß). Das Kartensymbol im Reiter „Fahrten“ zeigt alle Fahrten eines Monats, das unter **Mehr → Adressen** deine Adressen mit Radius. Dort legt langes Drücken eine neue Adresse an. Die Karte kommt von OpenStreetMap; ohne Netz siehst du Ausschnitte, die du schon einmal angesehen hast. Abschalten: **Mehr → Einstellungen → Kartenkacheln laden**.
- Fahrten werden nie gelöscht, sondern storniert. Das ist für ein ordnungsgemäßes Fahrtenbuch nötig.

## 8. Fehler melden

Fehlt eine Fahrt, ist eine Strecke falsch oder stürzt die App ab:

1. **Mehr → Fehler melden**
2. Zeitraum wählen (z. B. „Heute“) und kurz beschreiben, was passiert ist (Datum, Uhrzeit, was du erwartet hast).
3. Die ZIP-Datei über das Teilen-Menü an mich schicken.

Orte im Bericht sind standardmäßig unkenntlich gemacht. Der Bericht enthält kein Fahrtenbuch, keine Adressen, Namen oder Kennzeichen.

## 9. Bekannte Einschränkungen von Beta 1

- Die App zeichnet während der Testphase Erkennungssignale auf (für Fehlerberichte). Das lässt sich unter Mehr → Diagnose abschalten; alte Aufzeichnungen löscht die App nach 30 Tagen.
- Die App ersetzt keine Steuerberatung.
