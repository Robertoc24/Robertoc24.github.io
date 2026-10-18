---
title: "Autonomous Warehouse Robot"
excerpt: "Designing a compact robot for warehouse material handling: maze navigation, payload pickup, and elevated sorting, with an integrated scissor lift and claw."
collection: "portfolio"
permalink: "/portfolio/warehouse-robot/"
order: 1
share: false
comments: false
---

**March–May 2026 · MXET 250 · Three-person team**

Our team designed a robot for a warehouse logistics challenge: locate color-coded foam blocks, transport them through a maze, and place them on an elevated sorting platform. The design brought together a mobile base, payload-handling mechanism, and sensor-based control within a 40 × 40 × 40 cm resting envelope.

## Material-handling workflow

The task required coordinating movement, pickup, lifting, and placement. An omni-wheel base supported maneuvering through the maze, while a claw and scissor lift were designed to collect blocks at floor level and deliver them to the raised platform. Two time-of-flight sensors and a color sensor supported the planned navigation and sorting logic.

## My contribution

- Led chassis design and developed the full SolidWorks CAD assembly and motion simulation to check how the base and lifting mechanism worked together.
- Wrote early movement pseudocode and contributed to block-based programming on a REV Robotics Control Hub.
- Debugged and refined a teammate's Raspberry Pi 4 Python control code for the sensor-based system.

## Compact mechanical design

The TETRIX MAX chassis integrated the omni-wheel base, scissor lift, and claw into one structure. Extending the lift pulled the wheels inward, changing the base footprint as the mechanism moved. A 12 V NiMH supply powered the system.

To address bevel-gear alignment issues, the team redesigned the lift around symmetric planetary-gearbox motors driving it directly. This iteration connected mechanical reliability with the broader demands of payload handling and control integration.

## Controls and integration

We developed two control approaches: gamepad-based TeleOp on the REV Control Hub and a separate Raspberry Pi 4 Python system for sensor-based navigation and sorting.

The final demonstration used manual driving. Autonomous navigation and color sorting were not finalized, with lift reliability limiting integration-test time. My work spanned the mechanical assembly, movement logic, and control-code debugging needed to connect those subsystems.

**Tools:** SolidWorks, TETRIX MAX, REV Control Hub, block-based programming, Raspberry Pi 4, Python, time-of-flight and color sensors.
