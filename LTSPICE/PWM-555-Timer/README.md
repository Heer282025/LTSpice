# PWM Signal Generation Using 555 Timer IC

## 📌 Project Overview

This project demonstrates **Pulse Width Modulation (PWM)** using the **NE555 Timer IC**.

A sinusoidal control voltage is applied to **Pin 5 (Control Voltage)** of the 555 timer. The variation in the control voltage changes the **pulse width of the output at Pin 3**.

The circuit is designed and simulated using **LTspice**.

## ⚙️ Components
Component-Value:

NE555 Timer IC-1
R1-400 Ω
R2-400 Ω
C1-1 µF
C2-10 nF
Supply Voltage-9 V
Pin 5 Input-50 Hz sine wave

## 🔌 Pin Connections

- **Pin 1 (GND)** → Ground
- **Pin 2 (TRIG)** → Timing node
- **Pin 3 (OUT)** → PWM Output
- **Pin 4 (RESET)** → +9 V
- **Pin 5 (CV)** → Sinusoidal control input
- **Pin 6 (THRS)** → Timing node
- **Pin 7 (DIS)** → R1–R2 junction
- **Pin 8 (VCC)** → +9 V


## Simulation Output
The simulation shows the **50 Hz sinusoidal control signal at Pin 5** and the corresponding **PWM output at Pin 3**. The output pulse width varies according to the control voltage.
