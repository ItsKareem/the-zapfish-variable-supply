<img width="1280" height="650" alt="star-blinky-header" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish-header.png" />

# An AC-to-DC Variable Power Supply (3V–12V) ⚡︎ ˖ ࣪ 

A variable DC power supply built around diode applications. I designed and simulated the circuit on LTSpice to verify its behaviour, the recreated it in KiCad and designned a PCB for it. This project convers AC voltage from a transformer into a stable DC output, so it's pretty useful for powering and testing electronics projects. 

## Features
- Adjustable DC output voltage
- Bridge rectifier for AC-to-DC conversion
- Filter capacitor to reduce ripple
- THT components
  
I made this project as a qualifying project for [fallout](https://www.fallout.hackclub.com), a hardware hackathon organized by hack club Shenzhen, China.

### PCB:
<img width="1918" height="930" alt="the-zapfish" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish.png" />
<img width="1021" height="839" alt="the-zapfish-pcb" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish-pcb.png" />

## How it works

The PCB is designed to connect to the step-down transformer instead of mounting the transformer directly on the board.

1. The transformer steps down the 220V AC current to 12V
2. The diode rectifier converts it to DC
3. The filter capacitor reduces ripple of the pulsating DC
4. The adjustable voltage regulator controls the value of the voltage depending on the 2 resistors
5. The regulated DC output can then be used to power electronic circuits

The PCB handles steps 2-5.

### Simulation:
<img width="3840" height="2160" alt="the-zapfish-simulation-3v" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish-simulation-3v.jpg" />
<img width="3840" height="2160" alt="the-zapfish-simulation-3v" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish-simulation-12v.jpg" />

### Zine Page:
<img width="1680" height="2380" alt="the-zapfish-zine-page" src="https://github.com/ItsKareem/the-zapfish-variable-supply/blob/main/images/the-zapfish-zine-page.png" />
