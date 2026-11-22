# RoadScript Fahrtenbuch – Anleitung für Tester (Beta 1)

Danke, dass du mittestest. Diese Version ist eine **Testversion**. Sie erkennt Fahrten zuverlässig genug für den Alltag, aber es kann noch Fehler geben. Führe dein offizielles Fahrtenbuch während des Tests deshalb zusätzlich wie bisher weiter.

**Getestet ab Android 14.** Ältere Geräte (Android 13) können funktionieren, sind aber nicht geprüft.

Diese Anleitung hilft beim Installieren und Einrichten. Wie du im Alltag mit der App arbeitest, steht in der [Hilfe](HILFE.md); in der App öffnest du sie unter **Mehr → Hilfe**.

## 1. Installieren

Die App kommt nicht aus dem Play Store, sondern als Datei `roadscript.apk` direkt von mir. Android und vor allem Samsung sind dabei vorsichtig und fragen mehrmals nach. Das ist normal. Plane etwa 10 Minuten ein und geh die Schritte der Reihe nach durch. Die Namen der Menüpunkte können je nach Handy leicht abweichen.

### Schritt 0 (nur Samsung): Automatische Sperre ausschalten

Neuere Samsung-Handys haben die **Automatische Sperre**, oft ab Werk eingeschaltet. Sie blockiert jede App, die nicht aus einem Store kommt, und meldet dann nur „Aus Sicherheitsgründen … nicht installieren“, ohne weiterzuhelfen. Deshalb zuerst:

1. **Einstellungen** öffnen (Zahnrad).
2. **Sicherheit und Datenschutz** antippen.
3. **Automatische Sperre** antippen und ausschalten.
   - Findest du den Punkt nicht: In den Einstellungen oben auf die **Lupe** tippen und „Automatische Sperre“ eingeben. Auf manchen Geräten heißt die Einstellung **Maximale Einschränkungen**.
   - Steht dort schon „Aus“, ist alles gut.

Lässt du die Sperre nach der Installation wieder an, blockiert sie auch die Updates der App. Schalte sie dann für jedes Update kurz aus, oder lass sie während des Tests aus.

### Schritt 1: Datei herunterladen

1. Auf dem **Handy** (nicht am Computer) diesen Link antippen:
   `https://github.com/Liftkind/fahrtenbuch-pro-releases/releases/latest/download/roadscript.apk`
   Er lädt immer die neueste Version.
2. Der Browser (Chrome oder Samsung Internet) warnt, die Datei könnte schädlich sein. **Trotzdem herunterladen** antippen.
3. Unten erscheint kurz „Download abgeschlossen“. Diese Meldung brauchst du nicht, sie darf verschwinden.

### Schritt 2: Datei öffnen

Am zuverlässigsten öffnest du die Datei über die Dateien-App, nicht aus der Mail und nicht aus der Download-Meldung:

- **Samsung:** App **Eigene Dateien** öffnen (oft im Ordner „Samsung“), dann **Downloads**, dann **roadscript.apk** antippen.
- **Andere Handys:** App **Dateien** (Files by Google) öffnen, dann **Downloads**, dann **roadscript.apk** antippen.

Liegen dort mehrere Dateien wie `roadscript (1).apk`, nimm die neueste.

### Schritt 3: Installieren erlauben

Android fragt jetzt, ob die Dateien-App Apps installieren darf. Das musst du nur einmal erlauben.

1. In der Meldung „Aus Sicherheitsgründen ist die Installation unbekannter Apps aus dieser Quelle nicht zulässig“ auf **Einstellungen** tippen.
2. Den Schalter **Erlauben** bzw. **Aus dieser Quelle zulassen** einschalten.
3. Mit der Zurück-Taste (oder Wischgeste) zurückgehen.

### Schritt 4: Installieren

1. „Möchtest du diese App installieren?“ mit **Installieren** bestätigen.
2. Warnt **Google Play Protect** („Unsichere App blockiert“ oder „Unbekannte App“): auf **Weitere Details** tippen, dann **Trotzdem installieren**. Die Warnung kommt, weil Google die App nicht kennt, nicht weil etwas mit ihr nicht stimmt.
3. Nach „App wurde installiert“ auf **Öffnen** tippen. Auf dem Startbildschirm heißt die App **RoadScript**.

Spätere Updates meldet die App selbst (siehe Abschnitt 6). Du musst die Seite nicht beobachten.

### Wenn es nicht klappt

