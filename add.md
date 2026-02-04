# Basic Logic Gates — Makerchip / RISC-V Context

## 1. Introduction
This document summarizes the **basic logic gates**, their functionality, and corresponding **Verilog representations**. It also maps operations with their **Boolean arithmetic**, **Boolean calculations**, and **gate implementations**.

---

## 2. Basic Gates Diagram

![Basic Logic Gates Diagram](basicgates.png)  
*Figure: Standard logic gates including AND, OR, NOT, NAND, NOR, XOR, XNOR.*

---

## 3. Operations Table

![Operations Mapping Table](Screenshot%202026-02-03%20142124.png)  
*Figure: Mapping of operations to Boolean arithmetic, Boolean calculations, Verilog code, and gates.*

---

## 4. Notes / Observations

- **Universal Gates:** NAND and NOR gates can be used to implement **any logic function**.
- **Verilog Syntax:** Gate-level modeling in Verilog uses keywords such as  
  `and`, `or`, `not`, `xor`, etc.
- **Boolean Arithmetic vs Boolean Calculation:**
  - **Boolean Arithmetic** → Symbolic form (e.g., `A + B`, `A · B`)
  - **Boolean Calculation** → Evaluated result (outputs `0` or `1`)

---

## 5. References

- Lecture slides  
- Makerchip simulations  
- RISC-V digital design modules
