# SiFive Boards

This folder contains notes and configurations for SiFive RISC-V boards.

---

## MCU Overview
- RISC-V based SoCs (FE310 and others)
- Popular for education and development
- Reference: Chapter 3.2 Development Boards Overview

---

## Toolchain
- `riscv32-unknown-elf-gcc` or `riscv64-unknown-elf-gcc`
- Use `-march=rv32imac -mabi=ilp32`

---

## Debug Method
- OpenOCD + GDB
- On-board debug interface on HiFive1
