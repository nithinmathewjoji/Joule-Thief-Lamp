# VampBoost - joule thief circuit Build Guide
## project logo
![logo](https://github.com/user-attachments/assets/0ce2df57-75c0-4e0e-842e-c3342da03895)

This project is a **Joule Thief circuit** designed to step up the voltage from a low-voltage AAA battery to power a high-voltage LED array. The circuit uses a tilt switch to activate the circuit based on movement, making it ideal for motion-activated devices or low-power lighting solutions.

## **Table of Contents**
- [Introduction](#introduction)
- [Components](#components)
- [Schematic](#schematic)
- [Working Principle](#working-principle)
- [Step-by-Step Operation](#step-by-step-operation)
- [Applications](#applications)
- [Assembly Instructions](#assembly-instructions)
- [Testing and Troubleshooting](#testing-and-troubleshooting)
- [Conclusion](#conclusion)

---

## **Introduction**

The **Joule Thief** is a simple but powerful boost converter circuit that allows you to power devices, such as LEDs, from a low-voltage source like a nearly drained battery. In this project, a tilt switch is added to control when the circuit is activated, making it perfect for motion-sensitive or orientation-based lighting systems.

---

## **Components**

Here is a list of components required to build the circuit:

| Component         | Value/Part Number  | Description                                               |
|-------------------|--------------------|-----------------------------------------------------------|
| AAA Battery       | 1.5V               | Power source for the circuit                              |
| Tilt Switch       | -                  | Controls the circuit based on orientation                 |
| Resistor R1       | 1 kΩ               | Limits current to the base of transistor Q1               |
| Resistor R2       | 100 kΩ             | Provides bias to Q1 and helps in switching                |
| Capacitor C1      | 10 pF              | Stabilizes oscillations                                   |
| Capacitor C2      | 0.1 µF, 100V       | Smooths and stabilizes the output voltage                 |
| Inductor L1       | 100 µH             | Stores energy and generates the boosted voltage           |
| Diode D1          | 1N4148             | Fast-switching diode to direct current flow               |
| Transistor Q1, Q2 | KSP06 NPN          | Switching transistors that form the oscillator            |
| LED Array         | -                  | High-voltage LED array (requires around 70V to operate)   |

---

## **Schematic**

Here is the schematic for the **Joule Thief LED Driver Circuit**:

![VampBoost schematics hand drawn](https://github.com/user-attachments/assets/85853c16-f345-41be-a404-53946a6cb1eb)



## **Working Principle**

This circuit operates as a **Joule Thief** — a type of boost converter that extracts power from low-voltage sources. The circuit uses a tilt switch to activate and a combination of transistors and an inductor to create high-frequency oscillations. These oscillations generate voltage spikes that are stepped up and used to power high-voltage LEDs.

### Key Highlights:
- **Boost Converter:** The circuit steps up the 1.5V battery voltage to around **70V** to power a high-voltage LED array.
- **Tilt Switch Activation:** The circuit only activates when the tilt switch closes, making it ideal for motion-based applications.
- **Energy Efficiency:** Extracts power even from nearly depleted batteries, making it an energy-efficient solution for LED lighting.



## **Step-by-Step Operation**

1. **Power Supply (AAA Battery):** The circuit is powered by a **1.5V AAA battery**.
2. **Tilt Switch Activation:** When the **tilt switch** detects movement, it closes the circuit, allowing current to flow.
3. **Oscillating Transistors:** **Q1** and **Q2** form a self-oscillating pair, turning on and off rapidly to drive current through the inductor.
4. **Inductor Charging and Voltage Boost:** The **inductor (L1)** stores energy during the "on" state and releases a voltage spike when the transistors turn off.
5. **Boosted Voltage to LEDs:** The high-voltage spike is directed through **D1** to the output capacitor **C2**, which smooths the voltage and powers the **LED array**.
6. **LED Illumination:** The LEDs light up using the boosted voltage (~70V), even when the battery voltage is as low as 1.0V.



## **Applications**

- **Low-Power LED Lighting:** Ideal for energy-efficient lighting systems that can run off nearly dead batteries.
- **Motion-Activated Lights:** The tilt switch makes this circuit suitable for motion-activated devices or orientation-based lighting.
- **Energy Harvesting:** Extracts the remaining energy from drained batteries, making it useful for emergency lights or portable devices.
- **Educational Projects:** A simple yet powerful project to learn about boost converters, oscillators, and power electronics.



## **Assembly Instructions**

1. **Prepare the Components:** Gather all the components listed in the [Components](#components) section.
2. **Build the Circuit:**
   - Start by placing the **transistors (Q1, Q2)** and connect them according to the schematic.
   - Add the resistors (**R1, R2**) to the appropriate pins of the transistors.
   - Connect the **inductor (L1)** between the collector of **Q2** and the positive rail.
   - Place the **diodes (D1)** in the circuit for voltage rectification.
   - Add the capacitors (**C1, C2**) to their respective positions to stabilize the circuit.
   - Finally, connect the **tilt switch (S1)** to control the circuit activation.
3. **Connect the LED Array:** Attach the LED array to the output side of the circuit.
4. **Power the Circuit:** Insert the **1.5V AAA battery** and tilt the switch to activate the circuit.



## **Testing and Troubleshooting**

- **LEDs not lighting up:**
  - Ensure that the battery is connected properly and has sufficient charge.
  - Check the orientation of the **tilt switch**. The circuit will not activate unless the switch is closed.
  - Verify the connections to the **LED array** and ensure that the voltage boost is reaching around **70V**.
  
- **Oscillations not occurring:**
  - Ensure that the transistors **Q1** and **Q2** are correctly placed and wired.
  - Check the connections around the **inductor (L1)** and ensure that it is not open or shorted.

- **Excessive Heating:**
  - Ensure that the **transistors** are not overloaded. If the components heat up, reduce the load (e.g., by reducing the number of LEDs in the array).


## **Conclusion**

This **Joule Thief LED Driver Circuit** is a great way to explore the principles of boost converters, oscillators, and power electronics. It efficiently extracts power from low-voltage sources, such as drained batteries, and converts it into high-voltage energy to light up a series of LEDs. The added **tilt switch** functionality makes it even more versatile for motion-activated or orientation-based applications.

Happy building!
