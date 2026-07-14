# Mechatronics & Electronics Studies 🔧

This repository documents my practical journey, hands-on experiments, and technical evolution in Basic Electronics, Automation, and Arduino programming. The goal is to log my learning progress from the ground up, focusing on hardware logic, circuit design, and component manipulation.

---

## 🛠️ Developed Projects

### 1. First LED
* **Objective:** Initial hardware setup, understanding the core code structure (`setup` and `loop`), and configuring digital output pins.
* **Demonstration:**
<img width="480" height="480" alt="1-FirstLED-ezgif com-video-to-gif-converter (1)" src="https://github.com/user-attachments/assets/2e4cea78-c413-42f7-86d4-80e8526eb1b9" />

---

### 2. Two Sequences of LEDs Blinking (Flasher Circuit)
* **Objective:** Implementing sequential timing control with multiple LEDs acting on independent outputs to simulate a signaling effect.
* **Demonstration:**
<img width="480" height="480" alt="1-TwosequencesofLedsblinkinglikepolice-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/395caa0c-f0bd-45bd-829b-f3c13fc7100d" />

---

### 3. Christmas Tree LEDs
* **Objective:** Expanding digital outputs in parallel on the breadboard, organizing dynamic activation timings, and structuring clean loop logic.
* **Demonstration:**
<img width="480" height="480" alt="2-ChristmasTreeLeds-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/a63ed5ea-00b5-4de0-bb9d-98f1a89a6991" />

---

### 4. Traffic Light
* **Objective:** A classic project in urban/industrial automation. Programmed logic to simulate the exact transition states and timing of a real-world traffic light (Green, Yellow, and Red).
* **Demonstration:**
<img width="500" height="400" alt="3- Traffic Light" src="https://github.com/user-attachments/assets/68b0770c-7aee-4dc5-9e40-9837a0977ca6" />

---

### 5. Potentiometer
* **Objective:** Introduction to analog signals. Reading variable input data through a physical voltage divider and converting analog values within the IDE environment.
* **Demonstration:**
<img width="400" height="320" alt="4- Potentiometer" src="https://github.com/user-attachments/assets/914c88a8-74cf-4683-bbae-e52cba722e65" />

---

### 6. Button
* **Objective:** First implementation of digital input peripherals. Controlling physical current flow to trigger specific software actions via manual pressing.
* **Demonstration:**
<img width="500" height="400" alt="5- Button" src="https://github.com/user-attachments/assets/9c25f7c5-9d73-4e68-a0de-7b15e4a6c508" />

---

### 7. Fading (Breathing Effect)
* **Objective:** Controlling real power and intensity delivered to a component using Pulse Width Modulation (PWM) and loop control structures (`for` loops).
* **Demonstration:**
<img width="600" height="480" alt="6- Fading" src="https://github.com/user-attachments/assets/9d1ba4e8-9dd7-47dd-be95-8340f0286eda" />

---

### 8. Responder Experiment (Reaction Timer)
* **Objective:** Full integration of digital inputs and outputs (LED + Push Button + Pulldown Resistor) to build a high-precision reaction timer. The program calculates human response times in milliseconds using the `millis()` function and outputs the data to the Serial Monitor.
* **Demonstration:**
<img width="480" height="384" alt="7- Responder Experiment" src="https://github.com/user-attachments/assets/c16de16f-90c5-467c-9bae-ab409bb4b814" />

---

### 9. Active Buzzer
* **Objective:** Implementing a continuous hardware-driven alert system. This experiment demonstrates how an active internal oscillator automatically generates a fixed-frequency beep using simple high/low voltage states (`digitalWrite`).
* **Demonstration:**

https://github.com/user-attachments/assets/d4d69878-2e6f-4239-bc57-0b1f3c7f6526

---

### 10. Passive Buzzer
* **Objective:** Emulating distinct musical notes and controlling sound frequencies. The project utilizes the `tone()` function to send varying electronic pulses, allowing full control over pitch and duration on a non-oscillating membrane.
* **Demonstration:**

https://github.com/user-attachments/assets/c8b610a9-88ef-4213-8aef-553f27c90e17

---

### 11. LED RGB (Color Mixing)
* **Objective:** Mastering Pulse Width Modulation (PWM) to create multi-color visual interfaces. By independently dosing Red, Green, and Blue sub-LED intensities from `0` to `255` via `analogWrite()`, the project simulates complex color integration for industrial status displays.
* **Demonstration:**
<img width="500" height="400" alt="10- LED RGB" src="https://github.com/user-attachments/assets/21074cb1-0e38-4999-9a3c-ea4cbec32fb8" />

---

### 12. Photoresistor (Light Theremin)
* **Objective:** Mapping real-time analog light intensity readings to dynamic audio frequencies. By reading variable voltage from a Light Dependent Resistor (LDR) on pin A0 and mathematically scaling the values, the system drives a passive buzzer to emulate a pitch-bending optical instrument.
* **Demonstration:**

https://github.com/user-attachments/assets/31973904-0438-4c33-9f7c-3aa8e0c31e6f

---

### 13. Tilt Switch Alarm
* **Objective:** Implementing a gravity-based binary state detector. This project utilizes the Arduino's internal `INPUT_PULLUP` resistor to read the physical open/closed states of a ball-tilt sensor, instantly triggering an audiovisual alert (LED and Buzzer) when a tilt or orientation change is detected.
* **Demonstration:**

https://github.com/user-attachments/assets/1abc21f0-c3e4-42c9-a2c8-0410a7ceeff2

---

## 🚀 Next Steps
* Move forward with electric motor controls and relay switches.
* Study the integration of industrial and environmental sensors.

📫 LinkedIn: [Sheldon Rivabem](https://linkedin.com/in/sheldonrivabem88)
