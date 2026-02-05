# MBrew Datenschutzrichtlinie

Geltungsdatum: 2026-01-04

## Einleitung
MBrew ist eine lokale Desktop‑Anwendung auf Basis von Electron und Vue zur Verwaltung von Craft‑Beer‑Rezepten und Unterstützung beim Brauprozess. Wir legen großen Wert auf den Datenschutz und verarbeiten Daten nach Möglichkeit lokal. Es findet kein Upload oder Teilen von Nutzerdaten mit entfernten Servern statt.

## Datenerhebung und ‑nutzung
- Es werden keine personenbezogenen identifizierbaren Informationen erhoben (Name, E‑Mail, Adresse, Telefonnummer etc.).
- Es werden keine Finanz‑, Gesundheits‑, Kontakt‑ oder Foto/Dokument‑Daten sowie keine nutzergenerierten Inhalte erhoben.
- Es werden keine Gerätekennungen (z. B. Werbe‑IDs), Standortdaten oder sensiblen Informationen erhoben.
- Geschäftsdaten wie Rezepte, Zutaten, Inventar und Brauprotokolle werden lokal auf dem Gerät des Nutzers gespeichert (App‑Datenverzeichnis oder vom Nutzer gewählte Dateipfade für Backup/Import/Export).
- Die App übermittelt diese Daten nicht an Entwickler‑Server oder Drittanbieter‑Dienste.

## Drittanbieter und Netzwerk
- Die App kann externe Dokumentation oder Projektseiten aufrufen sowie Updates per HTTPS/TLS prüfen. Es werden keine personenbezogenen Daten erhoben oder analysiert.
- Die App integriert keine Analyse‑SDKs von Drittanbietern (z. B. Google Analytics, Sentry).
- Sämtliche externe Zugriffe dienen der reinen Anzeige/Versionsprüfung und beinhalten keinen Upload von Nutzerdaten.

## Tracking‑Erklärung
- Die App betreibt kein nutzerübergreifendes Tracking über Websites oder Apps hinweg.
- Es werden keine Werbe‑ oder Drittanbieter‑Tracking‑Technologien verwendet.
- Es werden keine Daten zu Werbe‑ oder Profilierungszwecken an Dritte weitergegeben.

## Berechtigungen und Sandbox
- Dateizugriff: Lese/Schreibzugriff nur, wenn der Nutzer einen Pfad auswählt (konform mit macOS App‑Sandbox `files.user-selected.read-write`).
- Netzwerkzugriff: Wird verwendet, um externe Dokumente zu laden oder Updates zu prüfen (ohne Nutzerdaten).
- Die App fordert keinen Zugriff auf Kamera, Mikrofon, Kontakte oder Standort an.

## Datensicherheit
- Alle Daten werden lokal gespeichert.
- Backup/Import/Export erfolgt über JSON‑Dateien; Nutzer verwalten die Speicherorte selbst.
- Für die Netzwerksicherheit wird das systemeigene HTTPS/TLS verwendet; es wird keine eigene oder allgemeine Verschlüsselung implementiert.

## Datenschutz von Kindern
- Die App richtet sich an erwachsene Nutzer im Kontext der Braumanagement‑Szenarien und ist nicht für Kinder konzipiert.
- Es werden keine personenbezogenen Daten von Kindern erhoben.

## Änderungen
- Bei Aktualisierung dieser Richtlinie wird eine neue Version auf der App‑Startseite oder in der Projektdokumentation veröffentlicht.
- Wesentliche Änderungen geben das Geltungsdatum und die Details der Änderung klar an.

## Kontakt
- Projekt‑Homepage: https://github.com/mimeoff/MBrew
- Support‑Kanal: Bitte melden Sie Probleme oder Vorschläge über GitHub Issues

