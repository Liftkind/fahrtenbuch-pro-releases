# RoadScript Fahrtenbuch – Downloads

*Einsteigen. Losfahren. Eingetragen.*

Hier gibt es die Android-App **RoadScript Fahrtenbuch** zum Herunterladen (bis Version 0.11.1 hieß sie „Fahrtenbuch Pro“). Die App erkennt Fahrten automatisch über einen Beacon im Auto und führt ein Fahrtenbuch mit Kilometerkette, Tachoabgleich, Statistiken und Export. Alle Daten bleiben auf dem Handy.

Der Quellcode liegt nicht hier. Dieses Repository enthält nur die fertigen Versionen.

## Herunterladen

Auf dem Handy diesen Link öffnen, er lädt immer die neueste Version:
https://github.com/Liftkind/fahrtenbuch-pro-releases/releases/latest/download/roadscript.apk

Alternativ unter [Releases](../../releases) die neueste Version öffnen und unter „Assets“ die Datei `roadscript.apk` herunterladen. Mindestens Android 13, getestet ab Android 14.

Wie du die App installierst und einrichtest, steht in der [Anleitung für Tester](ANLEITUNG_TESTER.md). Wie du im Alltag mit ihr arbeitest, erklärt die [Hilfe](HILFE.md).

Was die App ins Internet schickt und wie Fehlerberichte behandelt werden, steht in der [Datenschutzerklärung](DATENSCHUTZ.md).

Spätere Updates meldet die App selbst.

## Prüfsumme

Zu jeder Version gehört eine Datei `fahrtenbuch-pro-<version>.apk.sha256`. Die App prüft sie bei Updates automatisch. Von Hand unter Windows:

```
Get-FileHash fahrtenbuch-pro-<version>.apk -Algorithm SHA256
```

`roadscript.apk` ist dieselbe Datei wie `fahrtenbuch-pro-<version>.apk` der jeweiligen Version, nur mit festem Namen.

## Hinweis

Testversion (Beta). Ob das Finanzamt ein Fahrtenbuch anerkennt, entscheidet es im Einzelfall; kläre das bitte vorab mit deiner Steuerberatung. Die App ersetzt keine Steuerberatung.
