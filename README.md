# Transistor-power-optimization
 "A comparative analysis of transistor-level power gating techniques using 22nm FET, 7nm FinFET, and VS-CNFET transistors, modeled and simulated in HSPICE to evaluate leakage power and total power efficiency."
# Transistor Level Power Optimization

## Introduction
As transistor scaling continues and new transistor designs emerge, selecting the ideal transistor type for low-power applications becomes crucial. Power gating is a widely used technique to reduce leakage power in CMOS circuits. This project aims to analyze and compare the performance of different transistor technologies across various power gating techniques to determine the most efficient design choices.

## Project Overview
This project investigates leakage current and total power consumption for different transistor types, including:
- **22nm FET**
- **7nm FinFET**
- **VS-CNFET (Carbon Nanotube Transistor)**

These transistor models are evaluated across various power gating techniques:
- **High-Vth and Low-Vth Footer**
- **Double Footer**
- **New Power Gating Designs**
- **Optimal Zigzag Power Gating Design**

The circuits were modeled and simulated using **HSPICE**, and performance metrics such as leakage power, total power, and delay were analyzed.

## How We Built It
1. **Circuit Design:** Developed multi-inverter circuits with different transistor technologies.
2. **Power Gating Implementation:** Applied various power gating techniques.
3. **Simulation Setup:** Used HSPICE for modeling and simulations.
4. **Data Collection:** Measured leakage power, total power, and delay for each configuration.
5. **Comparison Analysis:** Identified the most efficient transistor type for each power gating method.

## Challenges We Faced
- Modeling VS-CNFET transistors accurately in HSPICE.
- Achieving correct sizing for transistors to maintain circuit functionality.
- Managing trade-offs between leakage power reduction and delay.

## Accomplishments We Are Proud Of
- Successfully implemented and compared multiple power gating techniques.
- Identified optimal transistor choices for different power gating methods.
- Achieved significant power reductions using 22nm FET and 7nm FinFET transistors.

## Key Findings
- **Conventional Power Gating:** 22nm FET had the lowest average power at **1.107 µW**.
- **Double Footer Method:** 22nm FET transistor had the lowest power at **1.005 µW**.
- **New Footer Method:** 22nm FET provided better power efficiency than VS-CNFET.
- **Optimal Zigzag Footer:** 7nm FinFET had the best power reduction with **1.095 µW**.
- **VS-CNFET transistors exhibited significantly higher leakage current** than FET and FinFET models.

## What We Learned
- The choice of transistor type significantly impacts leakage current and power efficiency.
- Power gating techniques such as **Double Footer and New Footer** provide up to **50% power reduction**.
- **7nm FinFET is ideal for Zigzag power gating**, while **22nm FET is preferable for conventional methods**.

## What's Next
- Extend the study to newer transistor technologies, such as **2nm Gate-All-Around FETs**.
- Implement power gating techniques in larger circuit designs.
- Investigate the effect of temperature variations on power gating performance.

