# 🔌 Variable DC Regulated Power Supply (2V – 3V)

## 📌 Overview
This project focuses on designing and implementing a **variable DC regulated power supply** capable of delivering an output voltage between **2V and 3V**. The system uses a **Zener diode-based regulation technique** combined with a **full-wave rectifier and filter circuit**.

---

## 🎯 Objective
- Convert AC supply into stable DC output
- Reduce ripple using filter capacitor
- Maintain constant voltage using Zener regulator
- Achieve adjustable output using voltage divider

---

## ⚙️ Components Used
- Transformer (6-0-6, center-tapped)
- Diodes (1N4007)
- Capacitor (1000µF)
- Zener Diode (1N4728, 3.3V)
- Resistors (100Ω, 3.3kΩ)
- Potentiometer (1kΩ)
- Ammeter & Voltmeter
- Breadboard & wires

---

## 🧠 Working Principle

### 1️⃣ Full-Wave Rectifier
- Converts AC input into pulsating DC
- Implemented using center-tapped transformer and diodes

### 2️⃣ Filter Circuit
- Capacitor reduces ripple
- Output fluctuates between **7.369V and 7.719V**

### 3️⃣ Zener Voltage Regulator
- Maintains constant voltage of **3.3V**
- Operates within safe current limits

### 4️⃣ Voltage Divider
- Produces adjustable output between **2V – 3V**
- Uses potentiometer for variation

---

## 📊 Results
- Output Voltage Range: **2.088V – 2.971V**
- Load Current Range: **3mA – 12mA**
- Load Regulation: **26.75%**

---

## ⚠️ Observations / Deviations
- Output drops below 2V for low resistance (<150Ω)
- Current range limited due to high resistance values
- Expected 70mA not achieved

---

## 🔧 Applications
- Low voltage DC supply
- Electronics lab experiments
- Educational circuit design

---

## 🔮 Future Improvements
- Improve load current range
- Use better regulation techniques (IC regulators)
- Reduce losses using optimized components

---

## 📷 Circuit & Outputs
(Add your images here)

---

## 📄 Documentation
Full report available in `/docs` folder

---

## 👨‍💻 Author
**Guruvisvesh S A**  
Electronics & Communication Engineering
