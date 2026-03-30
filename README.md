# 🛒 Retail Analytics & Footfall Tracking

<p align="center">
  <img src="assets/demo.gif" alt="Footfall Tracking Demo" width="600">
</p>

## 📌 Overview
Physical retail spaces often lack the accessible, data-driven insights common in e-commerce. This project bridges that gap by utilizing Computer Vision to create a lightweight, automated footfall counter. 

By processing standard security camera footage, the system tracks individuals, assigns unique IDs, and counts them as they cross a virtual threshold. This transforms raw video into actionable data for store operations.

## 💼 Business Impact & Use Cases
This tool is designed with clear managerial and financial utility in mind:
* **Operations & Management:** Identifies peak hours to optimize staff scheduling and reduce overhead.
* **Marketing ROI:** Measures changes in store traffic during specific promotional campaigns or window display updates.
* **Cost-Effective Finance:** Provides high-value, enterprise-level analytics using open-source models and standard CCTV footage, eliminating the need for expensive proprietary hardware.

## ⚙️ Technical Stack
* **Core Model:** YOLOv8s (Ultralytics) for high-speed, real-time object detection.
* **Tracking Algorithm:** BoT-SORT / ByteTrack for maintaining persistent object IDs across video frames.
* **Logic & Processing:** Python and OpenCV for drawing virtual boundaries, calculating vector crossings, and rendering video outputs.
* **Environment:** Developed and optimized using Google Colab (T4 GPU).

## 🚀 Key Features
* **Directional Counting:** Accurately distinguishes between people entering (Walking UP) and exiting (Walking DOWN) a designated zone.
* **Persistent Tracking:** Prevents double-counting by remembering individuals even if they are briefly obscured.
* **Accessible Hardware:** Designed to run efficiently without requiring massive local computational power.

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/arukima12/Retail-Analysis-and-footfall-tracking.git](https://github.com/arukima12/Retail-Analysis-and-footfall-tracking.git)
   cd Retail-Analysis-and-footfall-tracking
