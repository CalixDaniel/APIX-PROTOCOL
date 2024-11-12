# APIX-PROTOCOL 

This repository contains the Verilog implementation of an APIX Transmitter-Receiver System, along with testbenches and waveform analysis using GTKWave. The project simulates high-speed communication between a transmitter and receiver, focusing on pixel data transmission and integrity checks.

## PROJECT OVERVIEW 

APIX (Automotive Pixel Link) is a high-speed digital communication interface used in automotive applications for transmitting video and control signals. This project demonstrates a simple simulation of the APIX protocol, focusing on:

Data transmission from the transmitter (APIX_TX).
Data reception and decoding at the receiver (APIX_RX).
Pixel data handling for display systems.

## KEY FEATURES 

Clock Synchronization: Synchronizes transmitter and receiver using a generated clock signal.

Data Transmission: Sends 24-bit pixel data (pixel_data[23:0]) from the transmitter to the receiver.

Error Detection: Includes an error flag (error_flag) for data integrity checks.

Waveform Analysis: Uses GTKWave to verify signal timing, clock synchronization, and data accuracy.

Display System Integration: Simulates a basic display system with horizontal sync (hsync) and vertical sync (vsync) signals.

## SIMULATION TOOLS 

Verilog: HDL for designing the transmitter and receiver modules.

GTKWave: Waveform viewer for analyzing signal timing and data flow.

Vivado/ModelSim: (Optional) for synthesis and additional simulation.
