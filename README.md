## Hi, I'm Justin

Final-year mechatronics engineering student (ENSIL-ENSCI, exchange year at ISAE-Supméca, Paris).
I work on **embodied AI**: giving robots the perception and control they need to act on their own in the real world.

**Looking for a 6-month end-of-studies internship from March 2027** in robotics, perception or control. Open to relocation worldwide.

---

### Featured work

**Risk-aware navigation for a ground robot** · Politecnico di Torino (DIMEAS), May – July 2026

A 2D LiDAR cannot tell wet ground, mud or thick carpet from dry floor. I built a two-layer risk map (YOLO26 semantic layer + depth-based geometric layer) published live over ROS 2, and a GPU MPPI controller that trades speed against risk.

- 5,120 trajectories evaluated per control cycle, at 14 Hz
- Real risk exposure cut by 44% on a forced crossing and by 100% on an avoidable zone, for only 2–9% extra distance and time
- A cost-arbitrage model, validated on measurements, predicts when the robot switches from crossing to detouring
- Demonstrated on a physical TurtleBot 4

`ROS 2 Jazzy` `Gazebo Harmonic` `C++ / CUDA` `Python` `PyTorch` `MPPI-Generic`
→ [Project page](https://justinamenngblogni.github.io/assets/projects/mppi.html) · [Report (PDF)](https://justinamenngblogni.github.io/assets/docs/Report_RIsk_Aware_MPPI.pdf)

**Autonomous car, built from scratch** · EEIA summer school, Benin

In 2021 I built a self-driving car from a kit. The year after, I rebuilt it entirely: CAD, 3D printing, electronics and code, nothing bought ready-made. It learns to drive by imitation (I drive, it watches, it reproduces), first from three distance sensors, then from a camera.

`Python` `TensorFlow` `OpenCV` `Raspberry Pi 4` `ESP32` `TinyML`
→ [Project page](https://justinamenngblogni.github.io/assets/projects/autonomous-vehicle.html)

**FlyRenov: hose reel for a rooftop-cleaning drone** · Industry project, ENSIL-ENSCI × FlyRenov

With a classmate, I redesigned the machine that winds the drone's 60-metre hose: one person can now move it, two motors replace four, and a single ESP32 board replaces an entire CAN network.

`3DEXPERIENCE` `ESP32` `VESC / FOC` `C / C++` `DFMA`
→ [Project page](https://justinamenngblogni.github.io/assets/projects/flyrenov.html)

**ROS 2 onboarding** · [ROS-initiating](https://github.com/Justinamenngblogni/ROS-initiating)

C++ and Python packages written while learning ROS 2 Jazzy: publishers and subscribers, services, parameters, custom interfaces.

---

### Tech stack

- **Robotics:** ROS 2 · Gazebo · Isaac Sim · MPPI · SLAM · path planning · Kalman filter
- **AI & vision:** PyTorch · TensorFlow · OpenCV · YOLO · SegFormer · reinforcement learning
- **Code & embedded:** Python · C / C++ · Linux · ESP32 · STM32 · Raspberry Pi · CAN · SPI · I²C · UART
- **Design & simulation:** MATLAB / Simulink · Simcenter Amesim · SolidWorks · 3DEXPERIENCE · Fusion 360 · KiCad

---

### Get in touch

[Portfolio](https://justinamenngblogni.github.io) · [LinkedIn](https://www.linkedin.com/in/justin-ngblogni) · [CV (PDF)](https://justinamenngblogni.github.io/assets/docs/Cv%20Justin%20en.pdf) · justin.ngblogni@etu.unilim.fr
