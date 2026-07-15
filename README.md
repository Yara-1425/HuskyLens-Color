# HuskyLens-Colo# HuskyLens Color Recognition LED Controller

A simple and interactive project using the **HuskyLens AI camera** and **Arduino Uno** to detect specific colors and trigger corresponding colored LEDs.

## Overview
This project leverages the HuskyLens vision sensor to recognize up to three distinct colors. When the camera identifies a color it has been trained on, the Arduino processes the ID and lights up the corresponding LED (Blue, Red, or Green).

##  Hardware Requirements
*   Arduino Uno
*   HuskyLens AI Camera
*   3 LEDs (Blue, Red, Green)
*   3 Resistors (220Ω - 330Ω)
*   Breadboard and Jumper Wires

##  Circuit Wiring Details

### 1. HuskyLens Connection 
Connect the HuskyLens to the Arduino Uno using the following pins:

| HuskyLens Wire | Arduino Uno Pin |
| :--- | :--- |
| **VCC (Red)** | 5V |
| **GND (Black)** | GND |
| **SDA (Blue)** | A4 |
| **SCL (Green)** | A5 |

### 2. LEDs Connection
Connect the LEDs to the digital pins using resistors to prevent damage:

| LED Color | Arduino Pin | Connection |
| :--- | :--- | :--- |
| **Blue LED** | Pin 7 | Anode (+ to Pin 7 via resistor), Cathode (- to GND) |
| **Red LED** | Pin 8 | Anode (+ to Pin 8 via resistor), Cathode (- to GND) |
| **Green LED** | Pin 9 | Anode (+ to Pin 9 via resistor), Cathode (- to GND) |

*(Note: Ensure a common ground connection between your breadboard and the Arduino GND pin.)*

## 🖼 Wiring Diagram
![Wiring Diagram](path/to/your/fritzing_image.png)

## 🎥 Project Demo
[Click here to watch the demo video of the project]
(Insert the link to your video here)
    }
  }
}
