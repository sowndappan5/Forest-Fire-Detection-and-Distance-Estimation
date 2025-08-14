# Forest Fire Detection & Distance Estimation System

```
This repository contains the implementation code for a camera-based forest fire detection and distance estimation system.  
It is shared for viewing and reference purposes only — the model and dataset are not included.
```

This project is an AI-powered **Forest Fire Detection and Distance Estimation System** that detects fire in real-time camera feeds and estimates its distance from the camera **without additional hardware**.

The system uses:
- **YOLOv8** for fire detection.
- **Perspective Grid Mapping** for distance estimation using only camera parameters.

---

## 🔥 Features
- **Real-time fire detection** using a deep learning model.
- **Distance estimation** based on camera height and tilt angle.
- Works with **standard CCTV, drone, or surveillance cameras**.
- Designed for **low-cost deployment** without LiDAR or radar.

---

## ✨ Uniqueness

- Wide range distance estimation not using any traditional harware.

---

## 🛠️ Tech Stack
- **Python 3**
- **YOLOv8** (Ultralytics)
- **OpenCV** (image processing & perspective mapping)
- **NumPy** (matrix & math operations)
- **Jupyter Notebook** (`app.ipynb`)

---

## 📂 Repository Structure
```

.
├── app.ipynb              # Main notebook with fire detection & distance estimation logic
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies

```

---
## ⚠️ Important Notes
- **This repository does NOT contain:**
  - Trained YOLOv8 fire detection model (`.pt` file)
  - Grid calculation dataset
- Without these files, the notebook cannot be executed — it is intended **only for reading and reference**.

---

## 🖼️ System Workflow
1. **Camera Calibration** – Input camera height and tilt angle.
2. **Fire Detection** – YOLOv8 model detects flames in the video feed.
3. **Distance Estimation** – Perspective mapping calculates approximate distance.

---

## 📜 License
This project is shared for **educational and research viewing only**.

---

## 👤 Author
**Sowndappan S**
Email: santoshsowndappan@gmail.com

**Mythili S**

---
