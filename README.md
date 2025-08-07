# 👋 Hi, I'm Bruno Bavaresco Zaffari
*Olá 🇧🇷! · 你好 🇨🇳! · ¡Hola 🇪🇸! ·*  \
*안녕하세요 🇰🇷! · こんにちは 🇯🇵! · Привет 🇷🇺! ·* \
*Bonjour 🇫🇷! · Ciao 🇮🇹! · Hallo 🇩🇪! · مرحبًا 🇸🇦! · नमस्ते 🇮🇳!*

🎓 Computer Engineering graduate focused on embedded systems, applied AI, and hardware–software integration. 


***[Core Technologies](#%EF%B8%8F-core-technologies)***\
***[Featured Projects](#-featured-projects)***\
***[Get in touch](#-What-i-believe)***
  
---

## 🛠️ Core Technologies

- **Languages:** C, C++, Python, VHDL, SQL
- **Embedded Platforms:** Cortex-M0 (CubeIDE), ESP32 (ESP-IDF), FreeRTOS, Zephyr
- **AI & ML:** PyTorch, CNNs, Torch C++, embedded inference, signal-based feature extraction  
- **Build & Tooling:** PyBind11, CMake, Docker, Conan, GitHub Actions, Make, GCC/MSVC
- **Communication & Control:** TCP/UDP, MQTT, serial protocols(I2C, UART,SPI,1-Wire, etc), interrupts (ISR), thread-safety, servers
- **Focus Areas:** C/C++ systems, embedded, AI systems, safety-critical, dependable design, automation, hardware–software co-design, vector-based retrieval (FAISS), hybrid packaging (C++/Python), DevOps

---

## 💼 Featured Projects

### 🔹 [Cooling-Link EcoSystem](https://github.com/bbzaffari/Cooling-Link-Controller)
Modular system-architecture for wireless environmental monitoring and control in cold-storage chambers — **scalable, dependable**. \
Combines **ESP32** nodes, LoRa + MQTT communication, dew-point-aware logic, and scalable sensor-actuator coordination.
Includes custom drivers, FreeRTOS tasks, hardware integration, and analysis.\
**Delivered at U$ 120** compared to R$ 3000 charged by alternative commercial solutions. —  tailored for Brazilian agribusiness.

![ESP32](https://img.shields.io/badge/Framework-ESP--IDF-orange)
![Comm](https://img.shields.io/badge/Comm-LoRa%20+%20MQTT-green)
![System](https://img.shields.io/badge/System-Critical--Aware-red)
![Build System](https://img.shields.io/badge/Build-CMake-blue)


---

### 🔹 [PureCPP System](https://github.com/bbzaffari/purecpp_sp)
Cross-language C++/Python retrieval engine for modular vector processing and hybrid ML workflows.  
Features **embedding pipelines, FAISS search, PyBind11 bindings**, and **OpenMP-accelerated** document operations, packed in reproducible **manylinux** wheels and CI-driven builds.

![Language](https://img.shields.io/badge/Language-C++20-blue)
![Bindings](https://img.shields.io/badge/Bindings-PyBind11-brightgreen)
![Build](https://img.shields.io/badge/Build-CMake-blue)
![CI](https://img.shields.io/badge/CI-GitHub%20Actions-purple)
![Packaging](https://img.shields.io/badge/Wheels-manylinux-critical)
![Parallelism](https://img.shields.io/badge/Parallel-OpenMP-blueviolet)

---
### 🔹 [PS/2 VHDL Driver](https://github.com/bbzaffari/Driver-PS2-Mouse)
RTL module for PS/2 mouse decoding, written in **VHDL** and verified with **functional testbenches and synthesis reports**.  
Includes finite state machine design, and full **ASIC-oriented flow**, with post-synthesis timing validation and Cadence toolchain support.

![VHDL](https://img.shields.io/badge/Language-VHDL-yellow)
![Design](https://img.shields.io/badge/Flow-ASIC%20Synthesis-critical)
![Testbench](https://img.shields.io/badge/Verification-Testbench-blue)
![Platform](https://img.shields.io/badge/Tools-Cadence-brightgreen)


---

### 🔹 [Messaging Kernel Module](https://github.com/bbzaffari/Messaging-Kernel-Module)  
**Loadable Kernel Module (LKM)** enabling **message queueing between user-space processes** via a `/dev/mq` ***Character Device*** interface.  
Implements **per-process circular buffers**, a **control block registry**, and **spinlock-based synchronization** for concurrent messaging.  
Includes a C user-space client for interaction and was **cross-compiled with Buildroot** for embedded Linux systems.

![Linux](https://img.shields.io/badge/Kernel-Linux-black)
![Build](https://img.shields.io/badge/Build-Cross--compiled-blueviolet)
![Tool](https://img.shields.io/badge/Tool-Buildroot-informational)


---
### 🔹 [Vigenère Cipher Cryptanalysis Tool](https://github.com/bbzaffari/VigenereDecryptor)

This tool performs **automated cryptanalysis** of messages encrypted with the **Vigenère cipher**, a classical polyalphabetic substitution technique.  
Designed for educational purposes, it showcases the application of **frequency analysis and statistical inference** to deduce the key and decrypt a ciphertext. *Python-based cryptanalysis tool for the classical Vigenère cipher — developed with academic rigor and statistical methods.*

![Language](https://img.shields.io/badge/Language-Python-blue)
![Crypto](https://img.shields.io/badge/Focus-Cryptanalysis-critical)
![Stats](https://img.shields.io/badge/Analysis-χ²%20%7C%20IC%20%7C%20Kasiski-informational)
![Report](https://img.shields.io/badge/Format-IEEE--style--Report-lightgrey)

---

## 🧠 What I Believe

> “Firmware, networks, memory and learning — it’s all part of the same reliability surface.”

🧩 I approach systems as unified layers — from bits to models.  
📐 I aim for technical rigor, clean documentation, and reusable architecture.  
🌍 I’m constantly exploring intersections between AI, embedded design, and resilient engineering.

---

## 📫 Reach Me

- 📧 bruno.zaffari@edu.pucrs.br  
- 💼 [LinkedIn](https://www.linkedin.com/in/bruno-bavaresco-zaffari)  
- 🧠 [TCC Final Project Thesis](https://github.com/bbzaffari/TCC-Final-Project-Thesis)

---
