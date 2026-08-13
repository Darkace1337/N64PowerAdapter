# N64PowerAdapter

A modern, universal replacement power supply for the Nintendo 64 using readily available, high-quality power modules.

This project includes the PCB design, schematic, and 3D-printable enclosure required to build a replacement for the original Nintendo 64 power supply. The supply accepts universal AC mains through an IEC C8 connector and provides the 12 V and 3.3 V rails required by the N64 through the original 6-pin power connector.

The design uses TRACO Power modules for the AC/DC and DC/DC conversion, keeping the power circuitry simple while providing an isolated and compact replacement for aging original power supplies.

## Requirements

**A sacrificial Nintendo 64 power adapter (official or third-party) is required for the original 6-pin console connector.**

The connector must be removed from the donor power supply and installed onto the replacement PCB.

## Bill of Materials

| Reference | Qty | Manufacturer | Part Number | Description |
|:---|---:|:---|:---|:---|
| PS1 | 1 | TRACO Power | TEL 10-2410WI | 10 W isolated DC/DC converter, 9–36 V input, 3.3 V / 2.7 A output |
| PS2 | 1 | TRACO Power | TMPW 25-112 | 25 W AC/DC converter, 12 V / 2.083 A output |
| C1 | 1 | KYOCERA AVX | TAJD476K025SNJ | 47 µF, 25 V, 10% tantalum capacitor |
| C2, C4 | 2 | Vishay | 05007-BR104AKU-J | 0.1 µF, 25 V, 10% MLCC |
| C5 | 1 | Vishay | 592D477X96R3C2T20H | 470 µF, 6.3 V, 10% tantalum capacitor |
| F1 | 1 | Eaton | C310T-SC-2-5-R-TR1 | 2.5 A, 250 V ceramic cartridge fuse |
| J1 | 1 | — | Amazon | C8 Panel Mount Plug, flange mount type |
| J3 | 1 | Nintendo / Donor PSU | — | Original N64 6-pin power connector |
| Screws-A | 3 | - | Amazon | M3 x 5 mm Button-head machine screws
| Screws-B | 4 | - | Amazon | M3 x 6 mm Countersunk self tapping screws
| Thread Inserts| 2 | - | Amazon | M3 x 4 mm Heat-set insets


## Project Files

* Schematic and PCB design
* Gerber/manufacturing files
* 3D-printable enclosure
* Reference photos of the assembled prototype

## Prototype / Revision Note

**The photos shown below are of an earlier prototype revision.**

The PCB used in the photographed prototype required a small section of the board to be manually cut for proper mechanical fitment. The PCB layout has since been revised to correct this interference.

The current revision is intended to fit without this modification, but has not yet been physically verified in the same configuration shown in the photos.

## Photos

<p align="center">
  <img alt="N64 Power Adapter installed" src="/Images/5490.jpg" width="800" />
</p>

<p align="center">
  <img alt="N64 Power Adapter enclosure" src="/Images/5486.jpg" width="800" />
</p>

<p align="center">
  <img alt="N64 Power Adapter enclosure" src="/Images/5485.jpg" width="800" />
</p>

<p align="center">
  <img alt="N64 Power Adapter internal assembly" src="/Images/5483.jpg" width="800" />
</p>
