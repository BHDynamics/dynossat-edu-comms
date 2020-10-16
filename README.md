# DynOSSAT-EDU-Comms (Communications System)
DynOSSAT-EDU is the first open source PocketQube educational kit compatible with CircuitPython and Arduino.

This plaform is equipped with all the necessary modules for the operation of a nanosatellite (PocketQube)
in Low Earth Orbit (LEO) that would serve as a device for teaching, training, and driving curiosity about the philosophy and technology related to NewSpace.

This repository contains the hardware files for the Communications system, the module responsible for handling radio communications.It integrates a long range LoRa module
to simulate LEO-Earth communications and a 2.4 GHz nRF52832 SoC to simulate LEO-LEO communications and to allow communication with mobile apps for teaching and simulation projects using Smartphones.

Hardware in this repository is licenced under **CERN OHL v1.2**.

## Technical details

- Based on HopeRF’s RFM96W 868 MHz LoRa module, pad-to-pad compatible with the 433 MHz RFM95W version
- Easily controlled through SPI bus
- Secondary 2.4 GHz SoC (SKB369) based on Nordic Semi nRF52832 that can act as an independent or redundant processor through I2C or SPI
- Female USB-C 2.0 connector for power and data logging (CH340E USB to UART bridge)

## Documentation

Available soon!