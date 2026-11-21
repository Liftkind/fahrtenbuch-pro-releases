# Fahrtenbuch Pro – Downloads

Hier gibt es die Android-App **Fahrtenbuch Pro** zum Herunterladen. Die App erkennt Fahrten automatisch über einen Beacon im Auto und führt ein Fahrtenbuch mit Kilometerkette, Tachoabgleich, Statistiken und Export. Alle Daten bleiben auf dem Handy.

Der Quellcode liegt nicht hier. Dieses Repository enthält nur die fertigen Versionen.

## Herunterladen

Unter [Releases](../../releases) die neueste Version öffnen und unter „Assets“ die Datei `fahrtenbuch-pro-<version>.apk` herunterladen. Mindestens Android 13, getestet ab Android 14.

Wie du die App installierst und einrichtest, steht in der [Anleitung für Tester](ANLEITUNG_TESTER.md).

Was die App ins Internet schickt und wie Fehlerberichte behandelt werden, steht in der [Datenschutzerklärung](DATENSCHUTZ.md).

Spätere Updates meldet die App selbst.

## Prüfsumme

Zu jeder APK gehört eine Datei `.sha256`. Die App prüft sie bei Updates automatisch. Von Hand unter Windows:

```
Get-FileHash fahrtenbuch-pro-<version>.apk -Algorithm SHA256
```

## Hinweis

Testversion (Beta). Die App ersetzt keine Steuerberatung.
