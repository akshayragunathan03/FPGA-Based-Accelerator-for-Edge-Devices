# FPGA-Based-Accelerator-for-Edge-Devices
"FPGA-Based Object Detection Accelerator for Edge Devices" optimizes Tiny-YOLO for real-time detection using FPGA's parallelism. It achieves high speed and low power consumption, ideal for resource-constrained environments like IoT and robotics. The system enhances edge AI efficiency, enabling scalable, energy-efficient, real-time applications.

## Features
- Real-Time Detection: Processes video at 12 FPS with under 80 ms latency.
- Low Power Consumption: Operates at ~1.5W, ideal for energy-constrained environments.
- Edge-Optimized: Fully independent operation without cloud dependency.
- Scalable Architecture: Designed for modularity and adaptability to different edge AI tasks.

## Technologies Used
- Hardware: Xilinx Zynq SoC FPGA (PYNQ Z1 Board)
- Model: Tiny-YOLO (Quantized and Optimized)
- Programming: Python, PYNQ OS
- Libraries: OpenCV, Flask, NumPy

## Installation
1. Clone the Repository- 
   git clone https://github.com/akshayragunathan03/FPGA-Based-Accelerator-for-Edge-Devices.git
   cd FPGA-Based-Accelerator-for-Edge-Devices

2. Set up the FPGA environment:

    Install PYNQ OS on the board.
    Load the required overlays.
   
3.Install dependencies:

    bash
    Copy
    Edit
    pip install -r requirements.txt
    
4.Prepare the Model

  Place the Tiny-YOLO weights and configuration files in the designated folder.

