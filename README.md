<p align="center" style="margin-bottom: 0px !important;">
  <img width="400" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/nbgicon.png?raw=true" alt="Keyquest logo" align="center">
</p>
<h1 align="center" style="margin-top: 0px;">Keyquest Keyboards</h1>
<p align="center" >Developed As Part Of My Industrial Design Thesis</p>
<p align="center" >Some Aspects Of This Project Are In Spanish</p>
<p align="center" >Developed by Matias M.</p>

<p align="center" style="margin-bottom: 0px !important;">
  <a href="https://github.com/Mathiaszmrga">
    <img width="80" src="https://github.com/keyquesttech/Enclave/blob/main/imgs/git.png?raw=true" alt="adf" align="center">
  </a>
 <a href="https://www.behance.net/matiasms">
    <img width="80" src="https://github.com/keyquesttech/Enclave/blob/main/imgs/behance.png?raw=true" alt="adf" align="center">
  </a>

<div align="center" >
  
  ![GitHub Repo stars](https://img.shields.io/github/stars/keyquesttech/encalave?style=plastic)
  ![GitHub forks](https://img.shields.io/github/forks/keyquesttech/Encalave?style=plastic)
  ![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/w/keyquesttech/encalave?style=plastic)
  ![GitHub release (latest by date)](https://img.shields.io/github/downloads/keyquesttech/Enclave/total?style=plastic)
  
</div>
  
<p align="center" style="margin-top: 100px !important;">
  <h2 align="center" style="margin-bottom: 0px;">Versions And Repo Content</h2>
</p>

<p align="center" style="margin-bottom: 0px !important;">
  <a href="https://github.com/keyquesttech/Enclave/tree/main/Enclave-1/stm">
    <img width="300" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/bn-stm.png?raw=true" alt="adf" align="center">
  </a>
 <a href="https://github.com/keyquesttech/Enclave/tree/main/Enclave-1/avr">
    <img width="300" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/bn-avr.png?raw=true" alt="adf" align="center">
  </a>
  
</p>

<p align="center" style="margin-top: 0px !important;">
  <h2 align="center" style="margin-bottom: 0px;">Table of Contents (Enclave-1)</h2>
</p>

<p align="center" style="margin-bottom: 0px !important;">
  <img width="800" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/88.png?raw=true" alt="adf" align="center">
</p>

<p align="center" style="margin-bottom: 0px !important;">
  <h2 align="center" style="margin-top: 0px;"></h2>
</p>

- [Features](#Features)
- [Repo Content](#Repo-Content)
  - [STM](#STM)
  - [AVR](#AVR)
  - [Plate](#Plate)
- [Case](#Case)
- [Code](#Code)
  - [QMK](#QMK)
  - [VIA](#VIA)
  - [VIAL](#VIAL)
- [Suppliers](#Suppliers)
- [Contributing](#contributing)
- [Copyright and License](#copyright-and-license)

## Features:

- Lightweight.
- Cherry MX Compatible.
- Kailh Hotswap Sockets
- RGB Underglow.
- QMK, VIA And VIAL Compatible.
- Customizable.
- USB-C Interphase.
- Built In USB-HUB.

## Repo Content:

All files necessary for reproduction, manufacturing and modifications

| Branch | Content |
|--|--|
| AVR | Files for AVR (arduino) based PCB |
| STM| Files for STM based PCB |
| Plate| Files for FR-4 plate manufacturing |
| Imgs| Images on this repo and product pics |

### STM:

  <img width="400" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/42.jpg?raw=true" alt="STM PCB" align="center">

| Branch | Content |
|--|--|
| 3D| PCB 3D files |
| Datasheet| Datasheet of components used |
| Docs| DXF of PCB outline |
| ZIP Full| KiCad full source file |
| Enclave_stm_sch.pdf| PDF schematic |
| Enclave_stm_BOM.pdf| PDF Bill of materials|

This version of the PCB didn't work at first and it was forgotten in favor of AVR. Use at your own risk.

### AVR:

  <img width="400" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/81.png?raw=true" alt="STM PCB" align="center">

| Branch | Content |
|--|--|
| Datasheet| Datasheet of components used |
| Docs| DXF of PCB outline |
| Production| Production files |
| ZIP Full| KiCad full source file |
| Enclave_avr_BOM.pdf| PDF Bill of materials|
| Enclave_avr_sch.pdf| PDF schematic |

### Plate:

  <img width="400" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/85.jpg?raw=true" alt="STM PCB" align="center">

| Branch | Content |
|--|--|
| DXF SRC| FR-4 Plate DXF source file |
| EasyEDA SRC| EasyEDA JSON PCB source file |
| Plate Gerber| Production files |

## Case:

  <img width="400" src="https://github.com/keyquesttech/Encalave/blob/main/imgs/86.png?raw=true" align="center">

| Branch | Content |
|--|--|
| Case_one_part.step| STEP file of for the case |
| Case_one_part_Drawing.pdf| Technical drawings of the case |

## Code:

Source code files.
- [QMK repo](https://github.com/qmk/qmk_firmware)
- [VIA repo](https://github.com/the-via/keyboards)
- [VIAL repo](https://github.com/vial-kb/vial-qmk)

### QMK:

QMK code, just add to the kyeboards directory and compile or edit as desired. it's currently merged into main so it works on official website and tools.

### VIA:

VIA can be used for local upload of JSON but it's currently merged into main so it works on official website.

### VIAL:

VIAL Source code, merged into main so it works when compiling official branch.

## Suppliers:

**Information on the service providers used for the project**

| Supplier| Contact| Thing |
|--|--|-|
| Elecrow| [Elecrow](https://www.elecrow.com/) | CNC machining
| Elecrow| [Elecrow](https://www.elecrow.com/) | PCB manufacturing
| Upwork| [Alberto M.](https://www.upwork.com/freelancers/~01b4ecb4cf82c98eb9) | PCB design
| Alibaba| echo@hzyinzheng.com | Adhesive feet

## Contributing

All contributions are welcome and encouraged.

## Copyright and License

Released under the MIT license.


<hr>

<div align="center">
  <strong><h1>Other projects from the autor (me)</h1></strong>
</div>

3D models / Prints:
 - [Mason jar ashtray](https://www.printables.com/model/918749-ashtray-mason-jar)
A mason jar attachment to make almost every jar in to an ashtray.

Printer mods:
 - [Servo nozzle brush (printables).](https://www.printables.com/model/913748-ratrig-vcore-331-servo-nozzle-brush)
A servo attached nozzle brush.
 - [Servo nozzle brush (github).](https://github.com/keyquesttech/Ratrig-Vcore-3-3.1-servo-nozzle-brush)
A servo attached nozzle brush.
 - [Endstops.](https://github.com/keyquesttech/3d_printer_endstops)
A collection of custom endstops for 3d printers or cnc machines. 
 - [Thermexp.](https://github.com/keyquesttech/Thermexp)
A PCB to add more thermistors to a klipper printer.

Chrome extensions:
 - [Youtube ads auto skip.](https://github.com/keyquesttech/chrome-extensions)
A chrome extension that emulates a click and auto skips youtube ads. Works even after adblock prevention measures.

Keyboards:
 - [Enclave.](https://github.com/keyquesttech/Enclave)
A custom mechanical switch macro pad. Works on QMK and can be used with klipper.
