# STM32 Custom Dev Board (USB Powered)

## Overview
STM32 Custom Dev Board (USB Powered) is a minimal STM32 microcontroller development board designed for embedded firmware development and hardware prototyping. The board integrates essential support circuitry including USB power input, a 3.3V LDO regulator, external crystal oscillator, SWD debug interface, boot configuration circuitry, reset switch, and GPIO LEDs for testing and debugging.

---

## Features

- USB powered (5V input)
- 3.3V LDO voltage regulator
- External crystal oscillator
- SWD / JTAG debugging interface
- Boot configuration circuit
- Reset push button
- Two GPIO indicator LEDs
- Decoupling capacitors for stable MCU operation

---

## Hardware Blocks

### Microcontroller
The core of the system is an STM32 microcontroller responsible for executing firmware and controlling peripherals.

### USB Power Section
The board receives power through a USB connector providing 5V input.

### LDO Regulator
A low dropout regulator converts the USB 5V supply to a stable 3.3V supply required by the STM32 MCU.

### Clock Circuit
An external crystal oscillator with load capacitors provides a stable clock source for accurate timing.

### Boot Configuration
Boot pins are configured using resistors to define the startup mode of the microcontroller.

### Reset Circuit
A push button connected to the NRST pin allows manual reset of the system.

### Debug Interface
A SWD/JTAG connector allows firmware programming and debugging using tools such as:

- ST-Link
- J-Link
- OpenOCD

### LEDs
Two GPIO connected LEDs are provided for firmware testing and status indication.

---

## Block Diagram
USB Power → LDO Regulator (3.3V) → STM32 MCU
↓
Clock | Boot | Reset | SWD Debug | LEDs

---

## Applications

- Embedded firmware development
- STM32 learning platform
- Hardware prototyping
- Peripheral interface testing
- Embedded systems education

---

## Tools Used

- Altium Designer / KiCad / EasyEDA (schematic & PCB design)
- STM32CubeIDE (firmware development)
- ST-Link debugger

---

## Author

**Harsh Saini**

LinkedIn  
https://www.linkedin.com/in/sainiharsh-in/

GitHub  
https://github.com/harsh-hw-dev
