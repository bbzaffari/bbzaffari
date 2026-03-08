# 👋 Hi, I'm Bruno Bavaresco Zaffari
*Olá 🇧🇷! · 你好 🇨🇳! · ¡Hola 🇪🇸! · Hallo 🇩🇪! ·*  \
*안녕하세요 🇰🇷! · こんにちは 🇯🇵! · Привет 🇷🇺! ·* \
*Bonjour 🇫🇷! · Ciao 🇮🇹! · مرحبًا 🇸🇦! · नमस्ते 🇮🇳!*

🎓 Computer Engineering graduate focused on embedded systems, applied AI, and hardware–software integration. 


🛠️ [***Core Technologies***](#%EF%B8%8F-core-technologies) \
💼 [***Featured Projects***](#-featured-projects)

[***Get in touch***](#-what-i-believe)
  
---

## 🛠️ Core Technologies

- ***Languages:*** *C, C++, Python, VHDL, SQL*
- ***Embedded Platforms:***  *ESP32 (ESP-IDF), Cortex-M0 (CubeIDE), FreeRTOS, Zephyr*
- ***AI & ML:*** Torch C++, *PyTorch, CNNs, LLMs, Feature Extraction*
- ***Build & Tooling:*** *PyBind11, CMake, Docker, Conan, GitHub Actions, Make, GCC/MSVC*
- ***Communication & Control:*** *TCP/UDP, MQTT, Serial Protocols (I2C, UART, SPI, 1-Wire, PCIe, CAN), Interrupts (ISR), Thread-Safety*
  
####  ***Fields:***
 - *C / C++ Systems* · *HW–SW Co-Design*  · *Embedded / AI systems*  
 - *DevOps* · *Safety-Critical / Dependable Design*  ·  *Automation*
 - *C++ Bindings for Python*  ·  *Portable Build*  ·  *Vector-Based Retrieval (FAISS)*


---
## 💼 Featured Projects


### 🔹 [PureCPP System](https://github.com/bbzaffari/purecpp_sp)
Cross-language C++/Python retrieval engine for modular vector processing and hybrid ML workflows.  
Features **embedding pipelines, FAISS search, PyBind11 bindings**, and **OpenMP-accelerated** document operations, packed in reproducible **manylinux** wheels and CI-driven builds.

[![Lang](https://img.shields.io/badge/Lang-C%2B%2B20-blue)](https://en.cppreference.com/w/cpp/20)
[![Python Bindings](https://img.shields.io/badge/Python%20Bindings-pybind11-brightgreen)](https://pybind11.readthedocs.io/)
[![Build System](https://img.shields.io/badge/Build%20System-CMake-blue)](https://cmake.org/cmake/help/latest/)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-purple)](https://docs.github.com/actions)
[![Linux Wheels](https://img.shields.io/badge/Linux%20Wheels-manylinux-critical)](https://packaging.python.org/specifications/platform-compatibility-tags/#manylinux)
[![Shared Memory](https://img.shields.io/badge/Shared%20Memory-OpenMP-blueviolet)](https://www.openmp.org/specifications/)
---

### 🔹 [Memory-Mapped I/O (MMIO) - tDES](https://github.com/bbzaffari/MMIO-tripleDes-VHDL-core)

Hardware crypto module with **Triple DES core in VHDL**, exposed via **memory-mapped I/O registers** on a RISC-compatible SoC.
Implements full register binding to the RTL provided by vendors, enabling read/write operations through system calls on a lightweight **RTOS (UCX/OS)**.
Supports multiple cipher modes *(**ECB**, **CBC**, **CTR**)*.
Validated end-to-end through data encryption tests and binary inspection using `hexdump`.

[![Bus](https://img.shields.io/badge/Bus-MMIO-orange)](https://docs.kernel.org/driver-api/device-io.html)
[![HDL](https://img.shields.io/badge/HDL-VHDL-green)](https://www.vhdl.org/)
[![ISA](https://img.shields.io/badge/ISA-RISC--V-283272)](https://docs.riscv.org/)
[![Virtualization](https://img.shields.io/badge/Virtualization-KVM%2FQEMU-lightgrey)](https://www.qemu.org/docs/master/)
[![Container](https://img.shields.io/badge/Container-Docker-2496ED?logo=docker&logoColor=white)](https://docs.docker.com/)
---

### 🔹 [PS/2 VHDL Driver](https://github.com/bbzaffari/Driver-PS2-Mouse)
RTL module for PS/2 mouse decoding, written in **VHDL** and verified with **functional testbenches and synthesis reports**.  
Includes finite state machine design, and full **ASIC-oriented flow**, with post-synthesis timing validation and Cadence toolchain support.

[![HDL](https://img.shields.io/badge/HDL-VHDL-yellow)](https://www.intel.com/content/www/us/en/programmable/customertraining/webex/VHDL/presentation_html5.html)
[![Synthesis](https://img.shields.io/badge/Synthesis-ASIC-critical)](https://www.cadence.com/en_US/home/tools/digital-design-and-signoff/synthesis/genus-synthesis-solution.html)
[![Verification](https://img.shields.io/badge/Verification-Testbench-blue)](https://www.cadence.com/en_US/home/tools/system-design-and-verification/simulation-and-testbench-verification/xcelium-simulator.html)
[![EDA](https://img.shields.io/badge/EDA-Cadence-brightgreen)](https://www.cadence.com/en_US/home/tools.html)
---

### 🔹 [Vigenère Cipher Cryptanalysis Tool](https://github.com/bbzaffari/VigenereDecryptor)

This tool performs **automated cryptanalysis** of messages encrypted with the **Vigenère cipher**, a classical polyalphabetic substitution technique.  
Designed for educational purposes, it showcases the application of **frequency analysis and statistical inference** to deduce the key and decrypt a ciphertext. *Python-based cryptanalysis tool for the classical Vigenère cipher — developed with academic rigor and statistical methods.*

[![Language](https://img.shields.io/badge/Language-Python-blue)](https://docs.python.org/3/)
[![Crypto](https://img.shields.io/badge/Focus-Cryptanalysis-critical)](https://www.cipherchallenge.org/wp-content/uploads/2022/09/A-Book-on-Classical-Cryptography-by-Madness.pdf)
[![Stats](https://img.shields.io/badge/Analysis-χ²%20%7C%20IC%20%7C%20Kasiski-informational)](https://cse.iitkgp.ac.in/~debdeep/courses_iitkgp/Crypto/slides/cryptanalysis.pdf)
[![Report](https://img.shields.io/badge/Format-IEEE--style--Report-lightgrey)](https://www.overleaf.com/latex/templates/ieee-conference-template/grfzhhncsfqn)
---

### 🔹 [Messaging Kernel Module](https://github.com/bbzaffari/Messaging-Kernel-Module)  
**Loadable Kernel Module (LKM)** enabling **message queueing between user-space processes** via a `/dev/mq` ***Character Device*** interface.  
Implements **per-process circular buffers**, a **control block registry**, and **spinlock-based synchronization** for concurrent messaging.  
Includes a C user-space client for interaction and was **cross-compiled with Buildroot** for embedded Linux systems.

[![Linux](https://img.shields.io/badge/Kernel-Linux-black)](https://www.kernel.org/doc/html/latest/)
[![Build](https://img.shields.io/badge/Build-Cross--compiled-blueviolet)](https://buildroot.org/downloads/manual/manual.html)
[![Tool](https://img.shields.io/badge/Tool-Buildroot-informational)](https://buildroot.org/)
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
- #### ***Confidentiality Notice 📄***   **(TCC Final Project Thesis** ***[Cooling-Link](https://github.com/bbzaffari/TCC-Final-Project-Thesis) )***
    > Due to the need to preserve strategic information until the patent process is fully regularized, the thesis project remains private and full access is currently restricted. \
    > Full public disclosure will only be granted once all legal and procedural matters are resolved.\
    > If you are an interviewer and want to see send me an email. I will be more than happy to send.

---
---
