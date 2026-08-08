---
layout: default
title: Chris McCreary | Hardware, Test, and Tooling
description: Electrical test engineering, electronics development, rapid prototyping, embedded systems, mechanical design, and practical technical tooling.
---

# Chris McCreary

## Hardware development, electrical test, rapid prototyping, and systems integration

I build practical hardware and tools for ambiguous engineering problems. My background spans more than 20 years of RF communications, electronics repair, electrical test, embedded systems, rapid prototyping, systems integration, and technical leadership.

The work shown here focuses on public, shareable examples: test fixtures, PCB and library workflows, embedded utilities, CAD assemblies, vehicle electronics experiments, and tools that make repeatable engineering work easier.

[GitHub](https://github.com/Phoenixjack) · [LinkedIn](https://www.linkedin.com/in/chris-mccreary-9aa9b7138/) · [GrabCAD](https://grabcad.com/library/pan-tilt-platform-2)

---

## Areas of work

### PCB and electronics

- KiCad and Altium design support
- footprints, symbols, 3D models, and library organization
- microcontroller boards, driver boards, sensor interfaces, and RF antenna experiments
- Gerber review, board bring-up, soldering, rework, and assembly feedback
- additive PCB process support and verification boards

### Electrical test and troubleshooting

- DAQ interfaces, signal conditioning, and power monitoring
- RF, environmental, EMI, and life-cycle test preparation
- fixtures, adapters, diagnostic access points, and repeatable bench setups
- failure isolation, procedures, trade studies, and maintainability improvements
- practical in-house hardware that reduces test burden and exposes problems early

### Embedded and data systems

- ESP8266/ESP32, RP2040/Pico, Raspberry Pi, and Arduino-class hardware
- C/C++, sensors, I2C, serial interfaces, and remote configuration
- MQTT, Node-RED, time synchronization, diagnostics, and disconnected test environments
- browser-controlled fixtures and purpose-built bench utilities

### Mechanical design and fabrication

- Fusion 360 and SolidWorks
- 3D printing, CNC parts, enclosures, mounts, molds, and potting aids
- ruggedized housings, cable and harness interfaces, and electromechanical fixtures
- designs developed with assembly, repair, and real operating constraints in mind

---

## Selected public work

<p>
  <a href="https://github.com/Phoenixjack/Pan-Tilt-Platform">
    <img src="https://raw.githubusercontent.com/Phoenixjack/Pan-Tilt-Platform/main/images/PanTiltPlatform-Overall-Isometric.png" alt="Pan-tilt test platform CAD assembly" width="48%">
  </a>
  <a href="https://github.com/Phoenixjack/vehicle-lighting-addon">
    <img src="https://raw.githubusercontent.com/Phoenixjack/vehicle-lighting-addon/main/images/installation-overhead-conceptual.png" alt="Conceptual overhead-console vehicle electronics installation" width="48%">
  </a>
</p>

### [Pan-Tilt Platform](https://github.com/Phoenixjack/Pan-Tilt-Platform)

A paused but well-developed prototype combining an ESP8266 controller, browser-based positioning, stepper hardware, a tripod interface, and a mechanical pan/tilt assembly intended for RF, sensor, camera, or directional testing. The CAD files are also available on [GrabCAD](https://grabcad.com/library/pan-tilt-platform-2).

### [Vehicle Lighting Add-on](https://github.com/Phoenixjack/vehicle-lighting-addon)

A functional hobbyist prototype that uses an ESP8266 and ADXL345 accelerometer to detect deceleration, filter motion data, apply configurable thresholds, and drive an auxiliary lighting output with optional ambient-light scaling.

### [I2C Debug Tool](https://github.com/Phoenixjack/i2c-debug-tool)

An Arduino serial shell for hardware bring-up: scan a bus, identify likely devices, inspect registers, read and write values, and save recurring custom-device information.

---

## KiCad library tooling

The KiCad projects are separate on purpose. Each one explores a recognizable part of the larger library-management problem while the longer-term [KiCARR](https://github.com/Phoenixjack/KiCARR) architecture develops.

![KiCARR component ecosystem](assets/kicarr-ecosystem.svg)

### [KIA - KiCad Import Assistant](https://github.com/Phoenixjack/kicad-import-assistant)

Cautious intake and transformation of downloaded KiCad assets: source detection, naming, per-item import/replace/skip choices, preview, backups, writes, and source archiving.

### [KMFDM - KiCad Management of Field-Defined Metadata](https://github.com/Phoenixjack/kmfdm)

Scanning, metadata editing, policy auditing, pending changes, safe saves, and history for native KiCad symbol and footprint libraries.

### [KML - KiCad Metadata Lookup](https://github.com/Phoenixjack/kicad-metadata-lookup)

Experimental provider-backed component lookup and preview, with user-supplied API keys kept in ignored local data.

### [KiCARR](https://github.com/Phoenixjack/KiCARR)

The future cohesive desktop companion intended to bring those workflows together through queue, library, audit, changes, history, settings, and provider-preview concepts.

KiCARR is still at the planning/bootstrap stage. The diagram describes product direction, not a finished integrated application.

---

## How I approach development

1. Start with the real operating constraint, not an idealized specification.
2. Build a small fixture, board, interface, or proof of concept that can answer a useful question.
3. Test early enough to expose integration and maintainability problems.
4. Record results, weak points, and tradeoffs so the work remains useful even if the final direction changes.
5. Refine successful ideas for repeatability, repairability, and handoff.

---

## Resume

The [full public resume](resume/) includes role-family translations, complete experience from 1999 to the present, selected technical work, tools, credentials, and a print-friendly layout. Direct contact information, clearance details, and sensitive operational specifics are intentionally omitted from the public version.