| Meldung oder Problem | Lösung |
|---|---|
| „Aus Sicherheitsgründen …“, **ohne** Knopf Einstellungen (Samsung) | Die Automatische Sperre ist an. Schritt 0, dann die Datei noch einmal öffnen. |
| „Aus Sicherheitsgründen …“, **mit** Knopf Einstellungen | Schritt 3. |
| Die Erlaubnis von Hand setzen | Samsung: **Einstellungen → Sicherheit und Datenschutz → Weitere Sicherheitseinstellungen → Unbekannte Apps installieren**, dort **Eigene Dateien** (bzw. die App, mit der du die Datei öffnest) wählen und erlauben. Andere Handys: **Einstellungen → Apps → Spezieller App-Zugriff → Unbekannte Apps installieren**. |
| Beim Antippen der Datei passiert nichts | Die Datei über **Eigene Dateien** bzw. **Dateien** öffnen (Schritt 2), nicht aus der Mail. |
| „App nicht installiert“ oder „Paket ungültig“ | Der Download ist unvollständig. Datei in Eigene Dateien löschen und Schritt 1 wiederholen, am besten im WLAN. |
| „App nicht installiert, da das Paket mit einem vorhandenen Paket in Konflikt steht“ | Eine ältere Testfassung von mir ist noch installiert. Melde dich bei mir, bevor du etwas deinstallierst, damit keine Fahrten verloren gehen. |
| „Nicht mit deinem Gerät kompatibel“ | Die App braucht Android 13 oder neuer (Einstellungen → Telefoninfo → Softwareinformationen). |
| Diensthandy oder Arbeitsprofil | Meist sperrt die IT der Firma das Installieren. Das lässt sich nur dort ändern. |
| Nichts davon hilft | Schreib mir an support@achimwegner.com mit Handymodell und einem Foto oder Bildschirmfoto der Meldung. |

## 2. Einrichtungsassistent

Beim ersten Start führt dich ein Assistent durch die Einrichtung:

- **Fahrzeug** mit Kennzeichen und aktuellem Kilometerstand vom Tacho
- **Fahrer**, **Adressen** (Wohnung, Arbeit, ggf. Familienwohnsitz)
- **Beacon**: Der kleine Sender im Auto (iBeacon, siehe unten). Lege ihn ins Auto, schalte ihn ein und lass die App danach suchen. Ohne Beacon erkennt die App keine Fahrten automatisch; du kannst Fahrten dann nur von Hand eintragen.
- **Berechtigungen** (Abschnitt 3)
- **Sicherung**: Wähle hier einen **Sicherungsordner** (Abschnitt 5). Das ist wichtig.

**Welcher Beacon?** Die App funktioniert mit jedem iBeacon. Achte beim Kauf auf drei Dinge: Der Beacon sendet als **iBeacon**, behält immer dieselbe Bluetooth-Adresse (bei manchen Modellen einstellbar), und die Batterie lässt sich wechseln. Welches Modell ich empfehle, sage ich dir, sobald ich es selbst mit der App getestet habe. Für den Test brauchst du keinen Beacon: Ohne Beacon tippst du vor der Fahrt auf „Start“, den Rest macht die App genauso. Lege den Beacon so ins Auto, dass er nicht in der Sonne liegt, zum Beispiel ins Handschuhfach.

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

1. **Einstellungen → Akku → Hintergrundnutzungslimits → Nie in den Standby-Modus versetzte Apps** → „RoadScript“ hinzufügen.
2. **Einstellungen → Apps → RoadScript → Akku** → „Nicht eingeschränkt“.
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
- **Karte:** In der Fahrt siehst du die gefahrene Strecke auf einer kleinen Karte (antippen für groß, mit zwei Fingern zoomen). Das Kartensymbol im Reiter „Fahrten“ zeigt alle Fahrten eines Monats, das unter **Mehr → Adressen** deine Adressen mit Radius. Dort legt langes Drücken eine neue Adresse an. Die Karte kommt von OpenStreetMap; ohne Netz siehst du Ausschnitte, die du schon einmal angesehen hast. Abschalten: **Mehr → Einstellungen → Kartenkacheln laden**.
- Fahrten werden nie gelöscht, sondern storniert. Das ist für ein ordnungsgemäßes Fahrtenbuch nötig.

## 8. Fehler melden

Fehlt eine Fahrt, ist eine Strecke falsch oder stürzt die App ab:

1. **Mehr → Fehler melden**
2. Zeitraum wählen (z. B. „Heute“) und kurz beschreiben, was passiert ist (Datum, Uhrzeit, was du erwartet hast).
3. Auf **Erstellen und senden** tippen. Dein E-Mail-Programm öffnet sich mit einer fertigen Mail an **support@achimwegner.com**, der Bericht hängt an. Du tippst nur noch auf Senden. Ohne E-Mail-Programm hilft der Knopf **Anders teilen**.

Orte im Bericht sind standardmäßig unkenntlich gemacht. Der Bericht enthält kein Fahrtenbuch, keine Adressen, Namen oder Kennzeichen. Ich werte Berichte auch mit einer KI aus (Claude von Anthropic). Möchtest du das nicht, schreib es in die Beschreibung.

Fragen und Rückmeldungen jeder Art gern ebenfalls an support@achimwegner.com.

## 9. Bekannte Einschränkungen von Beta 1

- Die App zeichnet während der Testphase Erkennungssignale auf (für Fehlerberichte). Das lässt sich unter Mehr → Diagnose abschalten; alte Aufzeichnungen löscht die App nach 30 Tagen.
- Die App ersetzt keine Steuerberatung.

## 10. Datenschutz

Deine Fahrten bleiben auf deinem Handy. Was die App ins Internet schickt und wie ich mit Fehlerberichten umgehe, steht in der [Datenschutzerklärung](DATENSCHUTZ.md).
