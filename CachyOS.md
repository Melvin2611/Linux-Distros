> **Basis:** Arch-based  
> **Paketmanager:** pacman  
> **Release-Modell:** Rolling Release 
> **Getestetes DE:** Niri  
> **Testzeitraum:** 20.02-2026 – [Datum bis]

---

## 📥 Installation

### Installationserfahrung

<!-- Wie einfach/kompliziert war die Installation? Grafisch, textbasiert? -->
Der LiveUSB bootet standardweise in eine KDE Plasma 6 umgebung, wodurch alles sehr nutzerfreundlich ist, dazu gibt er dir eine haufen an Anleitungen zur installation. und direkt als CachyOS Welcome Fenster noch nen kompletten GUI Installer.
Der Installer war unkompliziert und einfach durchzulaufen, und hat während der installation ein paar infos über das System genannt. Ich hatte nur ein WLAN Problem, wo der Installer leider nicht wieder aufpicken wollte wo er stehengeblieben war und sich dann festgehangen hat. Nach einem Neustart(PC Reboot nicht App) konnte ich die Installation problemlos fortsetzen

### Nvidia-Treiber Setup

<!-- Hat es out-of-the-box funktioniert? Manuelle Schritte nötig? -->

- [x] Treiber automatisch erkannt
- [x] Wayland funktioniert
- [x] Kein Screen Tearing

### Besonderheiten bei der Installation

<!-- Partitionierung, Bootloader, sonstige Auffälligkeiten -->
Das komplette KDE Environment war eigentlich schon funktionsfähig, und hatte lustigerweise sogar fastfetch mit im LiveUSB. Firefox war auch noch drin, womit man den LiveUSB theoretisch einfach schon so als Linux nutzen könnte (wäre aber nicht empfehlenswert)

---

## 🖥️ Desktop Environment

**DE:** Niri  
**Version:** 25.11-1
**Session:** [] Wayland    [ ] X11

### Ersteindruck

<!-- Optik, Responsivität, Standard-Layout -->
In der Installation auf der Fetplatte lief alles performant und schick, außerdem sah alles sehr smooth, und modern aus was ein guter plus punkt ist. leider finde ich die keybinds bis her nicht intuitiv, aber die will ich noch lernen bzw. anpassen.
Niri hat einen am anfang auch durch ein Setup geführt, um den Style direkt so anpassen zu können wie man es will.

### Anpassbarkeit

<!-- Wie gut lässt sich das DE konfigurieren? -->
### Wayland-Stabilität

<!-- Abstürze, Kompatibilitätsprobleme, Screen Sharing etc. -->

---

## ⚡ Performance

> Hardware: Intel i5 7700 | RTX 3050 Laptop | 32GB DDR4 | 512GB NVMe

| Metrik                        | Wert / Eindruck                                                                                   |
| ----------------------------- | ------------------------------------------------------------------------------------------------- |
| RAM-Verbrauch (Idle)          |                                                                                                   |
| Boot-Zeit                     | 7 - 15 sekunden um in das DE reinzukommen (bootmanager und SDDM sind mit in die Zeit eingegangen) |
| Allgemeine Reaktionsfähigkeit |                                                                                                   |
| CPU-Last (Idle)               |                                                                                                   |

### Notizen zur Performance

<!-- Subjektive Eindrücke, Vergleich zu Arch/KDE -->
Sehr schnell und noch kein Stocken bisher

---

## 🎮 Gaming

### Steam

- [ ] Steam installierbar
- [ ] Proton funktioniert
- [ ] GE Proton funktioniert
- [ ] Native Games laufen

### Getestete Spiele

| Spiel                  | Läuft? | Performance | Notiz |
| ---------------------- | :----: | :---------: | ----- |
| Hollow Knight Silksong |   –    |      –      |       |
| Cyberpunk 2077         |   –    |      –      |       |
| Minecraft              |        |             |       |

### GameMode / MangoHud

- [ ] GameMode verfügbar
- [ ] MangoHud verfügbar

### Allgemeine Gaming-Notizen

<!-- Treiber-Probleme, Wayland-Kompatibilität beim Gaming, etc. -->

