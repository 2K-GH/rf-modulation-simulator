# RF Modulation Simulator

**RF Modulation Simulator** is an interactive educational platform designed to visualize and compare the behavior of common digital modulation techniques used in modern wireless communication systems. The project provides real-time waveform rendering, spectrum visualization, and noise-response demonstrations for OOK, FSK, PSK, and CSS (LoRa) modulation schemes.

<p align="center">
  <img src="rf_modulation.gif" alt="RF Modulation Demo">
</p>

---

## 📡 Project Overview

Understanding wireless communication often requires moving between mathematical theory and real-world signal behavior. This project bridges that gap by allowing users to observe how information is encoded, transmitted, and affected by noise across different modulation schemes.

The simulator was developed as an educational tool for:

* Electronics Engineering Students
* Telecommunications Students
* SDR Enthusiasts
* Amateur Radio Operators
* Wireless System Developers
* RF Researchers

---

## 🛠 Supported Modulation Techniques

### 📶 On-Off Keying (OOK)

OOK represents binary information through the presence or absence of a carrier signal.

#### Common Applications

* Wireless Doorbells
* Gate Controllers
* Low-Cost Remote Controls
* 315/433 MHz ISM Devices

#### Engineering Characteristics

* Simplest digital modulation scheme
* Lowest implementation complexity
* High susceptibility to interference and replay attacks
* Excellent power efficiency

---

### 📶 Frequency Shift Keying (FSK)

FSK encodes information by shifting between discrete carrier frequencies.

#### Common Applications

* POCSAG Paging Systems
* APRS Networks
* TPMS Sensors
* Industrial Telemetry

#### Engineering Characteristics

* Better noise immunity than OOK
* Constant amplitude transmission
* Reliable operation in noisy environments
* Widely used in legacy radio systems

---

### 📶 Phase Shift Keying (PSK)

PSK conveys information through changes in carrier phase while maintaining constant amplitude and frequency.

#### Common Applications

* GPS Systems
* Satellite Communications
* Digital Radio Systems
* Wireless Networking

#### Engineering Characteristics

* Improved spectral efficiency
* Foundation of many modern communication standards
* Excellent bandwidth utilization
* Robust digital communication performance

---

### 📶 Chirp Spread Spectrum (CSS)

CSS uses continuously varying frequency chirps to spread information across a wider bandwidth.

#### Common Applications

* LoRaWAN
* Meshtastic
* Long-Range IoT Devices
* Environmental Monitoring Systems

#### Engineering Characteristics

* Exceptional long-range capability
* High interference resistance
* Operates below noise floor conditions
* Optimized for low-power communication

---

## 🧠 Engineering Highlights

### Real-Time Waveform Visualization

Each modulation scheme is rendered dynamically, allowing direct observation of how binary data alters the transmitted carrier signal.

### Spectrum Analysis

The simulator provides frequency-domain insight into each modulation technique, demonstrating bandwidth utilization and spectral behavior.

### Noise Injection Demonstration

Users can introduce noise into the communication channel and observe how different modulation schemes respond to interference.

### LoRa Educational Mode

The CSS implementation includes adjustable spreading-factor demonstrations to illustrate the trade-off between data rate and communication range.

---

## 🎯 Learning Objectives

The simulator helps demonstrate:

* Amplitude-Based Modulation
* Frequency-Based Modulation
* Phase-Based Modulation
* Spread Spectrum Communication
* Signal Integrity
* Noise Resistance
* Spectrum Occupancy
* SDR Fundamentals
* Wireless Communication Principles

---

## 🚀 Deployment

1. Clone the repository:

```bash
git clone https://github.com/2K-GH/rf-modulation-simulator.git
```

2. Open:

```text
rf_modulation_simulator.html
```

3. Launch in any modern web browser.

No installation or external dependencies are required.

---

## 🔬 Future Improvements

* QPSK Visualization
* QAM Demonstrations
* OFDM Concepts
* Constellation Diagrams
* Waterfall Spectrum Display
* BER Analysis Tools
* IQ Signal Visualization
* Additional SDR-Oriented Examples

---

## ⚖ License

Distributed under the MIT License.

---

## Disclaimer

This project is intended for educational, research, and demonstration purposes only. References to real-world communication systems are provided solely to explain wireless communication concepts.
