# Hortuscopia Dot 1

A small robotic garden assistant. It seeds, waters, and rakes a 10-section decagon garden bed. It is the first version. It is open source.

> This README is a first draft. More detailed instructions, photos, and build notes will be added over time. In the meantime, join the Discord linked at [hortuscopia.com](https://hortuscopia.com) — that's where questions will be answered and progress shared.

---

## What is it

Dot 1 is built around a SO-101 robotic arm mounted at the centre of a 3D printed decagon garden bed. The arm is typically controlled from a PC running LeRobot. A Raspberry Pi 3B+ with touchscreen can be used as an optional standalone controller. A separate Arduino Nano handles water pump timing via a relay module.

The bed holds 10 sections. Each section takes a seeded disc.

---

## What's in this repo

- 3D print files for the decagon garden bed
- 3D print files for arm attachments
- Assembly instructions

The arm itself is not included here. See [SO-ARM100 by The Robot Studio](https://github.com/TheRobotStudio/SO-ARM100) for full arm print files and assembly.

---

## What you'll need

### Arm
- [SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100) — print and assemble following their instructions

### Electronics
- Raspberry Pi 3B+ *(optional — for standalone control)* — [AliExpress](https://a.aliexpress.com/_mtA7Pbb)
- 3.5" touchscreen LCD for Pi *(optional — for standalone control)* — [AliExpress](https://a.aliexpress.com/_mKRsuMZ)
- Arduino Nano V3.0 — [AliExpress](https://a.aliexpress.com/_mtRxaFr) *(optional)*
- 1 channel relay module — [AliExpress](https://a.aliexpress.com/_mrBVrx3) *(optional)*
- STS3215 servos (for the arm) — [AliExpress](https://a.aliexpress.com/_mOYubJb) *(optional)*

### Watering
- USB submersible pump — [AliExpress](https://a.aliexpress.com/_mPk9Q9F) *(optional)*
- Fuel line tubing — [AliExpress](https://a.aliexpress.com/_mt2lO4Z) *(optional)*

### Power
- 12V 5A power supply — for the pump
- Standard Raspberry Pi power supply — for the Pi
- Arm power — see [SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100) for requirements

---

## Software

No software is included in this repo. Dot 1 is a hardware project.

For controlling the arm and training it to perform garden tasks, we recommend [LeRobot by Hugging Face](https://github.com/huggingface/lerobot). It supports teleoperation for recording movements and model creation for autonomous replay.

Getting started with LeRobot is well documented in their repo. The SO-101 arm is compatible out of the box.

---

## Assembly

Full assembly instructions are included in the repo. Follow the SO-ARM100 guide for the arm, then refer to the Dot 1 instructions for mounting, wiring, and bed assembly.

---

## Licence

Hardware designs are open under the [CERN Open Hardware Licence v2 - Permissive](LICENSE-HARDWARE).

---

## What's next

Dot 1 is the beginning. Dot 2 is a larger arm, a larger bed, designed to live outside and grow a meaningful share of a family's vegetables.

Follow along at [hortuscopia.com](https://hortuscopia.com) or join the community on [Discord](https://discord.gg/bWBjVJUzq).
