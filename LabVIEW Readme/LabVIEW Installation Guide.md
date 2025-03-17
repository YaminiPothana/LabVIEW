# LabVIEW Installation Guide

## Overview

This document provides a comprehensive guide for installing **LabVIEW**, including system requirements, installation steps, and an introduction to its key features and functionalities. LabVIEW (Laboratory Virtual Instrument Engineering Workbench) is a graphical programming environment widely used in research, industry, and academia.

## Installation Steps

1. **Download LabVIEW**: Visit [NI LabVIEW Download](https://www.ni.com/en/support/downloads/software-products/download.labview.html#559079) and download the software.
2. **Sign Up & Log In**: Create an NI account and log in to proceed with the download.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/step3.png)

1. **Select Version**: Choose **LabVIEW 2025 Q1 Community Version** and start the download.
2. **Run the Installer**: Open the downloaded Disc Image file, double-click it, and navigate to the `.exe` folder.
3. **Install LabVIEW**: Run `install.exe` and follow the on-screen instructions.
4. **Install VI Package Manager**: This will be installed automatically. Choose `3D Express` or any other required software.
5. **Completion**: LabVIEW is now installed and ready for development.

## LabVIEW Overview

LabVIEW uses a **graphical programming language** called **G**, where programs are created using **Block Diagrams**.

### 🔹 Key Components

#### 1️ **Front Panel & Controls Palette**

- The **Controls Palette** is available on the **Front Panel** and contains various controls and indicators for building the user interface.
- It provides UI elements such as **numeric controls, Boolean controls, strings, graphs, arrays, and clusters**.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/frontpanel.png)

#### 2️ **Block Diagram & Function Palette**

- The **Function Palette** is used for programming and is available on the **Block Diagram**.
- It includes categories like **Numeric, Array, Time and Dialog, Waveform, Measurement I/O, Signal Processing, and Data Connectivity**. <br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/blockdiag.png)

#### 3️ **Tool Palette**

- Allows users to **create, modify, and debug Virtual Instruments (VIs)**.
- Shortcut: `Shift + Right Click`
- Common tools include:
  - **Operating Tool**: Select text or change control values.
  - **Positioning Tool**: Resize and position elements.
  - **Labeling Tool**: Edit text.
  - **Object Shortcut Menu Tool**: Access the shortcut menu of an object.<br>
    &nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/Toolplte.png)

## 🔹 Common Keyboard Shortcuts

| Shortcut   | Description                                   |
| ---------- | --------------------------------------------- |
| `Ctrl + B` | Deletes all broken wires in VI                |
| `Ctrl + .` | Stops the running VI                          |
| `Ctrl + E` | Toggles between Front Panel and Block Diagram |
| `Ctrl + T` | Displays both panels on one screen            |

## 🛠 Important LabVIEW Functions

## **Formula Node**

A **Formula Node** allows users to write text-based formulas inside LabVIEW’s Block Diagram.

- **Usage:** Perform mathematical calculations, data transformations, and conditional logic.
- **Syntax:** Supports `+`, `-`, `*`, `/`, `^`, logical operators (`AND`, `OR`, `NOT`), and functions (`SIN`, `COS`, `LOG`, etc.).

#### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Common Use Cases:**

- Data transformation & scaling
- Implementing conditional statements (IF-ELSE, CASE)
- Performing mathematical calculations (e.g., trigonometry, signal processing)

## **Layout & Components**

![alt Text](images/Layout.png)

### **Tab Control**

- Works like multiple web pages in a single interface.<br><br>
  ![alt Text](images/Layout.png)

### **Controls Palette**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/Controlplt.png)

Includes:

- **Numeric Controls** (for numbers & calculations)
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><br>![alt Text](images/Numericplt.png)<br><br>
- **Boolean Controls** (for switches & buttons)<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/bool.png)
- **String Controls** (for text handling)<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/string.png)
- **Array, List, Table, & Tree** <br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/array.png)
- **Ring & Enum** (for dropdown selections)<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/ring.png)
- **I/O Functions** (for data input & output)<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/io.png)
- **Decorations** (for UI enhancements)<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/deco.png)
- **.NET& ACtiveX**<br><br>![alt Text](images/deco2.png)

### **Function Palette** <br><br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/function.png)

Contains:

- **Programming Functions** (for logic implementation) <br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/programing.png)
- **Timing Functions** (for controlling execution flow) <br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt Text](images/Timing.png)

## Conclusion

This guide covers the complete **LabVIEW installation process**, an **overview of LabVIEW**, and a **detailed breakdown of its components**, including the **Front Panel, Block Diagram, and Tool Palette**. With this knowledge, users can efficiently start developing in LabVIEW. <br>

**Authored by**: <spam style = "color:grey;"><i>Yamini Pothana</i></spam>
