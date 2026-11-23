# RoadScript Fahrtenbuch – Anleitung für Tester (Beta 1)

Danke, dass du mittestest. Diese Version ist eine **Testversion**. Sie erkennt Fahrten zuverlässig genug für den Alltag, aber es kann noch Fehler geben. Führe dein offizielles Fahrtenbuch während des Tests deshalb zusätzlich wie bisher weiter.

**Getestet ab Android 14.** Ältere Geräte (Android 13) können funktionieren, sind aber nicht geprüft.

Diese Anleitung führt dich Schritt für Schritt durch Installieren und Einrichten. Du brauchst dafür kein technisches Vorwissen. Wie du im Alltag mit der App arbeitest, steht in der [Hilfe](HILFE.md); in der App öffnest du sie unter **Mehr → Hilfe**.

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

Spätere Updates meldet die App selbst (siehe Abschnitt 7). Du musst die Seite nicht beobachten.

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

## 2. Erster Start: Fahrtenbuch einrichten

Beim ersten Öffnen erscheint die Seite **Fahrtenbuch einrichten**. Plane dafür 5 Minuten ein und leg dir den Fahrzeugschein und den aktuellen Tachostand bereit (am besten vorher im Auto ablesen).

1. **Land:** Deutschland oder Österreich antippen, je nachdem, wo du steuerpflichtig bist.
2. Der Kasten **Vorab mit der Steuerberatung klären** ist nur ein Hinweis. Lies ihn kurz und scroll weiter.
3. **Dein Name:** Vor- und Nachname eintragen. Du stehst dann als Fahrer in jeder Fahrt.
4. **Fahrzeug:**
   - **Bezeichnung:** zum Beispiel „VW Golf“.
   - **Kennzeichen:** so wie auf dem Nummernschild, zum Beispiel „M-AB 123“.
   - **Antriebsart:** Benzin, Diesel, Elektro usw. auswählen.
   - **Kilometerstand zu Beginn:** der Stand vom Tacho, nur ganze Kilometer. **Bitte genau eintragen.** Er lässt sich später nicht mehr ändern, sobald die erste Fahrt gespeichert ist.
   - **Fahrzeugmodus:** **Privat** für dein eigenes Auto, mit dem du auch beruflich fährst. **Firma** für einen Firmenwagen mit Fahrtenbuch. Im Zweifel **Privat**.
   - **Kilometersatz** und **Gültig ab:** sind schon vorausgefüllt. Lass sie so, wenn du nichts anderes weißt.
5. Ganz unten auf **Einrichtung abschließen** tippen.

Alles außer dem Kilometerstand zu Beginn kannst du später unter **Mehr** ändern.

Danach öffnet sich der Assistent **Fahrterkennung einrichten**. Er hat 6 Schritte, oben steht „Schritt 1 von 6“ usw. Unten sind immer drei Knöpfe: **Zurück**, **Überspringen** und **Weiter**. Geh die Schritte der Reihe nach durch, die nächsten Abschnitte erklären jeden davon.

Hast du den Assistenten aus Versehen verlassen: Du findest ihn wieder unter **Mehr → Beacon** oder über den Hinweis auf der **Übersicht**.

## 3. Assistent Schritt 1: Berechtigungen

Damit die App Fahrten selbst erkennt, muss Android ihr vier Dinge erlauben. Auf der Seite stehen dafür vier Knöpfe untereinander. Tipp sie **von oben nach unten** an. Nach jedem Knopf erscheint eine Frage von Android:

1. **Standort (genau) erlauben** antippen. Android fragt, ob die App den Standort verwenden darf.
   - Falls zwei Bilder **Genau** und **Ungefähr** zu sehen sind: **Genau** antippen.
   - Dann **Bei Nutzung der App** (oder **Während der App-Nutzung**) antippen. Nicht „Nur dieses Mal“.
2. **Geräte in der Nähe (Bluetooth-Suche) erlauben** antippen. Android fragt, ob die App Geräte in der Nähe finden darf: **Zulassen**.
3. **Benachrichtigungen erlauben** antippen. Android fragt, ob die App Benachrichtigungen senden darf: **Zulassen**.
4. **Standort „immer“ erlauben** antippen. Jetzt öffnet Android eine Einstellungsseite statt einer Frage. Das ist richtig so.
   - Dort **Immer zulassen** antippen.
   - Gibt es den Schalter **Genauen Standort verwenden**, muss er eingeschaltet sein.
   - Dann mit der Zurück-Taste (oder Wischgeste vom Rand) zurück in die App.

