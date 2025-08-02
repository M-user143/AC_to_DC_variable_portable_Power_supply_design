# ⚡ DC Variable Power Supply – Portable AC to DC Converter

## 🔧 Project Summary
This project presents a **variable DC power supply** that converts standard 220V AC (WAPDA-supplied) into a **user-adjustable DC voltage ranging from 1.23V to ~12V**. It uses classic electrical engineering techniques such as **voltage step-down using a transformer**, **rectification**, **filtering**, and **DC-DC conversion** via the **LM2596 buck converter**. Designed to be low-cost and portable, it serves as a flexible DC source for labs and industrial applications.

---

## ⚙️ Features
- Input: 220V AC (mains)
- Output: 1.23V – 12V DC (adjustable)
- Max Output Current: 3A
- Digital voltage display
- Voltage adjustment via 10k potentiometer
- Fully hardware-implemented and tested

---

## 🧰 Hardware Components
- Step-down Transformer (220V AC to 12V AC)
- Full-Wave Bridge Rectifier
- LM2596 Buck Converter Module
- 1000μF Capacitor (Filter)
- 10kΩ Potentiometer (Voltage Adjustment)
- Digital Voltmeter (Output Display)

---

## ⚡ Working Principle
1. **Step-down Transformation**: A transformer reduces 220V AC to 12V AC.
2. **Rectification**: A full-bridge rectifier converts AC to pulsating DC.
3. **Filtering**: A capacitor smooths the DC signal by reducing ripples.
4. **DC-DC Conversion**: The LM2596 module adjusts the voltage from 1.23V up to input voltage.
5. **Monitoring**: Output is displayed on a digital voltmeter and adjusted using a potentiometer.

---

## 🛠 Applications
- Testing electronics circuits
- Charging batteries of various voltage levels
- Electroplating in industry
- Powering small DC motors or synchronous generators

---

## 📚 Background
AC power is widely available, but many devices require stable DC. This project addresses that need by converting readily available AC to variable DC using a combination of proven techniques — offering an efficient and user-controllable power source for a range of electrical tasks.

---

## 🧪 Simulation Results
> Simulation files and waveform screenshots (if available) are provided in the `/simulations` folder.

---

## 👨‍💻 Contributors
- Hafiz M. Ahsan Sheraz  
- Danyal Irfan Butt

---

## ✅ Conclusion
A portable and cost-effective solution to generate DC voltage from AC mains with an adjustable output range and current support up to 3A. This project is ideal for electronics labs, industry applications, and educational demonstrations.

