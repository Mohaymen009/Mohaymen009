# 🔬 Anti-Cheat Researcher

### Hardware Security Research

I study how modern anti-cheat systems — **Riot Vanguard, Easy Anti-Cheat, BattlEye, FACEIT** — detect, fingerprint, and classify hardware, and I publish what I learn for the security research community.

All research is conducted **ethically**: on my own hardware and test systems, with explicit permission, and published responsibly. The goal is understanding detection methodology — how endpoints are enumerated, probed, and trusted — not abusing it.

---

### 🔍 Research Focus

- **Anti-cheat internals** — PCIe device enumeration, config-space & BAR probing, hardware fingerprinting, detection-vector analysis
- **DMA hardware research** — custom FPGA firmware on Xilinx Artix-7 (100T/75T), PCIe endpoint emulation, FT601/USB3 data acquisition
- **Driver reverse engineering** — deep IDA Pro analysis of Windows kernel drivers: NDIS miniports, PCI/e behavior, anti-cheat kernel modules
- **Windows internals** — PnP enumeration, kernel-mode driver init flows, hardware identity & device-instance lifecycle

### 🛠️ Toolchain

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FPGA-8A2BE2)
![Vivado](https://img.shields.io/badge/Vivado-2023.2-blue)
![C](https://img.shields.io/badge/C-embedded-grey)
![Python](https://img.shields.io/badge/Python-tooling-yellow)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-reversing-red)
![PCIe](https://img.shields.io/badge/PCIe-Gen1--Gen2-00B4D8)

`pcileech-fpga` · `WinDbg` · `mmiotrace` · `lspci/setpci` · x86-64 asm

### 📌 Current Work

- PCIe endpoint identity & behavioral emulation research on Artix-7 DMA hardware
- Driver handshake protocol reconstruction from live MMIO traces
- Detection-surface audits of public anti-cheat builds

---

📧 Reach me via GitHub issues or discussions.
