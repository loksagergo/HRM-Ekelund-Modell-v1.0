# ⚙️ HRM-Ekelund Model Calculator
**High-precision numerical tool for Hot Rolling Force and Torque estimation.**

## 📖 Project Overview
This specialized engineering tool calculates the physical parameters of hot rolling passes using the **Ekelund model**. It is designed to provide quick and accurate feedback on rolling stability and equipment load without the need for complex FEM software.

### 🎯 Key Performance Indicator
The model's accuracy has been validated against industrial measurements:
* **Measured Force:** 355.0 kN
* **Calculated Force:** 350.2 kN
* **Precision:** ~1.3% error rate.

---

## 💻 Professional Features
The program now features standardized international metallurgical terminology:

* **Steel Grade Library:** Choose from standard grades like S235, S355, 37MnSi5, or input custom alloying elements (C, Mn, Cr).
* **Real-time Safety Monitoring:** Automatic status updates based on motor capacity.
  * `[SAFE]`: Operation is stable.
  * `[WARNING]`: Near equipment limits.
  * `[DANGER]`: Motor overload detected.

---

## 🛠️ Technical Specifications
* **Language:** C (Optimized Release Build)
* **Core Physics:** Modified Ekelund Equation for flow stress ($k_f$).
* **Inputs:** * Work roll diameter [mm]
  * Rolling width [mm]
  * Exit thickness [mm]
  * Entry temperature [°C]

---

## 🚀 How to Run the Program
1. Go to the **[Releases](https://github.com/loksagergo/HRM-Ekelund-Modell-v1.0/releases)** section.
2. Download the latest `v1.0HRM`.
3. Extract and run the `.exe` file.
4. Select your **Steel Grade** and enter the rolling parameters as prompted.

---

## 🔒 Confidentiality Notice
The source code is **Proprietary**. This repository serves as a portfolio to demonstrate numerical modeling capabilities, algorithm precision, and software engineering skills in a metallurgical context.

*Developed by: Loksa Gergo Andras*
































