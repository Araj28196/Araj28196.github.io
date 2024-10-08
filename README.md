# Project Sentinel: AI-Driven Security Camera System

## Overview
Developed a custom security camera system for a small distributor shop, leveraging an SBC and a TPU for advanced computer vision.

## System Components
- **SBC**: Youyeetoo X1
- **TPU**: Google Coral
- **Software**: Frigate for real-time object detection
- **Networking**: Twingate for secure remote access

## Implementation Details
The SBC runs the Frigate application, which uses the TPU for efficient object detection. We're currently training and refining detection models, focusing on accuracy with real-time data from the camera.

I started by setting up the Youyeetoo SBC and connecting it to the Coral AI Accelerator in PCIE slot provided. After configuring the hardware, I integrated the Frigate application to leverage its capabilities for real-time object detection. The Phi-3 model was chosen for its efficiency and accuracy in detecting objects locally.

![Frigate Dashboard](assets/images/frigate-dashboard.png)
