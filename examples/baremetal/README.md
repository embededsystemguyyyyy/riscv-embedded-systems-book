# Bare-Metal RISC-V Examples

These examples demonstrate:
- Startup code
- Register-level programming
- Minimal toolchain usage

All examples are based directly on the code and teachings from **"Open Hardware Revolution: Practical Embedded Design with RISC-V"** by Dean Wilson.

## Available Examples

- **blink** — LED blinking example from Chapter 4.1 (First Program)

## Getting Started

1. Choose a board from the `boards/` folder
2. Navigate to the example folder
3. Follow the example-specific README.md
4. Build with `make`
5. Flash using OpenOCD (see board documentation)

## Toolchain

Use the RISC-V GNU toolchain as described in Chapter 3:
- `riscv32-unknown-elf-gcc`
- `-march=rv32imac -mabi=ilp32`

## Structure

Each example contains:
- `README.md`
- `Makefile`
- `linker.ld`
- `src/main.c`
- `src/startup.S` (when needed)
