# VampBoost - joule thief circuit (**under development all related files will be uploaded soon**)


## project logo
![logo](https://github.com/user-attachments/assets/0ce2df57-75c0-4e0e-842e-c3342da03895)


**VampBoost**
why this name ? 
It combines "Vamp" (hinting at energy "stealing" or drawing from low sources, like a vampire) and "Boost" (highlighting the voltage-boosting function of the circuit). It's catchy and reflects the essence of the project!

## Table of Contents
- [Overview](#overview)
- [Working Principle](#working-principle)
- [Circuit Diagram](#circuit-diagram)
- [Components Required](#components-required)
- [How to Build](#how-to-build)
- [Applications](#applications)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Joule Thief** is a minimalist circuit used to boost low input voltage to a usable level. The name reflects its ability to "steal" energy from nearly drained batteries, giving them extended life and allowing devices like LEDs to remain operational for a longer period.

This repository includes:
- Circuit diagram
- Step-by-step assembly instructions
- Demonstration video (optional)
- Applications and use cases

## Working Principle

A Joule Thief is a simple, self-oscillating voltage-boosting circuit that allows a low-voltage power source, such as a single AA or AAA battery, to drive a higher voltage load, like an LED. It essentially "steals" the remaining energy in a battery that would otherwise be considered depleted for standard circuits.

**Working Principle of the Joule Thief**:

1. Inductor and Feedback: The circuit uses a toroidal core or coupled inductor (a coil of wire wound on a ferrite core) with two windings—one connected to the battery and another connected to the base of the transistor. These two windings are oriented in such a way that they create positive feedback.


2. Initial Condition: When power is first applied, a small current flows through the first winding of the inductor and the base-emitter junction of the transistor, turning it on.


3. Transistor Activation: As the transistor turns on, current starts flowing through the second winding of the inductor (connected to the transistor’s collector), causing the magnetic field in the core to expand. This change in the magnetic field induces a voltage in the first winding, which further increases the base current, turning the transistor on harder.


4. Saturation and Cutoff: The transistor continues to turn on until the magnetic core of the inductor saturates. Once it saturates, the inductor can no longer increase the current, and the voltage across the base-emitter junction of the transistor starts to drop, causing the transistor to turn off.


5. Energy Release: When the transistor turns off, the magnetic field in the inductor collapses. This collapsing field generates a high voltage spike across the windings, which is used to drive the load (e.g., the LED). The process then repeats itself rapidly, oscillating on and off, boosting the low battery voltage to a higher level.



Key Components:

Transistor: Switches the current on and off, enabling oscillation.

Inductor (Torus Core): Stores energy in the form of a magnetic field and releases it as a higher voltage when the transistor turns off.

Resistor: Provides bias current to the base of the transistor to start oscillation.

LED/Load: A device that requires a higher voltage than what the power source provides.


Applications:

Powering LEDs from nearly dead batteries.

Low-voltage to high-voltage conversion in energy-efficient systems.

Learning and experimentation for understanding inductive circuits.


The Joule Thief circuit works because it uses inductive energy storage and feedback to "recycle" the voltage and make use of a nearly depleted battery, hence the name "Joule Thief."


## Circuit Diagram

![VampBoost schematics hand drawn](https://github.com/user-attachments/assets/85853c16-f345-41be-a404-53946a6cb1eb)



## Components Required (rough list actual list will be updated soon)

- **NPN Transistor** (2N2222, BC547, or similar)
- **Toroidal Inductor Core**
- **Magnet wire** for winding the inductor
- **Resistor** (1kΩ)
- **LED** or diode
- **Low-voltage battery** (e.g., 1.5V AAA or AA)
- **Breadboard** and wires for assembly

## How to Build

1. **Wind the Inductor**: Use a toroidal core and wrap two windings (10-15 turns) of magnet wire to create a transformer.
2. **Assemble the Circuit**: Connect the inductor, transistor, resistor, and LED as per the circuit diagram.
3. **Test the Circuit**: Attach the low-voltage power source and watch the LED light up.

For detailed step-by-step instructions, refer to the [Build Guide](BuildGuide/BuildGuide.md). 

## Applications

- **LED lighting from nearly-dead batteries**
- **Powering small devices from low-voltage sources**
- **Educational projects on boost converters and switching circuits**

## Contributing

We welcome contributions to improve this project. If you'd like to contribute, please:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to use this project resources for your project...**I SUPPORT OPEN SOURCE**
