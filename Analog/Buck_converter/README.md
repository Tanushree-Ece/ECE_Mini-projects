# Buck Converter Design and Simulation using LTspice

## Overview

This project presents the design and simulation of a DC-DC buck converter using LTspice.

The converter steps down a DC input voltage to a regulated lower output voltage using PWM control and feedback regulation.

---

## Specifications

| Parameter | Value |
|----------|-------|
| Input Voltage | 12V |
| Output Voltage | 6V |
| Switching Frequency | 25kHz |
| Topology | Buck Converter |
| Peak to Peak capacitor ripple voltage | 20mV |
| Peak to Peak inductor ripple current | 0.8A |
| Simulator | LTspice |

---

## Circuit Components

- MOSFET switch
- Schottky diode
- Inductor
- Output capacitor
- Feedback network
- PWM voltage source

---

## Working Principle

The buck converter operates by controlling the duty cycle of the MOSFET switch.

During ON time:
- Energy is stored in the inductor.
- Current flows to the load.

During OFF time:
- Inductor releases stored energy through the diode.

The output voltage is controlled by:

Vout = D × Vin

where D is the duty cycle.

---

## Simulation Results

### Output Voltage

![Output Voltage](Simulation_Results/output_voltage.png)


### Switching Waveform

![PWM](Simulation_Results/switch_waveform.png)


### Inductor Current

![Inductor Current](Simulation_Results/inductor_current.png)

---

## Key Observations

- Stable output voltage regulation achieved.
- Continuous conduction mode operation verified.
- Switching behaviour analyzed.
- Output ripple voltage measured.

---

## Tools Used

- LTspice 


---

## Author

Tanushree L
