# UNIXR
A Real-time Depth Aided Adaptive Stereo Generation Framework

# RGBD to VR

## Introduction

This application is a **Virtual Reality (VR) demo** that renders a live video from a color and depth camera in a 3D virtual environment.

It uses a combination of:

- **OpenCV** – computer vision and machine learning library  
- **StereoKit** – mixed reality library for cross-platform VR/AR development  

This application demonstrates how **computer vision and VR can be combined to create immersive multimedia experiences**.

---

# Tools Required

## 1. Orbbec Femto Mega Camera

Depth + RGB camera with real-time streaming over Ethernet or USB.

Link:  
https://shop.orbbec3d.com/Femto-Mega

---

## 2. Meta Quest VR Headset

Tested devices:

- Quest 2  
- Quest Pro  

Link:  
https://www.meta.com/

---

## 3. Windows PC (Recommended Requirements)

Minimum system:

| Component | Requirement |
|---|---|
| CPU | Intel i5-4590 / AMD Ryzen 5 1500X or greater |
| Memory | 8 GB RAM or more |
| OS | Windows 11 64-bit |
| USB | 1× USB-A or USB-C port (USB-C 3.1 recommended) |

---

### Supported GPUs for Oculus Link

**NVIDIA**

- GTX 1650 Super  
- GTX 1660  
- GTX 1660 Ti  
- RTX 20 / 30 / 40 series

**AMD**

- Radeon 400 / 500 / 5000 series  
- Vega series

---

# Installation Guide

Once your Windows PC meets the requirements, install the following software.

### 1. Visual C++ Redistributable (x64)

https://aka.ms/vs/17/release/vc_redist.x64.exe

---

### 2. Orbbec Camera Drivers for Windows

https://dl.orbbec3d.com/dist/drivers/win32/astra-win32-driver-4.3.0.20.zip

---

### 3. Oculus Desktop Application

https://www.oculus.com/download_app/?id=1582076955407037

---

### 4. RGBD2VR Application

Download and unzip:

https://github.com/OrbbecDeveloper/RGBD2VR/releases/download/v0.1.1/RGBD2VR.zip

After extracting, the folder will contain:

- the application executable
- required libraries

---

# Usage Guide

1. Install all required software and hardware.
2. Connect the **Femto Mega camera** to the PC using the **USB-C to USB-C cable** included in the box.
3. Open the **Oculus Desktop App** and sign in with a Meta account.
4. Navigate to **Settings** in the Oculus app.
5. Click the **General** tab.
6. Enable **Unknown Sources**.
7. Turn on the VR headset.
8. Set up the headset with a Meta account (first-time setup).
9. Connect the headset to the PC.

---

### Headset Prompts

After connecting the headset, you may see two prompts.

**1. File access**

Allow connected devices to access files.

You can allow this.

**2. Enable Quest Link**

Enable Quest Link.

This **must be enabled** for the application to work.

---

### If Quest Link Was Not Enabled

You can manually enable it from **Oculus settings**.

Once enabled:

- Oculus Desktop App will launch automatically
- The headset should appear under **Devices**

---

### Running the Application

1. Enter **Oculus Link mode** in the headset.
2. On your PC, run:
