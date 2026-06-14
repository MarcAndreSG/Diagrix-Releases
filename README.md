# Diagrix – Releases

Dies ist das **Download-Repository** für [Diagrix](https://www.diagrixmac.com) – die
native Planungs-App für macOS. Hier liegen ausschließlich die fertigen App-Pakete
(Releases). **Quellcode ist hier bewusst nicht enthalten.**

> 🌐 Alle Infos, Screenshots und Anleitungen: **[www.diagrixmac.com](https://www.diagrixmac.com)**

## Download

Die jeweils neueste Version findest du in der
**[Releases-Übersicht »](https://github.com/MarcAndreSG/Diagrix-Releases/releases/latest)**
oder direkt auf der Projektwebseite [www.diagrixmac.com](https://www.diagrixmac.com).

Lade dort die Datei `Diagrix-<Version>.zip` herunter.

## Installation

1. ZIP herunterladen und entpacken – du erhältst `Diagrix.app`.
2. Die App in den Ordner **Programme** ziehen.
3. **Beim ersten Start:** Rechtsklick auf `Diagrix.app` → **Öffnen** und im Dialog
   erneut **Öffnen** bestätigen.

> **Warum dieser Zwischenschritt?**
> Diagrix ist eine kostenlose, nicht-kommerzielle App und daher zwar signiert, aber
> nicht von Apple notarisiert. macOS zeigt beim allerersten Öffnen deshalb eine
> Warnung. Über *Rechtsklick → Öffnen* startest du die App einmalig manuell –
> danach öffnet sie sich wie jede andere App per Doppelklick.
> Eine bebilderte Anleitung gibt es auf
> [www.diagrixmac.com](https://www.diagrixmac.com).

## Prüfsumme überprüfen (optional)

Zu jedem Release ist eine **SHA-256-Prüfsumme** angegeben. So vergleichst du sie nach
dem Download im Terminal:

```sh
shasum -a 256 Diagrix-1.0.0.0.zip
```

Der ausgegebene Wert muss exakt mit der im jeweiligen Release angegebenen Prüfsumme
übereinstimmen.

## Systemvoraussetzungen

- macOS 14 (Sonoma) oder neuer

## Links

- 🌐 Projektwebseite: **[www.diagrixmac.com](https://www.diagrixmac.com)**
- 📦 Alle Versionen: [Releases](https://github.com/MarcAndreSG/Diagrix-Releases/releases)
