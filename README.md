# AMD-AI-Engage

# Agri-Edge: AMD-Accelerated Crop Disease Diagnosis

This project demonstrates a high-performance Edge AI solution for real-time agricultural diagnostics. It is specifically optimized to run on **AMD Kria™ SOM** and **Zynq™ UltraScale+™** hardware.

## 🚀 Key Features
* **Hardware Acceleration:** Utilizes the AMD Deep Learning Processor Unit (DPU).
* **Optimization:** INT8 Quantization via **AMD Vitis AI**, reducing model size by 4x.
* **Low Latency:** Sub-20ms inference for offline field use.
* **Practical Impact:** Enables immediate localized treatment of crop diseases without cloud dependency.

## 🛠 Tech Stack
* **Language:** C++ 
* **Framework:** Vitis AI Runtime (VART)
* **Libraries:** OpenCV, XIR (Xilinx Intermediate Representation)
* **Hardware Target:** AMD Kria KV260 Vision AI Starter Kit

## 📂 Repository Structure
* `/src`: C++ source code for DPU execution.
* `/model`: Compiled `.xmodel` file for the AMD DPU.
* `/tests`: Sample images for verification.

## 📈 Performance Metrics
| Metric | Result |
| :--- | :--- |
| **Platform** | AMD Kria KV260 |
| **Inference Time** | 18ms |
| **Power Draw** | < 5 Watts |
| **Accuracy (INT8)** | 95.8% |

## ⚖️ License
This project is licensed under the MIT License.