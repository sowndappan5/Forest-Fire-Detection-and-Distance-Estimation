# Forest Fire Detection & Distance Estimation System

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

````

---

## ⚠️ Missing Files
This repository **does not include**:
1. **Trained fire detection model** (YOLOv8 `.pt` file)  
   - Required for running the fire detection part of the code.
2. **Grid calculation dataset**  
   - Required for accurate perspective mapping and distance estimation.

These files are excluded due to size and licensing constraints.

---

## 📥 How to Use
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/forest-fire-detection.git
   cd forest-fire-detection
````

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Add the missing files**

   * Place your YOLOv8 fire detection model file in the project folder.
   * Place your grid calculation dataset in the `data/` folder (or update the notebook path).

4. **Run the notebook**

   * Open `app.ipynb` in Jupyter Notebook or JupyterLab.
   * Update the camera height and tilt angle parameters as needed.
   * Run all cells to start detection and distance estimation.

---

## 📊 Distance Estimation Method

* Uses **camera calibration** (height + tilt angle).
* Applies **perspective projection** to map pixel positions to ground distance.
* Outputs estimated fire distance in meters.

---

## 🚀 Possible Improvements

* Integrate **thermal imaging** for low-light detection.
* Add **multi-camera triangulation** for higher accuracy.
* Implement **real-time alert systems** (SMS, Email, IoT triggers).

---

## 📜 License

This project is for **research and educational purposes only**. Use at your own risk for deployment in real environments.

---

## 👤 Author

**Sowndappan S**
📧 Email: [2k22it50@kiot.ac.in](mailto:2k22it50@kiot.ac.in)
🔗 [LinkedIn](https://linkedin.com/in/your-link)

```

---

If you want, I can also make a **requirements.txt** file for this repo so people can run `pip install -r requirements.txt` directly and not guess the dependencies.  
Do you want me to prepare that?
```
