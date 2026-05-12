[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/ldb) ![Build](https://github.com/0x007e/ldb/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `LDB` - LED Development Board

The `LDB` is a board with 10 LEDs and a 7-Segment display with a [MC14543](#additional-information) or any other `BCD/7-Segment` converter that meets the pin requirements. The board itself can be driven from `3` to `15V`. The board offers the possibility to convert a bcd number to a 7-segment display or control a set of leds by driving buttons, switches or any other logic board elements.

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/20?progress_color=00ff00&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/ldb/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30142/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/ldb/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30142/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/ldb/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| PCB       | [zip](https://github.com/0x007E/ldb/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/ldb/releases/latest/download/kicad.tar.gz) | KiCAD/Gerber/BoM/Drill files |
| Mechanical | [zip](https://github.com/0x007E/ldb/releases/latest/download/freecad.zip) / [tar](https://github.com/0x007E/ldb/releases/latest/download/freecad.tar.gz) | FreeCAD/Housing and exported step/stl files |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/ldb/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/ldb/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link                                                       | Description                                                   |
|:----------:|:----------------------------------------------------------:|:--------------------------------------------------------------|
| MC14543    | [pdf](https://www.onsemi.com/pdf/datasheet/mc14543b-d.pdf) | BCD-to-Seven Segment Latch/Decoder/Driver for Liquid Crystals |

---

R. GAECHTER