Neben jedem Punkt steht jetzt **Erledigt**. Dann unten auf **Weiter** tippen.

**Warum „immer“?** Die App muss die Strecke auch messen, wenn sie gerade nicht offen ist und das Handy in der Tasche steckt. Sie nutzt den Standort nur, solange eine Fahrt läuft oder geprüft wird.

**Wenn es nicht klappt:** Hast du aus Versehen „Nicht zulassen“ gewählt, fragt Android oft kein zweites Mal. Dann erscheint der Knopf **App-Einstellungen öffnen**. Antippen, dann **Berechtigungen**, und dort jede Berechtigung einzeln antippen und erlauben (Standort: **Immer zulassen**). Danach zurück in die App.

## 4. Assistent Schritt 2: Akku

Android legt Apps im Hintergrund gern schlafen, um Akku zu sparen. Dann verpasst die App den Anfang einer Fahrt. Deshalb:

1. **Akkuoptimierung ausschalten** antippen.
2. Android fragt, ob die App immer im Hintergrund laufen darf: **Zulassen**.
3. Neben dem Punkt steht jetzt **Von Akkuoptimierung ausgenommen**.

**Nur bei Samsung** erscheint darunter ein zweiter Punkt **„Nie schlafende Apps“ (Samsung)**. Samsung legt Apps nämlich zusätzlich schlafen. So geht es:

1. **Akku-Einstellungen öffnen** antippen. Die Seite **Akku** öffnet sich.
2. **Grenzen der Hintergrundnutzung** antippen. (Auf älteren Handys: **Hintergrundnutzungslimits**.)
3. **Apps nie automatisch in Standby** antippen. (Auf älteren Handys: **Nie schlafende Apps** oder **Nie in den Standby-Modus versetzte Apps**.)
4. Oben rechts auf **+** tippen.
5. **RoadScript** suchen, antippen (Haken setzen) und auf **Hinzufügen** tippen. Steht RoadScript schon in der Liste oder fehlt es in der Auswahl, ist die App bereits eingetragen. Das ist dann auch gut.
6. Mit der Zurück-Taste zurück in die App und dort beim Samsung-Punkt auf **Erledigt** tippen.

Dann unten auf **Weiter**.

Zusätzlich gilt auf allen Handys: Die App nicht aus der Liste der zuletzt geöffneten Apps wegwischen. Das ist nicht nötig und kann die Erkennung bis zur nächsten Fahrt unterbrechen.

## 5. Assistent Schritte 3 bis 6

### Schritt 3: Beacon

Der Beacon ist ein kleiner Bluetooth-Sender, etwa so groß wie eine Münze oder ein Schlüsselanhänger, der dauerhaft im Auto liegt. Merkt das Handy ihn, weiß die App: Du sitzt im Auto, gleich geht eine Fahrt los.

**Du hast keinen Beacon?** Dann unten auf **Überspringen** tippen, ebenso bei Schritt 4. Die App funktioniert trotzdem. Du tippst dann vor jeder Fahrt auf **Start** (siehe Abschnitt 8, „Fahrt von Hand“), den Rest macht sie genauso.

**Du hast einen Beacon:**

1. Beacon einschalten (meist ein Knopf oder die Batterie-Lasche herausziehen) und mit dem Handy ins Auto setzen. Der Motor muss nicht laufen.
2. **Beacon suchen** antippen. Die App sucht 30 Sekunden.
3. In der Liste erscheinen Beacons. Deiner ist meist der mit dem Zusatz **stärkster**. Ihn antippen.
4. Im Fenster **Beacon zuordnen** dein Fahrzeug wählen und **Zuordnen und koppeln** antippen.
5. Android fragt, ob die App mit dem Gerät verbunden werden darf: **Zulassen** (oder **Koppeln**).
6. Es erscheint „Beacon gekoppelt.“. Oben links auf den Pfeil **Zurück** tippen, dann bist du wieder im Assistenten. Dort **Weiter**.

Findet die App nichts („Kein Beacon gefunden“): Ist Bluetooth am Handy eingeschaltet? Ist der Beacon eingeschaltet und nah am Handy? Dann **Erneut suchen**.

Lege den Beacon später so ins Auto, dass er nicht in der Sonne liegt, zum Beispiel ins Handschuhfach.

**Welcher Beacon?** Du bist an keinen bestimmten Hersteller gebunden. Beim Kauf auf drei Dinge achten: Er sendet als **iBeacon**, behält immer dieselbe Bluetooth-Adresse (bei manchen Modellen einstellbar), und die Batterie lässt sich wechseln. Welches Modell ich empfehle, sage ich dir, sobald ich es selbst mit der App getestet habe.

