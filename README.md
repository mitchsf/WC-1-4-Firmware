# WordClock 1-4

Firmware for the WordClock family of alphanumeric display clocks by [Angry Electrons](https://angryelectrons.com). Displays randomly selected words from a user-editable library, interspersed with the time and date.

Clocks are available for purchase at [Stocks Clocks](https://stocksclocks.com/index.php/word-clocks-angry-electrons/).

---

## Hardware

Available in multiple configurations:

- **Display types:** Alphanumeric LED (.8" or 2.3") type 1 and 2, VFD type 3, B7971 Nixie tubes, type 4
- **Display widths:** 6, 8, and 16 characters
- **Models:** WordClock 1-6, 1-8, 1-16, 2-6, 2-8, 2-16, 3-6, 3-8, 3-16, 4-6, 4-8

---

## Features

- Randomly displays words from an SD card library every 5 seconds
- Time and date display at user-selectable intervals (always, 60s, 30s, 15s)
- NTP or GPS time source
- Up to five simultaneous word libraries
- Optional expletive file with three levels (mild / medium / strong)
- Over 150,000 English words included; additional libraries with 30,000+ words in several languages
- Word groups up to 64 characters; longer groups scroll automatically
- Proverbs and Klingon libraries included
- RGB LED backlight with multiple effects and library indicator mode
- Three override modes (dim, sleep, time-only) by time range and day type
- Light sensor support for automatic brightness adjustment
- OTA (over-the-air) firmware updates
- Web browser configuration via built-in access point
- DST and UTC offset support for worldwide use
- Word transitions: slide, energize, or random

---

## Configuration

On first power, the clock starts in Access Point mode. Connect to the Wi-Fi network **WordClock-[model]** from any device, then navigate to `192.168.4.1` in a browser to configure Wi-Fi, NTP server, libraries, display options, and override schedules.

---

## Library Files

All library files are plain text on the SD card, editable with any text editor:

| Extension | Purpose |
|---|---|
| `.wds` | Word file — one word group per line |
| `.fnt` | Font file — 16-bit segment bitmap per ASCII character |
| `.msg` | Message file — required for Library 1 only |
| `.xpl` | Expletive file — optional, word\|level format |

---

## Buttons

| Button | Action |
|---|---|
| SW1 single press | Cycle expletive level |
| SW1 double press | Cycle clock mode |
| SW2 single press | Cancel override temporarily |
| SW2 triple press | Light sensor calibration |
| SW1 hold (10s) | OTA firmware update |
| SW2 hold (5s) | Restart to AP mode |
| SW1+SW2 at power-on | Factory reset |

---

## License

Copyright © 2026 Mitchell Feig, d/b/a Angry Electrons. All Rights Reserved.
