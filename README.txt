🚀 Analog Signal Conditioning Module
📌 Overview

Analog-only signal conditioning system for extracting a usable signal from a noisy composite input

Designed for electrically hostile environments with interference and broadband noise

Developed as part of a hackathon challenge (Syntheix’26 – Electrical Stream)

🎯 Objective

Extract the 6 kHz usable signal component from a composite analog input

Suppress interference (low-frequency drift, structured noise, high-frequency noise, broadband noise)

Ensure stability, repeatability, and robustness under varying conditions

⚙️ System Approach

Multi-stage analog filtering architecture

Noise suppression using:

Low-pass filter

High-pass filter

Band-pass filter

Butterworth filter (for smooth frequency response)

Manual tuning via potentiometer for adaptive signal conditioning

🛠️ Tools & Technologies

Circuit Design: KiCad (PCB design in progress)

Simulation: LTspice (transient + frequency analysis)

Analysis & Visualization: MATLAB (calculations, FFT, graphs)

📊 Key Features

Pure analog design (no microcontrollers/DSP as per constraints)

Real-time manual adaptability

Stable output without oscillations or clipping

Frequency-domain validation using FFT

Robust noise and interference suppression

📈 Results

Successful extraction of dominant usable signal

Significant attenuation of unwanted frequency components

Verified through simulation and graphical analysis

🚧 Current Progress

✅ Circuit design completed

✅ Simulation and validation completed (LTspice + MATLAB)

⏳ PCB design in KiCad (not yet fabricated)

🔮 Future Work

PCB fabrication and testing

Hardware validation in real noisy environments

Optimization for compact and low-noise layout

🧠 Key Learnings

Practical challenges in analog signal conditioning

Trade-offs in filter design and stability

Importance of frequency-domain analysis (FFT)

Real-world noise handling without digital processing
