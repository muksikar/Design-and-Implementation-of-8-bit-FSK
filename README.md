# Design-and-Implementation-of-8-bit-FSK


## Overview

This project presents the design and implementation of an **8-bit Frequency Shift Keying (FSK) Modulation System** using **NI Multisim**. FSK is a digital modulation technique in which digital information is transmitted by varying the frequency of a carrier signal. It is widely used in wireless communication, telemetry systems, RFID, and low-power data transmission applications.

The project demonstrates the generation of an 8-bit digital data stream and its modulation into corresponding frequency-shifted signals. The design was simulated and analyzed to verify proper frequency transitions for binary data transmission.

---

## Objectives

* Design an 8-bit FSK modulation system.
* Understand the fundamentals of digital modulation techniques.
* Generate and transmit binary data using frequency variations.
* Simulate and verify FSK waveforms using NI Multisim.
* Analyze the relationship between digital input and carrier frequency.

---

## Theory

Frequency Shift Keying (FSK) is a digital modulation scheme where the carrier frequency changes according to the binary input data.

### Binary '1' (Mark Frequency)

When the input bit is '1', the carrier switches to a higher frequency:

[
s(t)=A\cos(2\pi f_1 t)
]

### Binary '0' (Space Frequency)

When the input bit is '0', the carrier switches to a lower frequency:

[
s(t)=A\cos(2\pi f_0 t)
]

where:

* (A) = Carrier amplitude
* (f_1) = Mark frequency
* (f_0) = Space frequency

The resulting waveform contains frequency transitions that represent the original binary data stream.

---

## Tools Used

| Tool                     | Purpose                     |
| ------------------------ | --------------------------- |
| NI Multisim              | Circuit Design & Simulation |
| Oscilloscope             | Waveform Observation        |
| Function Generator       | Carrier Signal Generation   |
| Digital Logic Components | Binary Data Generation      |

---

## Project Structure

```text
Design-and-Implementation-of-8-bit-FSK
│
├── Circuit_Design/
│   ├── FSK_Modulator
│
├── Simulation_Results/
│   ├── Input_Data_Waveforms
│   ├── FSK_Output_Waveforms
│
├── Reports/
│   └── Project_Report.pdf
│
└── README.md
```

---

## System Operation

### Data Generation

1. An 8-bit binary sequence is generated using digital logic sources.
2. Each bit acts as the control signal for carrier frequency selection.

### FSK Modulation

1. For logic '1', the modulator outputs the higher carrier frequency.
2. For logic '0', the modulator outputs the lower carrier frequency.
3. The output waveform continuously shifts between the two frequencies according to the input data.

### Signal Verification

1. Input and output waveforms are observed using the oscilloscope.
2. Frequency transitions are verified for correct modulation.
3. The generated waveform confirms successful transmission of the digital sequence.

---

## Simulation Results

### Example Input Data

```text
10110011
```

### Output Observation

| Input Bit | Output Frequency     |
| --------- | -------------------- |
| 1         | Mark Frequency (f₁)  |
| 0         | Space Frequency (f₀) |

Simulation results confirm that the output frequency changes correctly according to the input binary sequence.

---

## Applications

* Wireless Communication Systems
* Radio Telemetry
* RFID Systems
* Modems
* Remote Monitoring Systems
* Industrial Communication Networks
* Internet of Things (IoT) Devices

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Digital Communication Fundamentals
* Frequency Shift Keying (FSK) Modulation
* Carrier Signal Generation
* Digital Data Transmission
* NI Multisim Circuit Simulation
* Waveform Analysis and Verification

---

## Future Work

* Design and implementation of an FSK demodulator.
* Hardware realization using FPGA or microcontrollers.
* Noise and channel analysis.
* Bit Error Rate (BER) performance evaluation.
* Extension to M-ary FSK communication systems.
* Integration with complete digital communication systems.

---


---

## Acknowledgements

This project was carried out as part of the Electronics and Communication Engineering curriculum to gain practical exposure to digital modulation techniques and communication system design using NI Multisim.

---

### Repository Link

GitHub Repository: [https://github.com/muksikar/Design-and-Implementation-of-8-bit-FSK](https://github.com/muksikar/Design-and-Implementation-of-8-bit-FSK)

This format matches the PLL README style and looks professional for recruiters, internships, and portfolio showcasing.

