# Learning Roadmap

This document tracks technologies and skills I'm actively learning or plan to learn for embedded systems development.

---

## Real-Time Operating Systems

### FreeRTOS
- Task management and scheduling
- Queue-based IPC mechanisms
- Semaphores and mutexes
- Memory management schemes
- Timer services

### Zephyr RTOS
- Device tree configuration
- Kernel services
- Driver model
- Board support packages

### Bare-metal Development
- Startup code and linker scripts
- Interrupt vector tables
- Register-level peripheral configuration
- Memory-mapped I/O
- Clock and power management

---

## Microcontroller Architectures

### ARM Cortex-M Series
- **Cortex-M0/M0+:** Ultra-low power applications
- **Cortex-M3:** General purpose embedded
- **Cortex-M4:** DSP and floating-point applications
- **Cortex-M7:** High-performance real-time processing

**Topics:**
- ARM architecture and instruction set
- NVIC and exception handling
- SysTick timer
- Memory protection unit
- Debug and trace capabilities

### AVR Microcontrollers
- ATmega328P (Arduino Uno)
- ATtiny series
- AVR instruction set
- Timer/Counter peripherals

### RISC-V
- Open-source ISA fundamentals
- SiFive cores
- ESP32-C3 implementation

---

## Development Tools

### Debugging
- **OpenOCD:** On-chip debugging for ARM/RISC-V
- **Segger J-Link:** Professional debug probe usage
- **GDB:** Advanced debugging techniques

### Build Systems
- **PlatformIO:** Unified embedded development platform
- **CMake:** Cross-platform build automation

### CI/CD for Embedded
- Automated testing frameworks
- Hardware-in-the-loop testing
- Continuous integration workflows
- Automated firmware deployment

---

## Hardware Design

### PCB Design Tools
- **KiCad:** Open-source EDA suite
  - Schematic capture
  - PCB layout
  - 3D visualization
  - Component libraries
- **EAGLE:** Professional PCB design
  - Advanced routing
  - Design rule checking

### Test Equipment
- **Oscilloscopes:** Signal analysis and debugging
- **Logic Analyzers:** Digital protocol decoding
- **Multimeters:** Circuit measurement and troubleshooting

---

## Learning Priority

### High Priority (Current Focus)
1. FreeRTOS task management
2. ARM Cortex-M fundamentals
3. OpenOCD debugging workflow

### Medium Priority (Next 3-6 Months)
1. PCB design with KiCad
2. Bare-metal STM32 development
3. CI/CD for embedded projects

### Long-term Goals (6-12 Months)
1. Zephyr RTOS proficiency
2. RISC-V architecture deep dive
3. Professional debug probe usage (J-Link)

---

## Resources

### Online Courses
- ARM Cortex-M architecture courses
- FreeRTOS documentation and tutorials
- KiCad PCB design tutorials

### Books
- "The Definitive Guide to ARM Cortex-M" series
- "Mastering the FreeRTOS Real Time Kernel"
- "Embedded Systems Architecture"

### Practice Projects
- RTOS-based sensor data logger
- Custom bootloader implementation
- Multi-layer PCB design for embedded project

---

**Last Updated:** 2026-01-02
