# 👋👋👋 Hey there, I'm Diyari

🔬 Research & Engineering Intern at **IBISC Laboratory**, Université Évry Paris-Saclay
🎓 M2 in *Smart Aerospace and Autonomous Systems* at **Université Paris-Saclay**, double degree MSc in *Automatic Control and Robotics* at **Poznań University of Technology**
🎓 B.Sc. in **Mechanical & Mechatronics Engineering**, **Salahaddin University Erbil** (2nd in department)
📍 Évry-Courcouronnes, Greater Paris, France
📅 Available from **September 2026**

---

### 📄 Research

- **VIDAR: Visual-Inertial Dense Alignment and Reconstruction via a Geometric Foundation Model**
  *First author.* Preprint [arXiv:2607.17171](https://arxiv.org/abs/2607.17171), under review at IEEE ICARCV 2026.
  Fuses IMU and camera data (SVO + Ceres VIO) with Depth Anything 3 for metric dense monocular mapping. Inertial constraints cut mean trajectory RMSE from **0.898 m to 0.125 m** across 11 EuRoC MAV sequences; dense reconstruction reached **0.676** mean F@0.10 without ground-truth poses.

- **Can Geometric Foundation Models and Vision SLAM Serve as a Viable Alternative to LiDAR for Indoor Robot Localization?**
  *Co-author.* **IEEE ICARM 2026**, accepted, to appear in IEEE Xplore.
  Unified Gazebo/ROS benchmark of 10 SLAM systems across 6 indoor environments, 15,547 frames and 1.04 km of trajectory. Contributed the SVO monocular baseline and the vision versus LiDAR comparison.

- **Identity-Gated Gesture Control and Deterministic Mode Arbitration for Indoor Human-Drone Interaction**
  *First author.* Submitted July 2026, ARO Journal (Scopus / WoS ESCI).

- **GCS-SLAM: Globally Consistent Static Mapping from Dynamic Scenes Without Auxiliary Inputs**
  *Co-author.* Manuscript under review.

🧑‍⚖️ **Reviewer**, IEEE ICARCV 2026 (visual-inertial odometry, SLAM, foundation models)
🏅 **Best Volunteer Award**, IEEE ICARM 2026

---

### 🔭 About me

💻 Robotics and perception engineer working on **sensor fusion, visual-inertial odometry, SLAM and dense 3D reconstruction**
🤖 Comfortable across the stack: estimation and control theory, embedded firmware, and field debugging
⚙️ Projects span **UAVs**, **quadrupeds**, **holonomic and self-balancing robots**, and vision-based control
🧩 Working in `.cpp`, `.py`, `.ino`, `.m`, `.slx`, `.bash` with **ROS/ROS2**, **CUDA**, **OpenCV** and **PyTorch**
🌍 Interested in **drone autonomy**, **robotic perception** and **frugal navigation** for constrained platforms

---

### 📌 Featured

**[gesture-controlled-tello-drone](https://github.com/Diyari-Fariq-M-salih/gesture-controlled-tello-drone)**
Identity-gated gesture control on a DJI Tello EDU. MediaPipe 21-point hand landmarks with an RBF-SVM classifier (**99.71%** accuracy, macro F1 0.9971 over 7 gestures) and ArcFace-style ONNX face embeddings restricting control to the enrolled operator (**0.32% EER** over 13,410 images). Deterministic mode arbitration under a safety > authorization > control priority order, with hybrid perception **under 30 ms/frame**.

---

### 🧪 Other projects

- 🕷️ **Hexapod with on-device LLM** (EVOROBS): trajectory and control for a six-legged platform with an on-device Gemma 3 1B model.
- 🤖 **Quadruped Spider-Drone Hybrid**: four-legged platform carrying a detachable UAV with a camera-based vision module (CNN/OpenCV); balance and gait simulated in PyBullet.
- ⚖️ **Two-wheel self-balancing robot**: inverted-pendulum stabilisation from MPU-6050 accelerometer and gyroscope fusion driving a PID loop onto DC motors.
- 🔩 **Holonomic 4WD UGV**: chassis fabrication, HW-130 motor-driver integration, control firmware in Arduino C++, stable wireless teleoperation beyond 30 m.
- 🚗 **AI for Robotics**: OpenCV + YOLOv5 / MobileNet pipeline for real-time object detection and lane following at 30 FPS.
- 🛰️ **Fixed-wing UAV development**: co-developed a five-servo UAV with aerodynamic modelling and control in MATLAB and Python.
- ⚙️ **Path planning (A\*)**: Python/ROS implementation for collision-free path generation and obstacle avoidance.
- 🔧 **Analog input multiplexing (74HC4051)**: 8:1 analog multiplexer for multi-sensor input on Arduino, with scanning and filtering logic.
- 🧩 **3D printed robotic frames**: structural parts for UAV and quadruped integration in SolidWorks, printed on a custom-firmware Ender-3.

---

### ⚙️ Technical Skills

**Programming:** Python, C++, MATLAB, Bash, Arduino
**Perception & 3D:** Camera calibration, feature matching, multi-view geometry, monocular depth estimation, dense 3D reconstruction, visual odometry, SLAM
**Estimation & Fusion:** IMU and multi-sensor fusion, state estimation, nonlinear optimisation (Ceres), pose-graph optimisation, Sim(3)/Umeyama alignment, particle filters, ATE evaluation
**Control:** PID and cascaded loops, state-space modelling, trajectory generation, state machines and mode arbitration
**AI & ML:** PyTorch, scikit-learn, MediaPipe, geometric foundation models, ONNX Runtime, YOLOv5, latency and memory profiling
**Embedded:** Raspberry Pi, ESP32, Arduino, microcontrollers, I²C/SPI/UART, PCB design, PLC (Siemens TIA Portal)
**Simulation & Tools:** ROS 1/2, Gazebo, MATLAB/Simulink, PyBullet, CUDA, Git, CMake, Linux, Jupyter
**Mechanical Design:** SolidWorks, AutoCAD, additive manufacturing (PLA, PETG)
**Languages:** English (IELTS 8.0, C1; EF SET C2), French (A2, learning), German (A2), Arabic (native), Kurdish (native)

---

### 🛠️ Tools I Use
[![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=flat&logo=visualstudiocode&logoColor=white)]()
[![ROS](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)]()
[![MATLAB/Simulink](https://img.shields.io/badge/MATLAB%20%2F%20Simulink-0076A8?style=flat&logo=Mathworks&logoColor=white)]()
[![SolidWorks](https://img.shields.io/badge/SolidWorks-DA291C?style=flat&logo=dassaultsystemes&logoColor=white)]()

---

![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8)
![ROS](https://img.shields.io/badge/ROS-22314E?logo=ros)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

### 🌐 Connect with me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Diyari%20Fariq-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/diyari-fariq)
[![Gmail](https://img.shields.io/badge/Email-diyari.m.salih%40gmail.com-red?style=flat&logo=gmail)](mailto:diyari.m.salih@gmail.com)
[![arXiv](https://img.shields.io/badge/arXiv-2607.17171-B31B1B?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2607.17171)
[![Portfolio](https://img.shields.io/badge/Portfolio-diyari--fariq--m--salih.github.io-2ea44f?style=flat&logo=github&logoColor=white)](https://diyari-fariq-m-salih.github.io/)

---

> "Precision is the soul of engineering."
