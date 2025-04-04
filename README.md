# Aquarius<sup>+</sup> PCBs
Development of PCBs for the **Aquarius<sup>+</sup>** platform

## Introduction
The **Aquarius<sup>+</sup>** was developed as an open-source platform, including the hardware that comprises the system. To accomplish this and to make tools for the development and manufacture of the platform as accessible as possible, [KiCAD](https://github.com/KiCad/kicad-source-mirror) is used for PCB development, as it is a free, open source tool that has anyone can learn and use.

## Releases
Releases from this repo are by model/PCB and are geared specifically for manufacturing rather than PCB development.

> For example, if you want to make your own **Aquarius<sup>+</sup> Mini**, you would go to the [**Releases**](https://github.com/1stage/aquarius-plus-pcbs/releases) section, find the newest release for an **Aquarius<sup>+</sup> Mini**, and download it.

The **Source code (zip)** or **Source code (tar.gz)** payload will consist of the following components:
 * Gerber files, compressed in ZIP format (includes PCB, Drill, and Map files)
 * PDFs of the SCHEMATIC and PCB
 * BOM (Bill of Materials) and CPL1 (Component Placement Layout) files in XLSX (MS Excel) format, organized for JLCPCB manufacturing.
 * Release notes and other instructions in TXT format

## Development
If you want to explore how the **Aquarius<sup>+</sup>** is designed using KiCAD, you will need to Clone or Fork this repo to your local system. From there you can review and experiment with the schematic, PCB, and other files within the KiCAD environment.
