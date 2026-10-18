---
title: "Analog PWM Fan Controller"
excerpt: "Simulation-only design of a temperature-controlled PWM circuit for a 12 V fan, with a simulated 25.8 kHz triangle-wave generator."
collection: "portfolio"
permalink: "/portfolio/analog-pwm-fan/"
order: 5
share: false
comments: false
---

**Design and simulation · No physical build**

This circuit explores analog PWM control of a 12 V, four-pin fan using a temperature-related voltage input.

## Design targets

- Fan off below a 2.5 V input.
- A 50% PWM duty cycle at 2.5 V, increasing to 100% at 4.5 V.
- PWM frequency near 25 kHz.

## Circuit approach

The triangle-wave generator uses a TLV2372IP dual rail-to-rail op-amp: one section as a Schmitt-trigger comparator and the other as a Miller integrator. A divider from the single 12 V supply sets a reference near 3.39 V. An earlier version used LM741 op-amps.

## Simulation result

The triangle-wave stage produced approximately **3.08 V peak-to-peak**, a **2.60 V DC offset**, and a frequency of **25.8 kHz** in Multisim. These values describe the simulated oscillator; the complete fan response has not been verified on physical hardware.

**Tools:** Multisim, op-amp circuit design, analog PWM.