---

## 📦 Software & Paketmanagement

### Paketquellen

- [ ] Offizielle Repos ausreichend
- [x] Flatpak support
- [ ] Snap support (falls relevant)
- [x] AUR-Equivalent / Third-party Repos

#### Infos:
- Snap nicht getestet da Irrelevant
- aufs AUR kann man zugreifen aufgrund dessen das es Arch basiert ist
- Pacman ist meiner Meinung nach leider nicht ganz ausreichend

### Software-Verfügbarkeit

<!-- Fehlende Programme, einfache Installation, PPA/COPR etc. -->
none
### Paketmanager-Erfahrung

<!-- Geschwindigkeit, Benutzerfreundlichkeit des Paketmanagers -->

pacman finde ich persönlich sehr Benutzerfreundlich, ich meine man muss kurz etwas lernen wie -Syu -S aber der rest ist auch Googlebar und schnell lernbar. und ansonsten -h funktioniert auch immer

---

## 🔒 Stabilität

- [ ] Keine unerwarteten Abstürze
- [ ] Updates problemlos
- [ ] Keine Paket-Konflikte

### Stabilitäts-Notizen

<!-- Bugs, Abstürze, kaputte Updates -->

---

## 👤 Benutzerfreundlichkeit

### Out-of-the-Box Erfahrung

<!-- Was funktioniert direkt, was muss man noch einrichten? -->

### Dokumentation & Problemlösung

<!-- Wie gut findet man Hilfe? Wiki, Foren, etc. -->
Eigentlich sofort und Problemlos. Es ist alles gut dokumentiert aufgrund vom Arch Wiki allein schon.

### Für Einsteiger geeignet?

<!-- Würdest du diese Distro einem Linux-Neuling empfehlen? -->
Es ist halt Arch, also schon in einigen Aspekten hart, aber man lernt dadurch meiner Meinung nach sehr sehr schnell. Was CachyOS auch noch gut macht, ist den Einstieg sehr unkompliziert, und nicht wirklich Fehleranfällich zu gestalten. Es ist nicht komplett Idioten Sicher, aber wenn jemand gut genug ist Minecraft mods von selbst zu installieren sollte CachyOS definitiv auch möglich sein zu nutzen. Man sollte aber definitv keine Angst vorm Terminal haben, da man das immer mal wieder braucht Ich würde sogar so weit gehen und sagen das man es eigentlich in so gut wie jeder sitzung mind. einmal nutzt (Nicht weil man es brauch sondern weil es die Erfahrung so sehr verbessert).

TL:DR Ja man könnte es Linux einsteigern empfehlen, aber nur wenn diese auch Technisches Hintergrund wissen haben.

---

## 👥 Community

<!-- Kurze Einschätzung: Aktiv? Hilfreich? Gute Docs? -->
Die Community ist Aktiv, Groß, Hilfreich, und man hat auch den Vorteil von der eigentlichen Arch Community, da alles Arch auch auf CachyOS bisher problemlos funktioniert hat.

---

## 📊 Bewertung

| Kriterium              | Note (1–10) | Kommentar                                |
| ---------------------- | :---------: | ---------------------------------------- |
| Performance            |             |                                          |
| Gaming                 |             |                                          |
| Software               |             |                                          |
| Stabilität             |             |                                          |
| Benutzerfreundlichkeit |    9/10     | Man muss etwas technisches Wissen haben. |
| Community              |    10/10    |                                          |
| **Gesamt**             |    **–**    |                                          |

---

## ✅ Fazit

### Was hat gut gefallen?

### Was hat nicht gefallen?

### Würde ich wechseln?

<!-- Ja / Nein / Vielleicht – und warum -->

### Empfehlung für Freunde?

<!-- Für wen würdest du diese Distro empfehlen? Einsteiger, Power User, Gamer? -->
Power User, Gamer.

---

_Getestet auf: Intel i5 7700 | RTX 3050 Laptop | 32GB DDR4 | 512GB NVMe_  
_Zurück zur [Übersicht](!Linux%20Documentation.md)_