# EE2120: Distributed Smart Temperature Monitoring Node
## Group  | Department of Electrical & Electronic Engineering, UoP

Welcome to our core project repository for the EE2120 Mini-Project.

### 📂 Repository Structure & Ownership
* **/hardware-schematics**: Circuit designs for the LM35 + MCP602 Op-Amp, DS18B20, and power systems. 
    * *Primary Contributor:* Sensor Engineer
* **/firmware**: ESP32 C++/Arduino code utilizing non-blocking execution (`millis()`).
    * *Primary Contributor:* Embedded Engineer
* **/scada-config**: Node-RED flows, database configurations, and dashboard export files.
    * *Primary Contributor:* SCADA Engineer & Communication Engineer
* **/analytics**: Python/MATLAB scripts modeling sensor fusion weights and IDW algorithms.
    * *Primary Contributor:* Data Analytics Engineer

### 🚀 Branching Rules
1. Never push directly to `main`.
2. Create a feature branch for your work (e.g., `feature/lm35-amplifier`).
3. Open a Pull Request (PR) for the Project Leader to review before merging.
