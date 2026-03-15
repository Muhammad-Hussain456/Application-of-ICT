# 💻 Computer Parts / Components

A computer consists of **hardware** (physical components) and **software** (programs that instruct hardware).  

- **Hardware** – Tangible, physical parts you can touch  
- **Software** – Programs and instructions that tell hardware what to do  

---

## 🖥️ Main Hardware Components

### 1️⃣ Input Devices – Send data to the computer

| Device | Function |
|--------|---------|
| ⌨️ Keyboard | Type letters and numbers |
| 🖱️ Mouse | Point and click |
| 📠 Scanner | Convert documents to digital form |
| 🎤 Microphone | Record sound |
| 🎮 Gamepad | Control games |
| 🖊️ Stylus | Draw/write on a touchscreen |
| 🖲️ Trackball | Move cursor using a ball |
| 📷 Camera | Capture images and video |

---

### 2️⃣ Output Devices – Show results from the computer

| Device | Function |
|--------|---------|
| 🖥️ Monitor | Display visuals |
| 🖨️ Printer | Print documents |
| 🔊 Speakers | Play sound |
| 🎧 Headphones | Personal audio output |
| 📽️ Projector | Display visuals on a large screen |
| 💡 LED Display | Show information visually |
| 📢 Public Speaker | Amplify sound for an audience |
| 🏷️ Label Printer | Print labels |

---

### 3️⃣ Processing Devices – The Brain of the Computer

| Device | Function |
|--------|---------|
| 🧠 CPU | Main processing unit |
| 🎮 GPU | Handles graphics and visual tasks |
| ⚡ TPU | AI/ML computations |
| 🔢 Co-processor | Assists the main CPU |
| 🖥️ Microcontroller | Small embedded processor for specific tasks |
| 🪐 FPGA | Customizable hardware processor |
| 🖱️ Neural Processor | AI computations |
| 🔄 DSP | Processes digital signals like audio/images |

---

### 4️⃣ Storage Devices – Save and Retrieve Data

| Device | Function |
|--------|---------|
| 💽 HDD | Magnetic storage |
| 💾 SSD | Fast flash storage |
| 🗄️ USB Drive | Portable storage |
| 💿 CD/DVD | Optical media |
| 🧊 Cloud Storage | Online storage |
| 📝 Memory Card | Expandable storage |
| 🖴 Floppy Disk | Old magnetic medium |
| 🔑 Secure Token | Encrypted storage |

---

### 5️⃣ Networking Devices – Connect Computers & Devices

| Device | Function |
|--------|---------|
| 🌐 Router | Connects multiple networks |
| 📡 Modem | ISP Internet connection |
| 🔌 Switch | Connects devices in a network |
| 🖧 Hub | Shares network among devices |
| 🌍 Access Point | Provides Wi-Fi access |
| 🔄 Network Adapter | Network connectivity on a device |
| 🛰️ Satellite Modem | Internet via satellite |
| 🔗 Bridge | Connects/manages network segments |

---

## ✅ Supporting Hardware

Supporting hardware assists main components by **enabling connectivity, communication, or power**. These do **not perform core computing or storage** themselves.  

1. **Cables** – Wires that carry **power or data** (power cables, data cables, display cables, peripheral cables)  
2. **Connectors** – Cable ends that plug into ports (USB, HDMI, RJ-45, etc.)  
3. **Ports** – Receptacles on devices where connectors plug in; can be **physical** (USB port, HDMI port) or **virtual** (software/network ports like 80, 443)  
4. **Interfaces** – Communication standard; can be **physical** (USB, PCIe, Ethernet) or **virtual** (virtual NICs, OS interfaces)  
5. **Jacks** – Specialized ports, usually audio/video (3.5mm, RCA, headphone jack)  

---

## ✅ Additional Concepts Covered

- **Power & Data Flow** – How CPU ↔ RAM ↔ Storage ↔ GPU communicate  
- **Buses** – Data, address, and control lines inside the motherboard  
- **Role of Motherboard** – Connects all hardware, acts like the central “hub”  

---

## 💡 Memory Tip – Plumbing Analogy

Think of supporting hardware **like plumbing**:

| Hardware | Analogy |
|----------|---------|
| Cable | Wire or pipe |
| Connector | Pipe fitting end |
| Port | Hole in the wall where pipe fits (can be virtual as well) |
| Interface | Plumbing standard (PVC, copper, pressure; can be virtual as well) |
| Jack | Special kind of port (like a faucet for audio) |

This analogy helps **visualize how data and power flow through the system**, and why ports/interfaces can be **physical or virtual**.  

---

## 📊 Data Flow Inside a Computer

```mermaid
flowchart TD
    PSU[Power Supply Unit] --> MB[Motherboard]
    MB --> CPU[CPU (Central Processing Unit)]
    CPU --> RAM[RAM (Working Memory)]
    CPU --> GPU[GPU (Graphics Processing Unit)]
    RAM --> Storage[Storage Devices (HDD/SSD/USB/Cloud)]
    CPU --> Input[Input Devices (Keyboard, Mouse, Scanner)]
    GPU --> Output[Output Devices (Monitor, Printer, Speakers)]
    MB --> Network[Networking Devices (Router, Switch, Modem)]
    CPU -.-> Support[Supporting Hardware: Cables, Connectors, Ports, Interfaces, Jacks]
