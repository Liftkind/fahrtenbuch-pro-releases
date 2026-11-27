# Datenschutzerklärung für RoadScript Fahrtenbuch

Stand: 27.11.2026

## 1. Verantwortlicher

Achim Wegner
St. Leon-Rot, Deutschland

E-Mail: support@achimwegner.com

## 2. Das Wichtigste in Kürze

Die App speichert alle Fahrten und Einstellungen nur auf deinem Gerät. Es gibt kein Konto, keinen Server des Entwicklers, keine Werbung und keine Analyse- oder Tracking-Dienste. Ich bekomme deine Daten nur zu sehen, wenn du mir selbst einen Fehlerbericht oder eine E-Mail schickst (Abschnitt 6).

Ins Internet geht die App nur für drei Funktionen, und jede davon lässt sich in den Einstellungen abschalten: Adressauflösung, Kartenansicht und Update-Prüfung (Abschnitt 5).

## 3. Welche Daten die App auf deinem Gerät speichert

- Fahrten: Start- und Endzeit, Start- und Zieladresse, Kilometerstände, Strecke als GPS-Punkte, Fahrttyp, Reisezweck, Zwischenstopps
- Fahrzeuge und Fahrer: Kennzeichen, Bezeichnung, Namen der Fahrer
- Geschäftspartner und gespeicherte Adressen
- Änderungsprotokoll mit altem und neuem Wert jeder Änderung
- Einstellungen, zum Beispiel die Kennung deines Beacons, dein Kilometersatz und die Angaben für das Deckblatt der Berichte
- Diagnose-Aufzeichnungen (Beacon-Signalstärke, GPS-Punkte, Zustandswechsel), eine Datei pro Tag. In der Testphase ist die Aufzeichnung standardmäßig an. Du schaltest sie unter Mehr → Diagnose ab („Signale aufzeichnen“). Die App löscht sie nach der eingestellten Frist (7 bis 90 Tage, Standard 30).
- Zwischengespeicherte Kartenkacheln (bis zu 100 MB), siehe Abschnitt 5.

Die Daten liegen in einem geschützten Bereich der App, auf den andere Apps nicht zugreifen. Die automatische Android-Sicherung in die Google-Cloud ist abgeschaltet.

**Daten anderer Personen:** Wenn du Namen von Fahrern oder Geschäftspartnern erfasst, bist du dafür verantwortlich, diese Personen zu informieren und die Daten nach deinen eigenen Pflichten zu behandeln.

## 4. Berechtigungen und wofür sie dienen

| Berechtigung | Zweck |
|---|---|
| Standort (genau, auch im Hintergrund) | Strecke und Kilometer einer Fahrt messen, auch wenn die App nicht geöffnet ist. Der Standort wird nur während der Fahrterkennung und einer laufenden Fahrt erfasst. |
| Bluetooth (Suche nach Geräten in der Nähe) | Den eigenen iBeacon im Auto erkennen. Die App wertet nur den eingerichteten Beacon aus. |
| Gerätezuordnung (Companion Device) | Android meldet der App, wenn der Beacon in Reichweite kommt, ohne dass sie ständig suchen muss. |
| Benachrichtigungen | Laufende Fahrt anzeigen, nach der Fahrt nach „Beruflich“ oder „Privat“ fragen, auf Prüffälle hinweisen. |
| Vordergrunddienst | Die Aufzeichnung läuft sichtbar mit Benachrichtigung, damit Android sie nicht beendet. |
| Start nach dem Einschalten | Die Fahrterkennung nach einem Neustart des Handys wieder aufnehmen. |
| Ausnahme von der Akku-Optimierung | Verhindern, dass Android die Erkennung im Hintergrund abschaltet. |
| Internet | Nur für die Funktionen in Abschnitt 5. |
| Apps installieren (nur GitHub-Fassung) | Ein heruntergeladenes Update installieren. Du bestätigst jede Installation selbst. |

## 5. Wann die App Daten an Dritte sendet

Jede Verbindung überträgt technisch bedingt die IP-Adresse deines Geräts an den jeweiligen Anbieter.

