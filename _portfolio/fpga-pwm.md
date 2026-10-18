---
title: "FPGA PWM Duty-Cycle Controller"
excerpt: "Moore-state-machine logic and a live seven-segment duty-cycle readout on an Intel MAX 10 FPGA."
collection: "portfolio"
permalink: "/portfolio/fpga-pwm/"
order: 3
share: false
comments: false
---

**November 2025 · Digital logic final project · Two-person team**

We designed a pushbutton-controlled PWM duty-cycle controller on a Terasic DE10-Lite board with an Intel MAX 10 FPGA. We developed a Moore state diagram together before implementing the design in VHDL and Quartus Prime schematic capture.

## My contribution

- Implemented the next-state logic and D flip-flop state register.
- Built the count-value block and BCD-to-seven-segment decoder for the live duty-cycle display.
- Reviewed the PWM output block and corrected logic errors.

## Design

Pushbuttons adjusted a five-bit duty-cycle value across 32 steps. A clock-divider chain derived the timing signals from the board's 50 MHz clock, while seven-segment displays showed the selected value.

**Tools:** Intel MAX 10, Terasic DE10-Lite, VHDL, Quartus Prime, schematic capture, digital logic.
