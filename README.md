# 🚀 Sequential Control of Two Three-Phase Motors

### Automatic Timed Operation Using PLC (Ladder Logic)

This repository contains a PLC program written in **Ladder Logic** for the automatic sequential control of **two three-phase motors** using **Start** and **Stop** push buttons.

---

## 📘 Project Overview

The system consists of:

* **Motor 1 (M1)**
* **Motor 2 (M2)**
* **Start push button**
* **Stop push button**

The objective is to design a control sequence in which the motors turn on and off automatically with specific time delays.

---

## 🔄 Operating Sequence

1. When the **Start** button is pressed:
   → **Motor 1** turns **ON** immediately.

2. After **4 seconds**:
   → **Motor 2** turns **ON**.

3. After **4 seconds** from the moment Motor 2 starts:
   → **Motor 1** turns **OFF**.

4. When Motor 1 turns OFF, wait **another 4 seconds**:
   → **Motor 2** turns **OFF**.

5. After Motor 2 turns OFF, wait **4 seconds**, then:
   → The **entire sequence restarts automatically** from the beginning.

The process continues in a **loop** until the **Stop** button is pressed.


