# PCIEScanner
**PCIEScanner** is a Windows C++ tool that scans PCIe devices, detects DMA capable hardware, flags unusual devices, and identifies newly installed devices that are 30 days.

---

## Features

- Scans all PCIe devices.  
- Detect potential **DMA capable devices** .  
- Flags **unusual devices**.  
- Detect **new devices installed within 30 days**.   
- **CSV export**.  

---

## Usage

open via  **Command Prompt**

```bash
PCIEScanner.exe --all
PCIEScanner.exe --unusual
PCIEScanner.exe --all --export=devices.csv
PCIEScanner.exe --unusual --export=unusual_devices.csv
