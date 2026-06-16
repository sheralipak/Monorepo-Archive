# 🚗 Driver Anti-Sleep Alarm (Drowsy Driver Detection)

An embedded systems safety automation project designed to counter driver fatigue and prevent road accidents. The system monitors physical behavioral data in real-time and executes immediate alert protocols if signs of drowsiness are detected.

## ⚙️ Architecture & Automation Logic
The system pairs an 8051 microcontroller with sensor tracking hardware to create an active defensive feedback loop:
* **Anomalous State Detection:** Utilizes an **Eye Blink Sensor** connected to hardware registry inputs (`P1^0`) to track continuous eye closure patterns.
* **Incident Response Blueprint:** If the sensor detects that a driver's eyes remain closed past a calibrated threshold, the controller shifts states to trigger a high-frequency **Buzzer alert** (`P1^1`) to wake the driver instantly.
* **Visual Telemetry Output:** Integrates a $16 \times 2$ character **LCD screen** (`Port 2` and data pins) to output real-time system tracking metrics and warnings like `"DROWSY_DRIVER"` directly to the vehicle dashboard console.

## 🛠️ Technical Stack & Skills Demonstrated
* **Languages & Hardware Control:** Embedded C development
* **Microcontroller Architecture:** Intel 8051 register operations, pin mapping (`sbit`), and I/O bit addressing.
* **Peripherals Integrated:** LCD character displays, Infrared/Optical Eye-Blink Sensors, and Piezoelectric Buzzers.
* **Core Concepts:** Hardware delay subroutines, polling control loops, and embedded real-time threat mitigation logic.