### Schritt 4: Kalibrierung (nur mit Beacon)

Die App lernt hier, wie stark der Beacon im Auto zu sehen ist und wie stark im Haus. So startet keine Fahrt, nur weil du im Haus nahe am geparkten Auto sitzt.

1. **Kalibrieren** antippen.
2. Mit dem Handy ins Auto setzen und **Im Auto messen** antippen. 30 Sekunden warten.
3. Mit dem Handy ins Haus gehen, an den Platz, der dem Auto am nächsten ist und an dem das Handy oft liegt. **Im Haus messen** antippen und warten.
4. **Übernehmen** antippen, dann **Weiter**.

Kommt eine Meldung wie „Es gilt der Standardwert“, ist das in Ordnung. Die App funktioniert dann trotzdem.

### Schritt 5: Datensicherung

Das Fahrtenbuch liegt nur auf deinem Handy. Geht das Handy verloren oder kaputt, sind die Fahrten ohne Sicherung weg. Diesen Schritt bitte **nicht** überspringen.

1. **Ordner für automatische Sicherung wählen** antippen. Android zeigt eine Seite mit Ordnern.
2. Einen Ordner wählen, am besten so:
   - Steht oben schon **Documents** (oder **Dokumente**), bist du richtig. Sonst oben links auf die drei Striche **☰** tippen, den Speicher deines Handys wählen (er heißt wie dein Handy, z. B. „Galaxy A54“) und **Documents** antippen.
   - Oben auf das Symbol **Neuer Ordner** tippen (Ordner mit Plus; falls nicht zu sehen: oben rechts **⋮** und **Neuer Ordner**). **Fahrtenbuch** eintippen und **OK**. Den neuen Ordner antippen, damit du darin bist.
3. Unten auf **Diesen Ordner verwenden** tippen.
4. Android fragt, ob die App auf die Dateien in diesem Ordner zugreifen darf: **Zulassen**.
5. Die App legt sofort die erste Sicherung an und sichert ab jetzt jeden Tag selbst dorthin. Neben dem Punkt steht **Sicherung vorhanden**. Dann **Weiter**.

Meldet Android „Dieser Ordner kann nicht verwendet werden“, bist du im obersten Ordner oder im Ordner Download. Dann einen Ordner wie Documents/Fahrtenbuch wählen (Schritt 2).

Eine Sicherung im Handyspeicher hilft, wenn die App kaputtgeht, aber nicht, wenn das Handy verloren geht. Wie du zusätzlich in die Cloud oder an dich selbst sicherst, steht in Abschnitt 6.

### Schritt 6: Erkennung einschalten

1. **Standard (empfohlen)** ausgewählt lassen.
2. **Erkennung jetzt einschalten** antippen.
3. Zum Schluss zeigt die **Zusammenfassung**, was fertig ist. Steht dort „Alles eingerichtet“, bist du fertig.

Ohne Beacon steht hier „Bitte zuerst einen Beacon einrichten.“. Dann einfach **Überspringen**. Fahrten trägst du dann von Hand ein oder startest sie mit **Start**.

Steht in der Zusammenfassung ein Schritt als offen, kannst du ihn antippen und nachholen.

### Nach dem Assistenten: Adressen eintragen (empfohlen)

Damit die App weiß, wann du zu Hause oder in der Arbeit bist, trag deine wichtigsten Orte ein: **Mehr → Adressen**, dann **+**. Mindestens die Wohnung und die Arbeitsstelle, bei doppelter Haushaltsführung auch den Familienwohnsitz.

### Ist alles richtig eingestellt?

Oben auf der **Übersicht** steht ein schmaler **Statusbalken**. Grün heißt alles in Ordnung. Rot nennt kurz den Grund, zum Beispiel „Bluetooth aus“. Antippen führt direkt zum Beheben. Genaueres steht unter **Mehr → Diagnose**.

## 6. Datensicherung im Alltag

Die automatische Sicherung aus dem Assistenten läuft von selbst: einmal am Tag, die letzten 14 Sicherungen bleiben liegen, ältere löscht die App. Gab es 7 Tage keine Sicherung oder schlägt sie fehl, zeigt die App einen Hinweis auf der Übersicht. Du findest alles unter **Mehr → Datensicherung**.

**Zusätzlich außerhalb des Handys sichern (empfohlen),** etwa einmal im Monat:

