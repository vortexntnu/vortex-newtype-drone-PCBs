# Newtype-drone AUV PCB Repo

<p align="center">
  <img src="common/Vortex-Logo-3.png" alt="Logo" width="100%"/>
</p>

![KiCad Version](https://img.shields.io/badge/KiCad-10.0-blue)
![Status](https://img.shields.io/badge/status-in%20development-yellow)

---

## Overview

This is where all the project files for Newtype-drone PCBs are stored.

---

## Boards

| Project | Board | Location | Description | Responsible Member | Status |
|---------|-------|----------|-------------|--------------------|--------|
| [Acoustics](acoustics) | [Acoustics] | The big brain house | Acoustics you know | Alvar? | In development |

Each board folder contains its own README with schematics, BOM, and fabrication files.

## Libraries

We for the most part use Würth's github library since we mostly use Würth's components in our PCBs.
Make sure to clone the Würth repo OUTSIDE of this repo.
The Würth library does not contain WR-TBL (aka terminal blocks). To get these you must download it from Würth manually and then move the files into the correct Würth library folders. The reason these are not included by default is because it's ~3GB in size so make sure to have the Würth library repo OUTSIDE of this one.
The rest of our component libraries are either self made or downloaded via the impartGUI plugin.

## License

Hardware licensed under [CERN-OHL-P v2](https://ohwr.org/cern_ohl_p_v2.txt). Software licensed under [MIT](LICENSE).
