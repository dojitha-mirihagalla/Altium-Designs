# RF Power Amplifier PCB (6-Layer, 6 GHz)

Overview of a custom 6-layer PCB featuring controlled impedance, a high-frequency RF power amplifier, and digital power sequencer.
---

## Key Technical Features

- **PCB Stack-up:**  
  6-layer controlled impedance stack-up with detailed impedance profiling for high-frequency signal integrity.

- **RF Section:**  
  - Integrated **HMC637ALP5E** RF power amplifier  
  - 13 dB gain at 6 GHz  
  - Optimized microstrip/stripline layout for minimal loss

- **Power Distribution:**  
  - Multi-rail power network  
  - Digital power sequencer (ESP32-controlled) for regulated startup/shutdown  
  - Decoupling and filtering for RF and digital domains

---

## PCB and 3D Views



---

## Stack-up & Impedance Profile

| Layer | Function            | Notes                      |
|-------|---------------------|----------------------------|
| 1     | Top Signal          | Power, Digital             |
| 2     | Ground Plane        | Reference for Power/digital|
| 3     | Ground plne         | Digital, power             |
| 4     | Power/digital Signal| Core/IO power rails        |
| 5     | RF Ground Plane     | Reference for RF           |
| 6     | RF Signal           |  RF routing, controlled Z  |



*For further details, see the attached schematic and PCB documents*

