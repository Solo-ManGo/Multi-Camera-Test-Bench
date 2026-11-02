# Multi-Camera-Test-Bench
EyeQ6H Centralized Multi-Camera Test Bench Architecture Presentation

An interactive, responsive presentation slide deck engineered for high-level hardware, systems, and embedded software architecture reviews. Focuses on the Mobileye EyeQ6H Central ADAS Processor, 11-camera GMSL3 SerDes ingestion, PAM4 physical layer validation, and Direct Video Injection Hardware-in-the-Loop (HIL) pipelines.

🎯 Key Features & Technical Topics Covered

Executive Overview & Goals: System objectives for ingesting 11 high-resolution uncompressed camera feeds on a centralized hub board.

System Topology & Chipset Selection: Array of three Analog Devices MAX96792A GMSL3 deserializers driving dual 4-lane MIPI CSI-2 interfaces into the Mobileye EyeQ6H NVCSI host.

Direct Video Injection Data Flow: Detailed architecture breakdown (PCIe Host → FPGA protocol bridge → GMSL Serializer → ECU SerDes) and integration blockers (I2C Slave Emulation, Power-over-Coax isolation, Frame Synchronization/FSYNC).

Physical Test Bench Architecture: Dual operational modes (Physical Sensor Pods vs. Digital HIL Simulator) with Mini-FAKRA / HMTD® connectors and automotive battery transient simulation.

GMSL3 Physical Layer Challenges: PAM4 12 Gbps signal integrity, eye-diagram clearance, and multi-stage PoC inductor/ferrite filtering.

Software Stack & EyeQ Kit SDK: Linux Device Tree (DTS) virtual channel routing (VC0–VC3), I2C address translation, and V4L2 kernel media controller binding.

Automated Validation Matrix: Test domains, targets, and pass/fail metrics.

Implementation Timeline: 4-Phase rollout plan from PCB trace math to automated thermal HIL testing.

⌨️ Presentation Controls

Navigate Right / Next Slide: Right Arrow key

Navigate Left / Previous Slide: Left Arrow key

Toggle Technical Speaker Notes: Shift + N
Select the main branch and / (root) folder, then click Save.

⚖️ Legal & Compliance

All used information and concepts are provided in accordance with the Mobileye Terms of Use.