**Adressauflösung** (abschaltbar): Um aus GPS-Koordinaten eine lesbare Adresse zu machen, übergibt die App die Koordinaten von Start und Ziel an den Adressdienst von Android (Geocoder). Diesen Dienst stellt das Betriebssystem bereit, auf Geräten mit Google-Diensten ist das Google. Umgekehrt schickt die App die Anschrift einer gespeicherten Adresse ohne Koordinaten an diesen Dienst, um ihre Lage zu ermitteln. Ohne Adressauflösung zeigt die App Koordinaten, und du kannst die Adresse von Hand eintragen.
Datenschutzhinweise: [Google](https://policies.google.com/privacy)

**Kartenansicht** (abschaltbar unter „Kartenkacheln laden“): Für den Kartenhintergrund lädt die App Kartenkacheln vom Kachelserver der OpenStreetMap Foundation (Großbritannien). Dabei erfährt der Server deine IP-Adresse und welchen Kartenausschnitt du ansiehst, nicht aber deine Fahrten, Routen oder Adressen; die zeichnet die App selbst auf die Karte. Angesehene Kacheln speichert die App bis zu 100 MB auf dem Gerät. Ausgeschaltet zeigt die Karte Routen und Adressen auf neutralem Hintergrund, ohne Netzzugriff.
Datenschutzhinweise: [OpenStreetMap Foundation](https://osmfoundation.org/wiki/Privacy_Policy)

**Update-Prüfung** (nur in der Fassung von GitHub, abschaltbar): Höchstens einmal am Tag fragt die App bei GitHub (GitHub Inc., USA) nach, ob es eine neue Version gibt. Dabei werden keine Nutzerdaten übertragen, nur die üblichen Verbindungsdaten.
Datenschutzhinweise: [GitHub](https://docs.github.com/de/site-policy/privacy-policies/github-general-privacy-statement)

**Standortdienste von Google:** Für die Standortbestimmung nutzt die App die Standortdienste von Google Play. Ob und wie Google dabei Daten verarbeitet, hängt von deinen Android-Einstellungen ab (zum Beispiel „Google-Standortgenauigkeit“). Die App selbst sendet dabei keine Daten an Google.

Rechtsgrundlage für diese Übertragungen ist Art. 6 Abs. 1 lit. f DSGVO. Das berechtigte Interesse besteht darin, die jeweilige Funktion bereitzustellen.

## 6. Fehlerberichte und E-Mails an mich

Einen Fehlerbericht erstellst du selbst unter Mehr → Fehler melden. Er enthält Gerät, App-Version, Einstellungen und Protokoll der Fahrterkennung, deine Beschreibung und die Diagnose-Aufzeichnungen des gewählten Zeitraums. Orte sind standardmäßig unkenntlich gemacht (die GPS-Punkte werden an einen anderen Ort verschoben). Das Fahrtenbuch selbst, Adressen, Namen und Kennzeichen sind nicht enthalten. Die App verschickt den Bericht nicht selbst: Sie öffnet dein E-Mail-Programm mit einer fertigen Mail an support@achimwegner.com, oder du gibst den Bericht über das Teilen-Menü weiter. Gesendet wird nur, wenn du es dort bestätigst.

Schickst du mir einen Fehlerbericht oder schreibst du mir an support@achimwegner.com, verarbeite ich den Inhalt und deine E-Mail-Adresse, um den Fehler zu finden und dir zu antworten. Rechtsgrundlage ist Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an einer fehlerfreien App und an der Beantwortung deiner Anfrage).

**Auswertung mit KI:** Zur Fehlersuche werte ich Fehlerberichte mit dem KI-Assistenten Claude aus. Anbieter ist für Nutzer in der EU die Anthropic Ireland, Limited (Irland); Anthropic verarbeitet die Inhalte nach seiner eigenen Datenschutzerklärung und auch auf Servern in den USA. Für Übermittlungen in Länder ohne Angemessenheitsbeschluss nutzt Anthropic nach eigener Angabe EU-Standardvertragsklauseln. Die Verwendung meiner Eingaben zum Training der KI-Modelle habe ich ausgeschaltet; laut Anthropic werden Inhalte dann nur noch genutzt, wenn eine Unterhaltung für eine Sicherheitsprüfung markiert wird. Wenn du nicht möchtest, dass dein Bericht mit KI ausgewertet wird, schreib das einfach in die Beschreibung; dann sehe ich ihn mir nur selbst an.
Datenschutzhinweise: [Anthropic](https://www.anthropic.com/legal/privacy)

**Speicherdauer:** Ich lösche Fehlerberichte, sobald der Fehler geklärt ist, spätestens 6 Monate nach Eingang. E-Mails lösche ich, wenn die Anfrage erledigt ist und keine gesetzliche Pflicht zur Aufbewahrung besteht.

## 7. Sicherung, Export und Weitergabe

Sicherungen und Exporte (PDF, XLSX, CSV, Monatsbeleg) entstehen nur, wenn du sie anlegst oder einrichtest. Sie landen in dem Ordner, den du wählst, oder gehen an die App, die du im Teilen-Menü auswählst. Wählst du einen Cloud-Ordner oder einen Messenger, gelten dort die Bedingungen dieses Anbieters. Sicherungen lassen sich mit einem Passwort verschlüsseln.

## 8. Speicherdauer auf deinem Gerät

Die Daten bleiben auf deinem Gerät, bis du sie entfernst oder die App deinstallierst. Bei der Deinstallation löscht Android alle App-Daten. Sicherungen in deinem Ordner bleiben erhalten. Gesetzliche Aufbewahrungspflichten für Fahrtenbücher (in Deutschland in der Regel 10 Jahre, in Österreich 7 Jahre) liegen bei dir.

## 9. Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch. Die Daten in der App verwaltest du selbst. Für Fehlerberichte und E-Mails, die du mir geschickt hast, schreib an support@achimwegner.com. Für Daten bei den in Abschnitt 5 und 6 genannten Anbietern wende dich an diese.

Du kannst dich bei einer Datenschutz-Aufsichtsbehörde beschweren, zum Beispiel in dem Land, in dem du wohnst. Für mich zuständig ist der Landesbeauftragte für den Datenschutz und die Informationsfreiheit Baden-Württemberg, Lautenschlagerstraße 20, 70173 Stuttgart, [www.baden-wuerttemberg.datenschutz.de](https://www.baden-wuerttemberg.datenschutz.de).

## 10. Kinder

Die App richtet sich nicht an Kinder unter 16 Jahren.

## 11. Änderungen

Wenn sich die App ändert, passe ich diese Erklärung an. Es gilt die Fassung mit dem neuesten Stand-Datum.
