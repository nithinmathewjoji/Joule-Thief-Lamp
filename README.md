# Joule Thief Circuit (under development all related files will be uploaded soon)


## project logo
![VampBoost logo 3](https://github.com/user-attachments/assets/cd8e1e07-b31b-4030-95eb-0dcdad44d663)


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

The Joule Thief circuit is a type of **boost converter** that stores energy in an inductor and switches the transistor on and off rapidly, which results in the generation of a higher output voltage than the input voltage.

Here’s how it works:
1. When the transistor is on, current flows through one side of the inductor, creating a magnetic field.
2. As the transistor switches off, the magnetic field collapses, inducing a voltage spike across the second winding of the inductor.
3. This voltage spike is used to power the load, such as an LED, from a weak power source.

## Circuit Diagram

![VampBoost schematics hand drawn](https://github.com/user-attachments/assets/85853c16-f345-41be-a404-53946a6cb1eb)


The main components of this circuit:
- **Transistor** (e.g., 2N2222, BC547)
- **Inductor** (two windings on a toroidal core)
- **Resistor** (typically 1kΩ to 10kΩ)
- **Diode/LED** (output load)

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

For detailed step-by-step instructions, refer to the [Build Guide](link-to-detailed-guide). will be updated soon

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

Feel free to customize the README based on the specific details of your Joule Thief circuit project!
