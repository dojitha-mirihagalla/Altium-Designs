# IR Remote Controlled Fan
<p align="left">
  <img src="https://github.com/dojitha-mirihagalla/Altium-Designs/assets/126095827/638389bd-0367-4191-86dc-ce6b826c080a" width="100" alt="giphy">
</p>

This repository contains the code and schematics for an IR remote controlled fan project. The project involves controlling a fan using an infrared (IR) remote, making use of various components such as 2 servos, 1 DC motor MOSFET controller, RGB LED, OLED display, ATmega328P and an IR remote sensor.

---
## Components Used
1. **2 Servos**: Servo motors are used to control the direction and angle of the fan blades. They provide precise and controlled movements, allowing the fan to be adjusted easily.

2. **1 DC Motor MOSFET Controller**: This component is utilized to control the speed of the fan. It enables smooth and variable speed adjustments, making the fan more versatile in different scenarios.

3. **RGB LED**: The RGB LED adds a touch of color to the project, indicating the fan's status or modes. It enhances the visual appeal and provides user-friendly feedback.

4. **OLED Display**: The OLED display serves as the user interface, showing relevant information such as fan speed, mode and so on. It offers a clear and intuitive way to interact with the fan.

5. **IR Remote Sensor**: The IR remote sensor is the key input device, allowing users to wirelessly control the fan. With the remote, users can adjust fan speed, change modes, and power it on/off effortlessly.

<p align="center">
  <img src="https://github.com/dojitha-mirihagalla/Altium-Designs/assets/126095827/cfdf3865-c1d1-4ee9-a753-9d6978afa5d7" width="400" alt="ATmega328P-M3X-Regular", style="margin-right: 100px;">
  
  <img src="https://github.com/dojitha-mirihagalla/Altium-Designs/assets/126095827/45d4d858-425a-4350-9f47-8caa9bda9c58" width="195" alt="kit_ir">
</p>

---

## How it Works

1. When the IR remote sensor receives commands from the remote control, the Arduino or microcontroller interprets the signals.

2. The Arduino then processes the commands and sends appropriate signals to the servos to adjust the fan's direction and angle.

3. The DC motor MOSFET controller adjusts the voltage supplied to the fan's motor, controlling its speed accordingly.

4. The RGB LED provides visual feedback, changing colors based on the fan's status or mode.

5. The OLED display shows relevant information about the fan, making it easy for users to monitor and interact with the device.

---

## Getting Started

To replicate or build upon this project, follow these steps:

1. **Hardware Setup**: Connect the components following the provided schematics. Ensure proper connections and double-check the wiring before powering up the circuit.

2. **Upload Code**: Use the Arduino IDE or suitable software to upload the code to the microcontroller. The code is responsible for interpreting IR remote signals, controlling servos and DC motor, and managing OLED and RGB LED functions.

3. **Test and Calibrate**: After uploading the code, test the fan's functionality using the IR remote. Calibrate the servos and motor controller if needed to achieve desired performance.

4. **Interact and Enjoy**: With the setup complete, you can now use the IR remote to control the fan, adjust its direction, speed, and enjoy the RGB visual feedback on the LED.

---

## PCB Design
![PCB3d](https://github.com/dojitha-mirihagalla/Altium-Designs/assets/126095827/931936fa-9051-41a6-a1d0-4cab088f365b)


