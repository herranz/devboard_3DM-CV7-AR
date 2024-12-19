<div align="center">


  
  <h1> DevBoard 3DM-CV7-AR </h1>
  <p> DevBoard for the Parker 3DM-CV7-AR IMU </p>


<!-- Badges -->

<h4>
    <a href="https://bsky.app/profile/herranz.bsky.social">BLUESKY</a>
  <span> · </span>
    <a href="https://www.github.com/herranz">GITHUB</a>
  
  </h4>

<img src="https://github.com/herranz/devboard_3DM-CV7-AR/blob/main/img/dev_board_3DM-CV7-AR_2.png" alt="image" width="500" height="auto" />
  
  
</div>

<br />

<div>&nbsp;</div>

## Table of Contents
* [General Info](#general-information)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)


## General Information
- A standalone development board for the [3DMCV7-AR](https://www.microstrain.com/inertial-sensors/3dmcv7-ar), designed for integration into robotic systems. It features dual connection options (UART or miniUSB) and includes a PCB layout optimized to minimize interference with the magnetometer. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!--
## Technologies Used
- Tech 1 - version 1.0
- Tech 2 - version 2.0
- Tech 3 - version 3.0


## Features
List the ready features here:
- Awesome feature 1
- Awesome feature 2
- Awesome feature 3

-->
## Screenshots
![Example screenshot](./img/screenshot.png)
 


## Setup

The board was ordered through [JLCPCB](https://www.jlcpcb.com), utilizing their stack for controlled-impedance, JLC04161H-7628. While USB 2.0 at 12 Mbps is forgiving, it's best to adhere to the specifications for optimal performance.

If you're looking to save time, you can skip the UART LED indicators without impacting core functionality.

## Usage
The board is self-powered when used with USB (preferred mode). If USB is not used, ensure that the Vin does not exceed 5V to remain within specifications. Voltage levels for the serial connection should be TTL.

## Project Status
Project is: __COMPLETE__ 


## Room for Improvement

Room for improvement:
- Fix Silkscreen nomenclature for the Rs and Us in the UART led indicators



## Acknowledgements
- Thanks to caffeine, my soldering iron, and gravity for keeping this project (mostly) grounded. 


## Contact
Created by [@herranz]- feel free to contact me!



 ## License 
 This project is open source and available under the **CERN-OHL-S-2.0 license**


