# Solar Cell Module I-V and P-V Characteristics

## Understanding Solar Cell I-V Characteristics

The I-V characteristic curve shows the relationship between current (I) and voltage (V) for a photovoltaic (PV) cell, module, or array.

## Understanding Solar Cell P-V Characteristics

The P-V characteristic curve demonstrates the relationship between voltage (V) and power (P) output from the PV cell or panel.

## Key Parameters in the I-V Curve

- **Short Circuit Current (I<sub>SC</sub>):** The maximum current when the voltage is zero.
- **Open Circuit Voltage (V<sub>OC</sub>):** The maximum voltage when the current is zero.
- **Maximum Power Point (P<sub>MP</sub>):** The point on the curve where the product of current and voltage (I × V) is maximized, indicating the optimal operating condition for maximum power output.

## Important Points on the Curve

- The I-V curve is represented in red, and the P-V curve is represented in blue.
- The power from the solar cell is given by the equation \( P = V \times I \).
- The maximum power point (P<sub>MP</sub>) is indicated where the power curve peaks.

## Operating Conditions for Maximum Efficiency

To achieve the maximum power output, the solar cell should operate at the voltage and current corresponding to the maximum power point (V<sub>MP</sub>, I<sub>MP</sub>).

![image](https://github.com/user-attachments/assets/69989189-11ec-4639-be56-75025c13db36)

## Measurement Setup

1. **I-V Curve Measurement:** The I-V curve measurement is performed by applying a series of voltages to the solar cell device.

## Procedure for I-V Measurement

1. **Step 1:** Apply a series of voltages to the solar cell.
2. **Step 2:** Measure the current flowing through the device at each applied voltage.

## Instruments and Connections

- **Voltmeter:** Connected in parallel to the solar cell to measure the supplied voltage.
- **Ammeter:** Connected in series with the solar cell to measure the current flowing through the device.

## Circuit Components

- **Internal Resistance (R<sub>i</sub>):** Represents the inherent resistance within the solar cell.
- **Variable Resistor (R<sub>v</sub>):** Adjusts the voltage applied to the solar cell.
- **Solar Cell:** The device under test, exposed to sunlight or an equivalent light source.

![image](https://github.com/user-attachments/assets/6357f58f-fc1d-4787-9877-a16c5ed7cc31)

## Objective of the Experiment

- To plot the I-V characteristic curve by varying the voltage and recording the corresponding current, providing insights into the performance and efficiency of the solar cell.
- To accurately simulate the behavior of a solar cell under varying conditions using the given model components and equations.
- To understand how different parameters (e.g., temperature, solar irradiation) affect the output current and voltage of the solar cell.

## Components of the Solar Cell Model

- **I<sub>ph</sub>:** Photogenerated current.
- **I<sub>D</sub>:** Diode current.
- **I<sub>pv</sub>:** Output current of the solar cell.
- **V<sub>pv</sub>:** Terminal voltage of the solar cell.
- **R<sub>s</sub>:** Series resistance.
- **R<sub>sh</sub>:** Shunt resistance.
  
![image](https://github.com/user-attachments/assets/5dfc1a22-de50-4e2b-a32f-438138e4a048)

![image](https://github.com/user-attachments/assets/de65e372-cad8-4109-83fe-7b9232e7eb61)

## Key Equation

 I = Iph - Is*(e^((V+I*Rs)/(N*Vt))-1) - Is2*(e^((V+I*Rs)/(N2*Vt))-1) - (V+I*Rs)/R

Where:
- **I<sub>s</sub>** and **I<sub>s2</sub>** are the diode saturation currents.
- **V<sub>t</sub>** is the thermal voltage.
- **N** and **N<sub>2</sub>** are the quality factors (diode emission coefficients).
- **I<sub>ph</sub>** is the solar-generated current.

## Simulation Model

### Solar Cell Module Simulink Model

![image](https://github.com/user-attachments/assets/eda9cae2-8902-4c67-9668-9d67f26eb1c6)

### Sub-Systems

![image](https://github.com/user-attachments/assets/b61ff608-2810-4abc-949f-c944557a4a8b)

### Results

![image](https://github.com/user-attachments/assets/4687ecc3-f7e0-48ec-ac8b-db2ed20a71d4)
![image](https://github.com/user-attachments/assets/075da6ca-30ab-4b6b-ab03-24f7a3019dd2)

![image](https://github.com/user-attachments/assets/4992d475-ce58-4fe5-9e1b-d750796d2efc)
![image](https://github.com/user-attachments/assets/074b39d0-18ab-4032-be98-2e07b8f6111e)