1. **Mehr → Datensicherung** öffnen.
2. Unter **Von Hand sichern** auf **Jetzt sichern** tippen.
3. Android fragt, wo die Datei hin soll. Oben links auf **☰** tippen und **Google Drive** (oder OneDrive, Dropbox) wählen, wenn es dort steht. Dann **Speichern**.
   - Steht dort keine Cloud, speichere die Datei in Documents/Fahrtenbuch und schick sie dir danach per Mail an dich selbst.

**Verschlüsseln (empfohlen, wenn die Sicherung in die Cloud geht):**

1. **Mehr → Datensicherung → Verschlüsselung**, Schalter **Sicherungen verschlüsseln** einschalten.
2. Ein Passwort zweimal eingeben, das Kästchen „Ich habe verstanden …“ antippen und **Einschalten**.
3. **Schreib das Passwort auf Papier.** Ohne das Passwort lässt sich eine verschlüsselte Sicherung nicht wiederherstellen. Niemand kann es zurücksetzen, auch ich nicht.

**Wiederherstellen** (zum Beispiel auf einem neuen Handy):

1. App installieren (Abschnitt 1) und öffnen.
   - Die Seite **Fahrtenbuch einrichten** kurz ausfüllen. Die Angaben ersetzt gleich die Sicherung.
   - Im Assistenten Schritt 1 und 2 erledigen (Abschnitte 3 und 4), die übrigen Schritte **überspringen**.
2. **Mehr → Datensicherung → Wiederherstellen → Sicherung auswählen …**
3. Die Sicherungsdatei suchen und antippen. Sie heißt `fahrtenbuch-…` und endet auf `.zip` oder, wenn verschlüsselt, auf `.fbsich`.
4. Die App zeigt, was in der Sicherung steckt. Mit **Wiederherstellen** bestätigen. Bei einer verschlüsselten Sicherung fragt sie nach dem Passwort. Danach startet die App neu.
5. Auf dem neuen Handy danach den Sicherungsordner und gegebenenfalls die Verschlüsselung wieder einschalten.

## 7. Updates

Die App fragt einmal am Tag bei GitHub nach, ob es eine neue Version gibt. Dabei sendet sie keine Daten von dir.

**Samsung:** Hast du die Automatische Sperre nach der Installation wieder eingeschaltet (Abschnitt 1, Schritt 0), schalte sie vor dem Update kurz aus. Sonst blockiert sie das Update ohne klare Meldung.

So installierst du ein Update:

1. Es erscheint die Benachrichtigung **Update auf Version … verfügbar**. Antippen. (Hast du sie weggewischt: **Mehr → Über die App**.)
2. Auf **Herunterladen und installieren** tippen. Die App legt vorher selbst eine Sicherung an.
3. **Nur beim ersten Update:** Die App meldet, dass du die Installation einmal erlauben musst. **Installation erlauben** antippen, auf der Einstellungsseite den Schalter **Aus dieser Quelle zulassen** (oder **Erlauben**) einschalten und mit der Zurück-Taste zurück in die App. Dann noch einmal **Herunterladen und installieren**.
4. Android fragt, ob du die App aktualisieren möchtest: **Aktualisieren**.
5. Meldet sich **Google Play Protect**, auf **Weitere Details** und dann **Trotzdem installieren** (oder **Ohne Prüfung installieren**) tippen.
6. Die App startet neu. Deine Fahrten bleiben erhalten.

Während einer laufenden Fahrt installiert die App nicht. Dann einfach nach der Fahrt.

Ohne Benachrichtigung prüfen: **Mehr → Über die App → Jetzt prüfen**. Die Update-Prüfung lässt sich dort ausschalten; bitte lass sie während des Tests an.

**Wenn es nicht klappt:**

| Meldung oder Problem | Lösung |
|---|---|
| „GitHub ist gerade nicht erreichbar“ | Internet prüfen (WLAN oder mobile Daten an) und später erneut versuchen. |
| „Die Installation wurde abgebrochen“ | Du hast bei Android auf Abbrechen getippt. Einfach noch einmal **Herunterladen und installieren**. |
| Samsung: „Aus Sicherheitsgründen …“ ohne Knopf | Die Automatische Sperre ist an. Ausschalten (Abschnitt 1, Schritt 0) und erneut versuchen. |
| Es passiert gar nichts | Neueste Version von Hand laden wie in Abschnitt 1, Schritte 1 bis 4. Du installierst einfach drüber, deine Daten bleiben erhalten. **Nicht vorher deinstallieren**, sonst sind die Fahrten weg. |

## 8. Im Alltag

