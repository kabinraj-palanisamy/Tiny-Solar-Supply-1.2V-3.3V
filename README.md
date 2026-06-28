# Tiny Solar Supply — 1.2V to 3.3V Boost Converter
A compact solar-powered boost converter PCB built in KiCad,
based on the Elektor design by Clemens Valens (Circuit Special 2023).

## Overview
Converts a 1.2V Ni-MH AA battery (charged via solar panel) into a
regulated 3.3V output suitable for microcontroller applications.
Includes automatic day/night switching via 2N7002 MOSFET.

## Specifications
- Input voltage: 1V – 12V
- Output voltage: 3.3V regulated
- Max output current: 100mA (AP3015A)
- Switching IC: AP3015 micropower step-up DC/DC converter

## Tools
KiCad 10.0.1

## Credit
Original circuit design: Clemens Valens, Elektor Circuit Special 2023
