# 🐧 Linux Distro Exploration

> **Ziel:** Verschiedene Linux-Distributionen kennenlernen, um ggf. von Arch Linux zu wechseln und fundierte Empfehlungen geben zu können.

---

## 📋 Rahmenbedingungen

|Eigenschaft|Details|
|---|---|
|**Hardware**|Intel i5 7700, RTX 3050 Laptop GPU, 32GB DDR4, 512GB NVMe|
|**Test-Methode**|Vollinstallation, mind. ein paar Tage Nutzung pro Distro|
|**Aktueller Daily**|Arch Linux (Main PC) + Windows 11 Dual Boot|
|**Ventoy USB**|✅ Vorhanden|
|**Vorherige DEs**|KDE Plasma 6, Hyprland|

---

## 🎯 Bewertungskriterien

|Kriterium|Priorität|
|---|---|
|Performance|⭐⭐⭐ Hoch|
|Gaming|⭐⭐⭐ Hoch|
|Software-Verfügbarkeit|⭐⭐⭐ Hoch|
|Stabilität|⭐⭐ Mittel|
|Benutzerfreundlichkeit|⭐⭐ Mittel|
|Community|⭐ Niedrig|

---

## 📊 Übersichtstabelle

| Distro                        | DE getestet             | Performance | Gaming | Software | Stabilität | Usability | Gesamtnote | Status        |
| ----------------------------- | ----------------------- | :---------: | :----: | :------: | :--------: | :-------: | :--------: | ------------- |
| [Arch Linux](Arch%20Linux.md) | Hyprland; KDE Plasma 6; |   9.5/10    | 8.5/10 |  10/10   |    9/10    |   9/10    |    9/10    | ✅️ Abgecheckt |
| [CachyOS](CachyOS.md)         | Niri                    |      –      |   –    |    –     |     –      |     –     |     –      | ☑️ Aktuell    |
| [Debian](Debian.md)           |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |
| [Fedora](Fedora.md)           |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |
| [Linux Mint](Linux%20Mint.md) |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |
| [OpenSUSE](OpenSUSE.md)       |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |
| [Ubuntu](Ubuntu.md)           |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |
| [ZorinOS](ZorinOS.md)         |                         |      –      |   –    |    –     |     –      |     –     |     –      | 🔲 Ausstehend |

> Bewertung: 1–10 Punkte pro Kriterium

---

## 🖥️ Desktop Environments – Übersicht

|DE|Getestet auf|Ersteindruck|Wayland?|Gaming-tauglich|Notiz|
|---|---|:-:|:-:|:-:|---|
|GNOME||–|✅|–||
|Cinnamon||–|⚠️ (X11 primär)|–||
|Niri||–|✅ only|–|Compositor, kein vollst. DE|
|KDE Plasma 6|(bekannt)|–|✅|✅|Bereits genutzt|
|Hyprland|(bekannt)|–|✅ only|–|Bereits genutzt|

---

## 🔖 Distro-Seiten

- [Arch Linux (***current distro***)](Arch%20Linux.md)
- [CachyOS](CachyOS.md)
- [Debian](Debian.md)
- [Fedora](Fedora.md)
- [Linux Mint](Linux%20Mint.md)
- [OpenSUSE](OpenSUSE.md)
- [Ubuntu](Ubuntu.md)
- [ZorinOS](ZorinOS.md)

---

## 📝 Allgemeine Notizen

<!-- Übergreifende Beobachtungen, die mehrere Distros betreffen -->
#### Probleme:
   Das Größte Problem bisher wäre, das ich immernoch manchmal zu Windows wechseln muss für zB. Davinci Resolve (codecs und kann zwar mit der Studio version gefixt werden aber ich will keine 300€ dafür ausgeben), oder Proton fehlern bei zB Dark Souls 2 mit dem Controller.

#### Notizen:
   Ich will auch noch XORG ausprobieren, um zu schauen wie der kompetitor von Wayland ist.
### Nvidia RTX 3050 Erfahrungen

<!-- Hier allgemeine Nvidia-Treiber Erfahrungen über Distros hinweg eintragen -->

### Ventoy Kompatibilität

<!-- Boot-Probleme oder Besonderheiten beim Booten via Ventoy -->

---

_Letztes Update: 20.02.2026_

Biggest Problem would be that I still need to switch back to Windows sometimes for "Davinci Resolve (mp4 codecs)", "Dark Souls 2". everything else worked great with Wine, or Proton.