- Nach jeder Fahrt kommt eine Benachrichtigung mit km und Strecke. Tippe „Beruflich“ oder „Privat“, oder öffne die Fahrt zum Ergänzen.
- Offene Fahrten stehen in der **Prüfliste** (Hinweis auf der Übersicht, „… Einträge prüfen“). Bitte innerhalb weniger Tage einordnen.
- **Schnell einordnen per Wischen:** In der Fahrtenliste und der Prüfliste eine Fahrt nach rechts wischen = beruflich, nach links = privat. Fehlt danach nichts, ist die Fahrt bestätigt. Vertan? In die andere Richtung wischen. Seltene Aktionen wie Stornieren findest du in der Fahrt oben rechts im Menü ⋮.
- **Tank- und Ladestopps:** Speichere Tankstellen und Ladesäulen, die du öfter nutzt, als Adresse mit dem Typ „Tank- oder Ladestopp“. Eine Pause dort teilt die Fahrt nicht, sie erscheint als Zwischenstopp „Laden“ bzw. „Tanken“. Hast du eine Fahrt doch in zwei Teilen, kannst du sie in der Fahrtenliste zusammenführen.
- **Fahrt von Hand:** Hat das Auto keinen Beacon (Mietwagen, zweites Auto) oder erkennt die App eine Fahrt nicht, tippe auf der Übersicht oben rechts in der blauen Leiste auf **▶ Start** und bestätige mit **Fahrt starten**. Die App zeichnet dann mit GPS auf. Beenden mit **■ Stopp** oben rechts oder mit „Beenden“ in der Benachrichtigung; die App fragt vorher immer nach. Eine von Hand gestartete Fahrt endet nie von selbst; steht das Auto 30 Minuten, erinnert die App.
- **Tachostand:** Einmal im Monat (oder wenn die App erinnert) den Tachostand eintragen: **Mehr → Kilometerabgleich**. Kleine Abweichungen (bis 1 %, mindestens 2 km) sind normale Messabweichungen. Mit **Verteilen** rechnet die App sie anteilig auf die erkannten Fahrten seit dem letzten Abgleich um.
- **Berichte:** Unter **Export** gibt es PDF, Excel und CSV, wählbar nach Zeitraum, Fahrzeug, Kategorien und Fahrern. Name und Anschrift für das Deckblatt trägst du unter **Mehr → Angaben für Berichte** ein.
- **Karte:** In der Fahrt siehst du die gefahrene Strecke auf einer kleinen Karte (antippen für groß, mit zwei Fingern zoomen). Das Kartensymbol im Reiter „Fahrten“ zeigt alle Fahrten eines Monats, das unter **Mehr → Adressen** deine Adressen mit Radius. Dort legt langes Drücken eine neue Adresse an. Die Karte kommt von OpenStreetMap; ohne Netz siehst du Ausschnitte, die du schon einmal angesehen hast. Abschalten: **Mehr → Einstellungen → Kartenkacheln laden**.
- Fahrten werden nie gelöscht, sondern storniert. Das ist für ein ordnungsgemäßes Fahrtenbuch nötig.

## 9. Fehler melden

Fehlt eine Fahrt, ist eine Strecke falsch oder stürzt die App ab:

1. **Mehr → Fehler melden** öffnen und auf **Fehler melden …** tippen.
2. Zeitraum wählen (z. B. „Heute“) und kurz beschreiben, was passiert ist (Datum, Uhrzeit, was du erwartet hast).
3. Auf **Erstellen und senden** tippen. Dein E-Mail-Programm öffnet sich mit einer fertigen Mail an **support@achimwegner.com**, der Bericht hängt an. Du tippst nur noch auf Senden. Ohne E-Mail-Programm hilft der Knopf **Anders teilen**.

Orte im Bericht sind standardmäßig unkenntlich gemacht. Der Bericht enthält kein Fahrtenbuch, keine Adressen, Namen oder Kennzeichen. Ich werte Berichte auch mit einer KI aus (Claude von Anthropic). Möchtest du das nicht, schreib es in die Beschreibung.

Fragen und Rückmeldungen jeder Art gern ebenfalls an support@achimwegner.com.

## 10. Bekannte Einschränkungen von Beta 1

- Die App zeichnet während der Testphase Erkennungssignale auf (für Fehlerberichte). Das lässt sich unter Mehr → Diagnose abschalten; alte Aufzeichnungen löscht die App nach 30 Tagen.
- Die App ersetzt keine Steuerberatung.

## 11. Datenschutz

Deine Fahrten bleiben auf deinem Handy. Was die App ins Internet schickt und wie ich mit Fehlerberichten umgehe, steht in der [Datenschutzerklärung](DATENSCHUTZ.md).
