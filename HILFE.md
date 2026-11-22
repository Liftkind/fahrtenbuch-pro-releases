# Fahrtenbuch Pro – Hilfe

Diese Seite erklärt, wie du mit der App im Alltag arbeitest. Wie du sie installierst und einrichtest, steht in der [Anleitung für Tester](ANLEITUNG_TESTER.md). Fragen, die hier nicht beantwortet werden, gern an **support@achimwegner.com**.

**Inhalt**

1. [Erste Schritte](#1-erste-schritte)
2. [Erkennung und Beacon](#2-erkennung-und-beacon)
3. [Fahrten einordnen](#3-fahrten-einordnen)
4. [Fahrt von Hand](#4-fahrt-von-hand)
5. [Laden und Tanken unterwegs](#5-laden-und-tanken-unterwegs)
6. [Tachoabgleich und Verteilen](#6-tachoabgleich-und-verteilen)
7. [Berichte und Export](#7-berichte-und-export)
8. [Karte](#8-karte)
9. [Datensicherung und Verschlüsselung](#9-datensicherung-und-verschlüsselung)
10. [Neues Fahrtenbuch beginnen](#10-neues-fahrtenbuch-beginnen)
11. [Handy wechseln oder verkaufen](#11-handy-wechseln-oder-verkaufen)
12. [Fehler melden](#12-fehler-melden)
13. [Häufige Fragen](#13-häufige-fragen)

## 1. Erste Schritte

Beim ersten Start führt dich ein Assistent durch Fahrzeug, Fahrer, Adressen, Beacon, Berechtigungen und Sicherungsordner. Die einzelnen Schritte beschreibt die [Anleitung für Tester](ANLEITUNG_TESTER.md), Abschnitte 2 bis 5.

Danach brauchst du die App im Alltag kaum zu öffnen. Sie erkennt Fahrten selbst und fragt nach jeder Fahrt per Benachrichtigung, ob sie beruflich oder privat war.

## 2. Erkennung und Beacon

**Statusbalken:** Oben auf der Übersicht zeigt ein schmaler Balken zwei Leuchten, eine für die Erkennung und eine für den Beacon. Grün heißt alles in Ordnung. Rot nennt kurz den Grund, etwa „Bluetooth aus“ oder „Standort nicht immer erlaubt“. Antippen führt direkt dorthin, wo du es behebst. Genauere Angaben stehen unter **Mehr → Diagnose**.

**Beacon-Warnung:** Auf der Übersicht und als Benachrichtigung „Beacon prüfen“ meldet die App zwei Dinge:

- *Die Batterie des Beacons ist schwach:* Der Beacon meldet weniger als 20 % Batterie. Wechsle sie bald. Nicht jeder Beacon meldet seinen Batteriestand; dann gibt es diese Warnung nicht.
- *Seit mehr als 3 Tagen nicht gesehen:* Das Handy hat den Beacon 3 Tage lang nicht empfangen. Vielleicht bist du nicht gefahren, der Beacon liegt nicht mehr im Auto oder seine Batterie ist leer. Bist du in der Zeit gefahren, fehlen diese Fahrten vermutlich. Dann bitte einen Fehler melden (Abschnitt 12).

Die App prüft stündlich und meldet jeden Hinweis nur einmal. Ist alles wieder in Ordnung, verschwindet die Benachrichtigung von selbst.

**Samsung-Handys** beenden Apps im Hintergrund besonders gern. Trag die App unter **Einstellungen → Akku → Hintergrundnutzungslimits → Nie in den Standby-Modus versetzte Apps** ein und stell unter **Einstellungen → Apps → Fahrtenbuch Pro → Akku** „Nicht eingeschränkt“ ein. Die Bezeichnungen weichen je nach One-UI-Version leicht ab.

**Beacon tauschen oder neu kalibrieren:** unter **Mehr → Beacon**.

## 3. Fahrten einordnen

Nach jeder Fahrt kommt eine Benachrichtigung mit Kilometern und Strecke. Tippe **Beruflich** oder **Privat**. Antippen der Benachrichtigung öffnet die Fahrt, dort ergänzt du Reisezweck, Geschäftspartner oder Fahrer.

**Per Wischen:** In der Fahrtenliste und in der Prüfliste eine Fahrt nach rechts wischen heißt beruflich, nach links privat. Fehlt danach keine Pflichtangabe, ist die Fahrt bestätigt. Vertan? In die andere Richtung wischen.

**Prüfliste:** Fahrten, bei denen etwas fehlt oder unsicher ist, sammelt die App unter **Mehr → Prüfliste**. Auf der Übersicht steht ein Hinweis „… Einträge prüfen“. Ordne Fahrten bitte innerhalb weniger Tage ein; das Finanzamt erwartet ein zeitnah geführtes Fahrtenbuch.

**Vorschläge:** Unter **Mehr → Einordnungsregeln** legst du Zeitregeln an, etwa „werktags 7 bis 9 Uhr beruflich“. Die App merkt sich außerdem, wie du Fahrten zu bestimmten Adressen eingeordnet hast. Ein Vorschlag ist nur ein Vorschlag; bestätigen musst du selbst.

**Korrigieren und stornieren:** Fahrten werden nie gelöscht. Seltene Aktionen wie Stornieren oder Teilen am Zwischenstopp findest du in der Fahrt oben rechts im Menü ⋮. Mehrere Fahrten führst du zusammen, indem du in der Fahrtenliste lange auf eine Fahrt drückst und weitere antippst. Jede Änderung steht mit altem und neuem Wert im Änderungsprotokoll.

## 4. Fahrt von Hand

Hat das Auto keinen Beacon (Mietwagen, zweites Auto) oder hat die App eine Fahrt nicht erkannt:

- **Jetzt fahren:** Auf der Übersicht oben rechts in der blauen Leiste **▶ Start** antippen und mit **Fahrt starten** bestätigen. Die App zeichnet dann mit GPS auf. Beenden mit **■ Stopp** oder mit „Beenden“ in der Benachrichtigung. Eine von Hand gestartete Fahrt endet nie von selbst; steht das Auto 30 Minuten, erinnert die App.
- **Nachtragen:** Eine vergessene Fahrt trägst du im Reiter **Fahrten** mit **Fahrt erfassen** ein. Zeigt der Tachoabgleich fehlende Kilometer, bietet die App dort direkt „Fahrt nachtragen“ an.

## 5. Laden und Tanken unterwegs

Ob ein Stopp die Fahrt teilt, entscheidet die App nur über dein **Adressbuch**. Vom Auto oder aus dem Internet erfährt sie nicht, dass geladen oder getankt wird.

- **Gespeicherter Tank- oder Ladestopp** (Adresse mit dem Typ „Tank- oder Ladestopp“): Die Fahrt wird nur angehalten. Geht es innerhalb der Pause weiter (Laden Standard 90 Minuten, Tanken kürzer), bleibt es eine Fahrt mit Zwischenstopp „Laden“ oder „Tanken“.
- **Unbekannter Ort:** Nach 5 Minuten Stillstand endet die Fahrt, die Weiterfahrt ist eine neue Fahrt. Gehst du an einer unbekannten Tankstelle in den Shop, kann die Fahrt schon nach etwa 3 Minuten enden, weil das Handy den Beacon nicht mehr sieht. Kilometer und Orte stimmen trotzdem. Die Prüfliste schlägt vor, beide Teile zusammenzuführen und den Ort als Tank- oder Ladestopp zu speichern. Danach kennt die App ihn.
- **Tipp:** Häufig genutzte Ladesäulen und Tankstellen gleich vor Ort unter **Mehr → Adressen** mit „Aktuelle Position“ speichern.

## 6. Tachoabgleich und Verteilen

GPS misst Strecken nie ganz genau. Deshalb gleichst du regelmäßig mit dem Tacho ab:

- Einmal im Monat oder wenn die App erinnert, den Tachostand unter **Mehr → Kilometerabgleich** eintragen.
- Kleine Abweichungen bis 1 % (mindestens 2 km) sind normale Messabweichungen.
- **Verteilen** rechnet die Abweichung anteilig auf die erkannten Fahrten seit dem letzten Abgleich um. Die Kilometerkette schließt dann lückenlos an den Tacho an.
- Am Monatsende schließt du den Monat unter **Mehr → Monatsabschluss** ab. Danach lassen sich die Fahrten dieses Monats nicht mehr ändern, nur noch stornieren und neu erfassen.

## 7. Berichte und Export

Einen schnellen Überblick gibt der Reiter **Statistiken**. Stellst du dort **Jahr** oder **Quartal** ein, zeigt ein Balken je Monat, wie viele Kilometer beruflich (blau), privat (grün) und noch nicht eingeordnet (grau) waren. Ein Tipp auf einen Monat zeigt diesen Monat.

Im Reiter **Export** erstellst du PDF, Excel (XLSX) und CSV. Das PDF ist zum Ausdrucken und Weitergeben, Excel zum Lesen und Rechnen. CSV ist reiner Text für andere Programme und zur Archivierung. Wählbar sind Zeitraum, Fahrzeug, Kategorien und Fahrer. Name und Anschrift für das Deckblatt trägst du unter **Mehr → Angaben für Berichte** ein. Sätze und Pauschalen für die Kostenberechnung stehen unter **Mehr → Pauschalen und Sätze**.

Der PDF-Bericht beginnt mit einem Deckblatt: Fahrzeug, Zeitraum, eine Zusammenfassung mit Kilometern und Beträgen je Art und die Tachoabgleiche. Danach folgen die Fahrten, nummeriert und nach Monaten mit Monatssumme. Am Ende steht das Änderungsprotokoll: Zu jeder Fahrt (gleiche Nr.) siehst du, wann was geändert wurde, mit dem Wert vorher und nachher. Fahrten mit späteren Änderungen tragen in der Tabelle den Vermerk „nachträglich geändert“. Der Bericht ist A4 hochkant. Fahren mehrere Personen das Auto, steht bei jeder Fahrt ein Kürzel; was es bedeutet, steht auf dem Deckblatt und über der Fahrtentabelle.

Den fertigen Bericht speicherst du in einem Ordner deiner Wahl oder gibst ihn über das Teilen-Menü weiter, zum Beispiel an deine Steuerberatung.

## 8. Karte

- In der Fahrt siehst du die gefahrene Strecke auf einer kleinen Karte. Antippen öffnet sie groß, mit zwei Fingern zoomst du.
- Das Kartensymbol im Reiter **Fahrten** zeigt alle Fahrten eines Monats.
- Das Kartensymbol unter **Mehr → Adressen** zeigt deine Adressen mit ihrem Radius. Langes Drücken auf die Karte legt eine neue Adresse an.
- Die Karte kommt von OpenStreetMap. Ohne Netz siehst du Ausschnitte, die du schon einmal angesehen hast. Abschalten unter **Mehr → Einstellungen → Kartenkacheln laden**; dann zeigt die Karte Strecken und Adressen auf neutralem Hintergrund.

## 9. Datensicherung und Verschlüsselung

Alle Daten liegen nur auf deinem Handy. Geht es verloren, sind sie ohne Sicherung weg.

- **Automatische Sicherung:** **Mehr → Datensicherung → Automatische Sicherung → Ordner wählen.** Am besten ein Ordner in Google Drive, OneDrive oder auf einer SD-Karte. Die App sichert dann täglich und behält die letzten 14 Sicherungen (einstellbar). Gab es 7 Tage keine Sicherung oder schlägt sie fehl, meldet sie sich.
- **Von Hand sichern** legt jederzeit zusätzlich eine Sicherung an.
- **Verschlüsseln:** Schalter **Sicherungen verschlüsseln**, Passwort zweimal eingeben. Die Dateien enden dann auf `.fbsich`. Ohne das Passwort lässt sich eine verschlüsselte Sicherung nicht wiederherstellen. Niemand kann es zurücksetzen.
- **Wiederherstellen:** **Mehr → Datensicherung → Wiederherstellen** und die Datei (`.zip` oder `.fbsich`) wählen.

Vor jedem Update legt die App automatisch eine Sicherung an.

## 10. Neues Fahrtenbuch beginnen

Hast du zuerst Probefahrten gemacht und willst jetzt richtig anfangen: **Mehr → Datensicherung → Neues Fahrtenbuch beginnen**.

- Es entfernt alle Fahrten. Fahrzeuge, Fahrer, Kategorien, Adressen, Einstellungen und Beacon bleiben.
- Das geht nur, solange noch kein Monat abgeschlossen ist.
- Vorher speichert die App eine Sicherung; aus ihr holst du die alten Daten jederzeit zurück.
- Danach den aktuellen Tachostand eintragen. Er ist der Startpunkt der Kilometerkette.

## 11. Handy wechseln oder verkaufen

**Neues Handy:** Auf dem alten Handy eine Sicherung anlegen (oder die letzte automatische Sicherung nehmen) und auf dem neuen Handy unter **Mehr → Datensicherung → Wiederherstellen** einspielen. Liegt der Sicherungsordner in der Cloud, findest du die Datei dort direkt. Danach auf dem neuen Handy den Sicherungsordner neu wählen, gegebenenfalls die Verschlüsselung wieder einschalten und den Beacon unter **Mehr → Beacon** neu koppeln.

**Handy verkaufen oder weitergeben:**

1. Eine Sicherung anlegen und vom Handy wegkopieren, etwa auf den PC. Fahrtenbücher musst du aufbewahren, in Deutschland in der Regel 10 Jahre, in Österreich 7 Jahre.
2. Die App deinstallieren. Android löscht dabei alle Daten der App vollständig: Fahrten, Adressen, Einstellungen, Aufzeichnungen und die Beacon-Kopplung. Es gibt keine versteckte Kopie in der Google-Cloud.
3. Eigene Sicherungs- und Exportdateien löschen, die du selbst auf dem Handy abgelegt hast (zum Beispiel im Download-Ordner).
4. Das Handy auf Werkseinstellungen zurücksetzen.

## 12. Fehler melden

Fehlt eine Fahrt, ist sie geteilt, beginnt oder endet sie falsch, oder stürzt die App ab:

1. **Mehr → Fehler melden**
2. Zeitraum wählen, am besten so, dass die betroffene Fahrt drin ist, und kurz beschreiben, was passiert ist.
3. Im Teilen-Menü E-Mail wählen. Die Adresse **support@achimwegner.com** ist schon eingetragen.

Am besten am selben Tag melden. Der Bericht enthält Gerät, App-Version, Einstellungen, das Protokoll der Erkennung und die Signalaufzeichnungen des Zeitraums. Das Fahrtenbuch selbst, Adressen, Namen und Kennzeichen sind nicht enthalten. Orte sind standardmäßig unkenntlich gemacht; Strecken und Geschwindigkeiten bleiben gleich, der Fehler lässt sich also trotzdem nachvollziehen.

Ich werte Berichte auch mit einer KI aus (Claude von Anthropic). Möchtest du das nicht, schreib es in die Beschreibung. Mehr dazu in der [Datenschutzerklärung](DATENSCHUTZ.md), Abschnitt 6.

## 13. Häufige Fragen

**Braucht die App Internet?** Nein. Ins Internet geht sie nur für die Adressauflösung, die Kartenkacheln und die Update-Prüfung. Adressauflösung und Kartenkacheln schaltest du unter **Mehr → Einstellungen** ab, die Update-Prüfung unter **Mehr → Über die App**. Deine Fahrten verlassen das Handy nie von selbst.

**Kostet die App Akku?** Wenig. Zwischen den Fahrten wartet sie, bis Android den Beacon meldet. GPS läuft nur während einer Fahrt.

**Warum kann ich eine Fahrt nicht löschen?** Ein ordnungsgemäßes Fahrtenbuch darf keine Einträge verlieren. Falsche Fahrten stornierst du; sie bleiben sichtbar markiert und zählen nicht mit.

**Die Kilometer weichen vom Tacho ab.** Das ist normal, GPS misst etwas anders als der Tacho. Trag regelmäßig den Tachostand ein und nutze **Verteilen** (Abschnitt 6).

**Eine Fahrt fehlt.** Sieh im Statusbalken nach, ob die Erkennung grün ist. Trag die Fahrt nach (Abschnitt 4) und melde den Fehler am selben Tag (Abschnitt 12).

**Ich fahre einen Mietwagen.** Starte die Fahrt von Hand (Abschnitt 4) und leg das Auto unter **Mehr → Fahrzeuge** an.

**Ersetzt die App eine Steuerberatung?** Nein. Sie hilft dir, ein Fahrtenbuch zu führen. Ob es steuerlich anerkannt wird, entscheidet das Finanzamt.
