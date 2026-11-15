# NOCTA Desktop

**Deine Musik. Dein eigener Klang.** Eigene Musikbibliothek, nativer Equalizer, Sessions und ein persönlicher Musikraum für Windows.

[Website](https://tysoncca.github.io/nocta-downloads/) · [2.0.0 Vorschau herunterladen](https://github.com/TysonCCA/nocta-downloads/releases/download/v2.0.0/NOCTA-Setup.exe) · [Installation & Hilfe](https://tysoncca.github.io/nocta-downloads/installieren.html) · [Releases](https://github.com/TysonCCA/nocta-downloads/releases)

## Aktuell: 2.0.0 Vorschau

- Eigene Musikordner, Metadaten/Cover, Alben, Suche und Sessions ohne Spotify-Anmeldung.
- Nativer 48-kHz-Stereo-Audiopfad mit Bass-/Mitten-/Höhen-EQ, Presets, Crossfade und optionalem Pegelabgleich.
- Fortlaufende lokale Queue, Wiederaufnahme, Windows-Mediensteuerung und Mini-Player mit Lautstärke.
- Spotify-Integration mit Clarg Radio, fortlaufender Queue und nachvollziehbaren Suchgründen.
- Listening Loft, Theme Studio, Sound-DNA, Zeitreise und Sammlungs-/Session-Werkzeuge.

Windows 10 ab Version 2004 / Windows 11, **x64**. Installer: **261.236.736 Bytes (249,1 MiB)**.

SHA-256 von NOCTA-Setup.exe:

146A9DAF3183E294B85FFA6D2E0D8FA09672D4A9CE07D5C2CF04E8C9B5B78BEC

Der Build ist **unsigniert**. Windows kann den Start melden oder blockieren. Schutzfunktionen nicht deaktivieren. Eine Prüfsumme ersetzt keine Herausgebersignatur.

Native Tests mit generierten WAV-Dateien prüfen die tatsächliche PCM-Verarbeitung; Browserprüfungen verwenden simulierte Dienste. Reale Audiohardware, Windows-Medien-Flyout, Langzeitbetrieb und unabhängige Installation stehen noch aus. Codec-Unterstützung teilweise Windows-abhängig; keine universelle Gapless-Zusage.

2.0.0 ist als **Prerelease** gekennzeichnet. [1.2.0 bleibt der bisherige stabile Release](https://github.com/TysonCCA/nocta-downloads/releases/tag/v1.2.0); die Vorschau wird nicht als neuester stabiler Release ausgerollt. 1.2.0 enthält die neuen lokalen Audiofunktionen noch nicht und ist ebenfalls unsigniert.

## Einrichtung

Lokale Musik benötigt kein Spotify-Konto. Spotify-Wiedergabe im integrierten Player benötigt Premium und gegebenenfalls eine Kontofreigabe im Entwicklungsmodus. Der direkte lokale EQ benötigt kein APO; der Spotify-/System-EQ verwendet die separate Equalizer-APO-Geräteeinrichtung. KI-Gespräch, Stimme und Bildbearbeitung benötigen einen selbst eingerichteten API-Zugang. Es gibt kein Hosting für gemeinsame Online-Besuche im Loft.

[Vollständige Einrichtung](https://tysoncca.github.io/nocta-downloads/installieren.html) · [Daten & Dienste](https://tysoncca.github.io/nocta-downloads/datenschutz.html) · [Fehler melden](https://github.com/TysonCCA/nocta-downloads/issues)

## Dieses Repository

Hier liegen die **Downloadwebsite und Release-Binärdateien**, nicht der native App-Quellcode. Die Website wird aus docs/ über GitHub Pages ausgeliefert. Keine Laufzeitabhängigkeiten, externen Webfonts oder eigenen Tracking-Skripte. Statische Dateien lokal per HTTP bereitstellen, um die Seite anzusehen.

App-Ansichten zeigen simulierte Beispieldaten. Die EQ-Skizze auf der Website spielt keine Musik und verändert keinen Systemsound. Bewegungen respektieren die Betriebssystemeinstellung für reduzierte Animationen. Webfont-Lizenzen liegen unter docs/assets/fonts/; native Abhängigkeiten mit Lizenzen und passendem TagLibSharp-Quellarchiv im App-Paket.
