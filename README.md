# 👋 Hi, I'm Bruno Bavaresco Zaffari
*Hallo 🇩🇪! · Olá 🇧🇷! · 你好 🇨🇳! · ¡Hola 🇪🇸! ·*  \
*안녕하세요 🇰🇷! · こんにちは 🇯🇵! · Привет 🇷🇺! ·* \
*Bonjour 🇫🇷! · Ciao 🇮🇹! · مرحبًا 🇸🇦! · नमस्ते 🇮🇳!*

🎓 Computer Engineering graduate focused on embedded systems, applied AI, and hardware–software integration. 


🛠️ [***Core Technologies***](#%EF%B8%8F-core-technologies) \
💼 [***Featured Projects***](#-featured-projects)

[***Get in touch***](#-what-i-believe)
  
---

## 🛠️ Core Technologies

- **Languages:** C, C++, Python, VHDL, SQL
- **Embedded Platforms:** Cortex-M0 (CubeIDE), ESP32 (ESP-IDF), FreeRTOS, Zephyr
- **AI & ML:** PyTorch, CNNs, Torch C++, embedded inference, signal-based feature extraction  
- **Build & Tooling:** PyBind11, CMake, Docker, Conan, GitHub Actions, Make, GCC/MSVC
- **Communication & Control:** TCP/UDP, MQTT, serial protocols(I2C, UART,SPI,1-Wire, etc), interrupts (ISR), thread-safety, servers
- **Core Fields:** C/C++ systems, embedded, AI systems, safety-critical, dependable design, automation, hardware–software co-design, vector-based retrieval (FAISS), hybrid packaging (C++/Python), DevOps


---
## 💼 Featured Projects


### 🔹 [PureCPP System](https://github.com/bbzaffari/purecpp_sp)
Cross-language C++/Python retrieval engine for modular vector processing and hybrid ML workflows.  
Features **embedding pipelines, FAISS search, PyBind11 bindings**, and **OpenMP-accelerated** document operations, packed in reproducible **manylinux** wheels and CI-driven builds.

[![Language](https://img.shields.io/badge/Language-C++20-blue)]()
[![Bindings](https://img.shields.io/badge/Bindings-PyBind11-brightgreen)]()
[![Build](https://img.shields.io/badge/Build-CMake-blue)]()
[![CI](https://img.shields.io/badge/CI-GitHub%20Actions-purple)]()
[![Packaging](https://img.shields.io/badge/Wheels-manylinux-critical)]()
[![Parallelism](https://img.shields.io/badge/Parallel-OpenMP-blueviolet)]()
---

### 🔹 [Memory-Mapped I/O (MMIO) - tDES](https://github.com/bbzaffari/MMIO-tripleDes-VHDL-core)

Hardware crypto module with **Triple DES core in VHDL**, exposed via **memory-mapped I/O registers** on a RISC-compatible SoC.
Implements full register binding to the RTL provided by vendors, enabling read/write operations through system calls on a lightweight **RTOS (UCX/OS)**.
Supports multiple cipher modes *(**ECB**, **CBC**, **CTR**)*.
Validated end-to-end through data encryption tests and binary inspection using `hexdump`.

[![MMIO](https://img.shields.io/badge/Interface-MMIO-orange)]()
[![RTL](https://img.shields.io/badge/Core-VHDL-green)]()
[![Dockerized](https://img.shields.io/badge/Environment-Docker--Ready-2496ED?logo=docker&logoColor=white)]()
[![Virtualization](https://img.shields.io/badge/Virtualization-HW%2FSW-lightgrey.svg)]()
[![CPU](https://img.shields.io/badge/CPU-RISC%20Architecture-informational)]()



---
### 🔹 [PS/2 VHDL Driver](https://github.com/bbzaffari/Driver-PS2-Mouse)
RTL module for PS/2 mouse decoding, written in **VHDL** and verified with **functional testbenches and synthesis reports**.  
Includes finite state machine design, and full **ASIC-oriented flow**, with post-synthesis timing validation and Cadence toolchain support.

[![VHDL](https://img.shields.io/badge/Language-VHDL-yellow)]()
[![Design](https://img.shields.io/badge/Flow-ASIC%20Synthesis-critical)]()
[![Testbench](https://img.shields.io/badge/Verification-Testbench-blue)]()
[![Platform](https://img.shields.io/badge/Tools-Cadence-brightgreen)]()


---

### 🔹 [Messaging Kernel Module](https://github.com/bbzaffari/Messaging-Kernel-Module)  
**Loadable Kernel Module (LKM)** enabling **message queueing between user-space processes** via a `/dev/mq` ***Character Device*** interface.  
Implements **per-process circular buffers**, a **control block registry**, and **spinlock-based synchronization** for concurrent messaging.  
Includes a C user-space client for interaction and was **cross-compiled with Buildroot** for embedded Linux systems.

[![Linux](https://img.shields.io/badge/Kernel-Linux-black)]()
[![Build](https://img.shields.io/badge/Build-Cross--compiled-blueviolet)]()
[![Tool](https://img.shields.io/badge/Tool-Buildroot-informational)]()


---
### 🔹 [Vigenère Cipher Cryptanalysis Tool](https://github.com/bbzaffari/VigenereDecryptor)

This tool performs **automated cryptanalysis** of messages encrypted with the **Vigenère cipher**, a classical polyalphabetic substitution technique.  
Designed for educational purposes, it showcases the application of **frequency analysis and statistical inference** to deduce the key and decrypt a ciphertext. *Python-based cryptanalysis tool for the classical Vigenère cipher — developed with academic rigor and statistical methods.*

[![Language](https://img.shields.io/badge/Language-Python-blue)]()
[![Crypto](https://img.shields.io/badge/Focus-Cryptanalysis-critical)]()
[![Stats](https://img.shields.io/badge/Analysis-χ²%20%7C%20IC%20%7C%20Kasiski-informational)]()
[![Report](https://img.shields.io/badge/Format-IEEE--style--Report-lightgrey)]()

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
- 📄 [TCC Final Project Thesis](https://github.com/bbzaffari/TCC-Final-Project-Thesis)
  > ***Confidentiality Notice:*** Due to the need to preserve strategic information until the patent process is fully regularized, the thesis project remains private and full access is currently restricted. 
  > Full public disclosure will only be granted once all legal and procedural matters are resolved.
  > If you are an interviewer and want to see send me an email. I will be more than happy to send.

---
