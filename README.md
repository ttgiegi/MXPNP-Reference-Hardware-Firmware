# MXPNP Legacy Hardware & Firmware

This repository is a public reference archive for historical and superseded MXPNP hardware designs and legacy firmware.

## About

The contents represent earlier generations of MXPNP development. They may have been replaced by newer hardware and software architectures and are not expected to receive ongoing maintenance.

## Repository Scope

Released hardware designs may include manufacturing and reference material such as Gerber files, drill files, bills of materials (BOMs), pick-and-place files, schematic PDFs, and related documentation. Original CAD source files may not always be provided.

Legacy firmware may include modified versions or configurations of upstream projects, such as Marlin. Each component should retain its appropriate upstream attribution and license information.

## Repository Structure

```text
hardware/     Legacy hardware designs and manufacturing/reference files
firmware/     Legacy firmware sources and configurations
docs/         Design-specific notes and reference documentation
```

Directories will be added as legacy designs are archived.

## Status Labels

- `LEGACY`: Historical design retained for reference.
- `SUPERSEDED`: Replaced by a newer design or implementation.
- `EXPERIMENTAL`: Incomplete or intended for experimentation.
- `UNTESTED`: Not recently verified.

## Legacy Hardware

Hardware releases are provided for study, manufacturing of an older design, porting work, and experimentation. Availability and completeness vary by design.

### PCB Design Notes

Design-specific scope, upstream references, release contents, and known limitations are documented on these Wiki pages:

- [Smoothieware Control Board](https://github.com/ttgiegi/MXPNP-Reference-Hardware-Firmware/wiki/Smoothieware-Control-Board)
- [Six-Axis Pick-and-Place Mainboard](https://github.com/ttgiegi/MXPNP-Reference-Hardware-Firmware/wiki/Six%E2%80%90Axis-Pick%E2%80%90and%E2%80%90Place-Mainboard)
- [Nine-Axis Pick-and-Place Mainboard](https://github.com/ttgiegi/MXPNP-Reference-Hardware-Firmware/wiki/Nine%E2%80%90Axis-Pick%E2%80%90and%E2%80%90Place-Mainboard)

## Legacy Mechanical Designs

The archive also includes historical CoreXY mechanical-design references for DIY study and experimentation. They are marked `LEGACY`, `EXPERIMENTAL`, and `UNTESTED`; they are not validated machine designs and are not recommended for direct production use.

The large design archives are distributed through the [CoreXY Mechanical Reference Release](https://github.com/ttgiegi/MXPNP-Reference-Hardware-Firmware/releases/tag/legacy-corexy-v1.0.0). See the [CoreXY Mechanical Reference Designs Wiki page](https://github.com/ttgiegi/MXPNP-Reference-Hardware-Firmware/wiki/CoreXY-Mechanical-Reference-Designs) for download guidance, checksums, and known limitations.

## Legacy Firmware

Firmware releases are retained as historical implementations and configurations. Compatibility with current MXPNP hardware or software is not guaranteed.

## Licensing and Attribution

License and attribution information, including applicable upstream notices, is provided with the relevant component where available.

## Current MXPNP Project

This repository is distinct from the current MXPNP project and its documentation. Refer to the current MXPNP project repository and documentation location when available: `CURRENT_MXPNP_PROJECT_URL`.

## Disclaimer

Legacy designs are provided for reference and experimentation. They are not guaranteed to be compatible with current MXPNP hardware or software, production-ready, safe, or actively supported unless a particular design explicitly states otherwise.

## Contact
For questions about uncertain or archive-specific information, contact `1025971921@qq.com`.
