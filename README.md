# 4-Bit Ripple Carry Adder (RCA) using NAND-Based Logic in Cadence Virtuoso

## Overview
This repository presents the complete custom VLSI design of a **4-Bit Ripple Carry Adder (RCA)** implemented using **NAND-based logic** in **Cadence Virtuoso (GPDK45 Technology)**.

The project follows a full custom design flow starting from transistor-level schematic design to physical layout implementation, verification, and simulation.

---

## Project Objectives

- Design a CMOS NAND gate at transistor level.
- Implement an XOR gate using only NAND gates.
- Design a 1-Bit Full Adder using NAND-based logic.
- Construct a 4-Bit Ripple Carry Adder by cascading Full Adder cells.
- Develop custom layouts for all building blocks.
- Perform DRC and LVS verification.
- Validate functionality through transient simulations.

---

## Design Hierarchy

```text
NAND Gate
    │
    ▼
XOR Gate
    │
    ▼
Full Adder
    │
    ▼
4-Bit Ripple Carry Adder
