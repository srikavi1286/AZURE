# Systems Infrastructure, Cloud Storage & UI/UX Design Portfolio

A comprehensive overview of cloud deployments, hardware testing environments, and design specifications documented across various systems and platforms.

---

## 🛠 Tech Stack & Tools

* **Cloud Services:** Microsoft Azure (Container Instances, Storage Browser, Blob Storage)
* **Operating Systems:** Windows Server Infrastructure, Windows 11
* **Hardware & EDA:** Raspberry Pi, Fritzing Hardware Simulator, Dell Workstations
* **Design & Branding:** Vora Design Studio System

---

## ☁️ Cloud Infrastructure & Storage Architecture

### 1. Azure Container Instances (ACI)
Deployment setup showing lightweight container initialization hosted on Microsoft Azure.
* **Public Endpoint:** `20.75.212.60` (or `200.214.10`)
* **Environment:** Welcome page instance confirming container readiness and active service running.

![Azure Container Instances](assets/azure-container-instances.jpg)

### 2. Azure Storage Browser (`srikavistorage`)
Data and asset management hosted on Azure Storage Services.
* **Storage Account Name:** `srikavistorage`
* **Container Asset:** `spider profile.avif` (Block blob, Hot access tier, Server Encrypted)
* **Access Control:** Shared Access Signature (SAS) and direct URL blob exposure.

| Asset File | Size | Access Tier | Type | Encryption |
| :--- | :--- | :--- | :--- | :--- |
| `spider profile.avif` | 201.05 KiB | Hot (Inferred) | Block blob | Server Encrypted (`true`) |

![Azure Storage Browser](assets/azure-storage-browser.jpg)
![Spider Profile Graphic Asset](assets/spider-profile-asset.jpg)

---

## 🎨 Design System & Branding Overview

### Vora Studio
Portfolio and design direction showcase for modern web interfaces.
* **Design Philosophy:** *"Good design is never decoration. It is the clearest possible expression of what something is."*
* **Contact Information:**
  * **Email:** `hello@vora.studio`
  * **Phone:** `+41 44 000 0000`
  * **Locations:** Zürich, Switzerland & Remote Worldwide

![Vora Studio Interface](assets/vora-studio.png)

---

## 🖥 Hardware & Electronics Prototyping

### 1. Windows Server Environment
Local and cloud host workstation setups running Windows Server operating system routines.
* **Host System:** Dell Workstation Display Setup
* **Interface:** Multilingual server welcome screen (`Welcome` / `Tervetuloa`).

![Windows Server Setup](assets/windows-server-dell.jpg)

### 2. Raspberry Pi & Fritzing Simulator
Electronic Design Automation (EDA) and embedded IoT prototyping session.
* **Hardware:** Raspberry Pi 3/4 Board with breadboard connection and LED actuator circuit.
* **Software:** Fritzing IoT Simulator with Node.js Azure IoT Hub integration script (`raspberrypi-azure-iot-web-simulator`).

![Fritzing Simulator](assets/fritching-raspberry-pi.jpg)

---

## 📁 Suggested Repository Directory Structure

To keep your images organized in GitHub, store your screenshots inside an `assets/` folder in your repository:

```text
.
├── assets/
│   ├── azure-container-instances.jpg
│   ├── azure-storage-browser.jpg
│   ├── spider-profile-asset.jpg
│   ├── vora-studio.png
│   ├── windows-server-dell.jpg
│   └── fritching-raspberry-pi.jpg
└── README.md
