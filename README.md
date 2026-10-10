# CASIO Projector Firmware Update Prank

🇬🇧 [English](#english) · 🇩🇪 [Deutsch](#deutsch)

**Live: https://xboggs.github.io/casio/**

---

## English

A harmless prank screen that looks like a **Casio projector stuck in recovery mode during a firmware update**. Mirror it to a Casio projector (for example at school) and watch the room wonder what happened.

It is a plain HTML page that works on very old devices, including an **iPad with iOS 9.3.6**.

### Use it

1. Open **https://xboggs.github.io/casio/** in Safari.
2. Tap **Share → Add to Home Screen** to install it as an app.
3. Start it from the home screen (fullscreen) and mirror the screen to the projector.

Tip: set **Auto-Lock** to *Never*, otherwise the screen turns off.

### What it shows

1. Black screen with the blue **CASIO** logo, `RECOVERY MODE` below it.
2. `FIRMWARE UPDATE - VER. 1.5d` with a thin progress bar and a percentage.
3. The bar starts at **10%** and reaches **45% within 3 minutes**, then slows down and reaches **100% after 1 hour 20 minutes** in total.
4. At 100% a grey dialog appears: *"Please turn Projector off, wait 1 Minute, then turn back on"*. That is the cue to disconnect.

Nothing is saved: every time the app is opened, it starts again at 10%.

### Files

| File | Purpose |
| --- | --- |
| `index.html` | Tiny loader that loads `app.html` with a fresh timestamp, so iOS cannot show an outdated cached copy. |
| `app.html` | The actual prank screen. The timing is set by `TOTAL` and `PHASE1` at the top of its script. |

### Disclaimer

This is a joke project for fun. It does **not** touch any projector and does **not** perform a real firmware update. Please use it responsibly: do not disrupt exams, presentations or other people's real work. This project is not affiliated with Casio. CASIO is a trademark of Casio Computer Co., Ltd.

---

## Deutsch

Ein harmloser Prank-Screen, der aussieht wie ein **Casio-Beamer im Recovery-Modus während eines Firmware-Updates**. Spiegle ihn auf einen Casio-Beamer (zum Beispiel in der Schule) und schau zu, wie sich der Raum fragt, was passiert ist.

Es ist eine einfache HTML-Seite, die auch auf sehr alten Geräten läuft, zum Beispiel auf einem **iPad mit iOS 9.3.6**.

### Benutzen

1. **https://xboggs.github.io/casio/** in Safari öffnen.
2. Auf **Teilen → Zum Home-Bildschirm** tippen, um sie als App zu installieren.
3. Die App vom Home-Bildschirm starten (Vollbild) und den Bildschirm auf den Beamer spiegeln.

Tipp: **Automatische Sperre** auf *Nie* stellen, sonst geht das Display aus.

### Was angezeigt wird

1. Schwarzer Bildschirm mit blauem **CASIO**-Logo, darunter `RECOVERY MODE`.
2. `FIRMWARE UPDATE - VER. 1.5d` mit dünner Fortschrittsleiste und Prozentanzeige.
3. Die Leiste startet bei **10%** und erreicht **45% innerhalb von 3 Minuten**, wird dann langsamer und erreicht insgesamt nach **1 Stunde 20 Minuten 100%**.
4. Bei 100% erscheint ein graues Fenster: *"Please turn Projector off, wait 1 Minute, then turn back on"*. Das ist das Zeichen, sich zu trennen.

Es wird nichts gespeichert: Bei jedem Öffnen der App beginnt es wieder bei 10%.

### Dateien

| Datei | Zweck |
| --- | --- |
| `index.html` | Kleiner Lade-Rahmen, der `app.html` mit frischer Zeitmarke lädt, damit iOS keine veraltete Kopie aus dem Cache zeigt. |
| `app.html` | Der eigentliche Prank-Screen. Die Zeiten stehen als `TOTAL` und `PHASE1` am Anfang des Skripts. |

### Hinweis

Dies ist ein Spaßprojekt. Es verändert **keinen** Beamer und führt **kein** echtes Firmware-Update durch. Bitte nutze es verantwortungsvoll: keine Prüfungen, Präsentationen oder die echte Arbeit anderer stören. Das Projekt steht in keiner Verbindung zu Casio. CASIO ist eine Marke der Casio Computer Co., Ltd.
