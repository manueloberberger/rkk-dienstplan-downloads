# RKK Dienstplan · Downloads

Fertige macOS-App für den persönlichen Incode-Dienstplan – mit Kalender, Statistiken, Exporten und optionalen Telegram-Meldungen.

**Version 1.8.2 · macOS 14+ · Intel und Apple Silicon**

**[Aktuelle App herunterladen](https://github.com/manueloberberger/rkk-dienstplan-downloads/releases/latest)** · [Alle Veröffentlichungen](https://github.com/manueloberberger/rkk-dienstplan-downloads/releases)

## Installation

1. Die Universal-ZIP aus dem gewünschten Release herunterladen; eine GitHub-Anmeldung ist für öffentliche Downloads nicht erforderlich.
2. Entpacken und eine bereits laufende ältere Version beenden.
3. **RKK Dienstplan.app** nach **Programme** ziehen und öffnen.
4. Bei einer macOS-Blockierung die App nach Prüfung unter **Systemeinstellungen → Datenschutz & Sicherheit** freigeben.

Das Bundle enthält seine Laufzeit. Eine zusätzliche Python-Installation oder die separate Incode-CLI ist nicht nötig. Intel wurde tatsächlich getestet; Apple Silicon ist enthalten und statisch geprüft, ein echter Hardwarelauf steht aus.

Aktuelle Builds verwenden eine dauerhafte Signieridentität. Sie sind nicht Apple-notarisiert. Ältere Releases können noch ad-hoc signiert sein.

## Einstieg und Updates

Zum Ausprobieren gibt es Beispieldaten. Eigene Dienste benötigen ein berechtigtes Incode-Konto. Zugangsdaten und persönliche Dienstplandaten werden nicht mitgeliefert.

Unter **Einstellungen → App-Updates** beziehungsweise **Nach App-Updates suchen …** lassen sich neue Versionen suchen und automatische Prüfungen aktivieren. Die Installation wird bestätigt. Sparkle prüft den signierten Updateweg; private Signierschlüssel werden nicht veröffentlicht.

## Inhalt dieses Repositories

Hier liegen Downloadinformationen und Releases mit fertigen App-Paketen sowie dem Sparkle-Updatefeed. Der Entwicklungsquellcode wird getrennt privat verwaltet. Hinweise zu den enthaltenen Fremdbibliotheken liegen im App-Bundle.

Für Fehlerberichte App-Version, macOS-Version und eine Beschreibung der Schritte angeben. Zugangsdaten, Dienstpläne, Kontaktdaten und unbereinigte Logs nicht öffentlich posten.

Version 1.8.2 beendet App-eigene Abrufe und Hilfsprozesse beim Beenden. Der separat eingerichtete Telegram-Botdienst bleibt aktiv.
