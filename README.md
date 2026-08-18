<h1 align="center">Vivek Sai</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=600&lines=Robotics+%26+AI+Engineer;Grasp+Pose+Estimation+%2B+Motion+Planning;Sim-to-Real+Manipulation+Pipelines" alt="Typing SVG"/>
</p>

<p align="center">
  <strong>Robotics &amp; AI Engineer · Stuttgart, Germany</strong><br/>
  M.Sc. Computer Science (Autonomous Systems) · University of Stuttgart
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivek-sai-5b363221a/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://vivek-portfolio-mocha.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://drive.google.com/file/d/100ASiH-YpZPtIgrZWnRVemSBunrSxf93/view?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=VivekSai07&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="Profile Views"/>
</p>

<p align="center">
  <a href="#about">About</a> ·
  <a href="#featured-projects">Projects</a> ·
  <a href="#technical-skills">Skills</a> ·
  <a href="#activity">Activity</a>
</p>

---

<a id="about"></a>

## 🧭 About

I am a Master's student in Computer Science (Autonomous Systems) at the University of Stuttgart, focused on building robotic systems that are perception-driven, reliable, and deployable in real environments. My work sits at the intersection of robot perception, motion planning, and AI — with hands-on experience taking projects from simulation through to hardware execution.

- 🔭 Currently building **GAUGE** — a gated, uncertainty-aware grasping engine
- 🌱 Currently deepening my work on sim-to-real transfer for FR3 manipulation

Over the past year I have been working extensively with the **Franka Research 3 (FR3)** collaborative robot, developing a vision-guided manipulation pipeline that integrates multi-camera point-cloud fusion, Contact-GraspNet pose estimation, MuJoCo simulation, and differential IK execution. I have iterated this pipeline using a structured benchmark harness, improving grasp success rates from 38% to 90%+.

My technical interests include:

- **Robot Perception** — 3D LiDAR odometry, visual SLAM, point-cloud processing
- **Manipulation & Grasping** — grasp pose estimation, motion planning, sim-to-real transfer
- **Locomotion** — quadruped control, legged robot simulation (MuJoCo, ROS 2)
- **AI/ML for Robotics** — vision-language models, multimodal retrieval, deep learning for perception

I aim to contribute to serious robotics engineering efforts, whether in research or industry.

---

<a id="featured-projects"></a>

## 🚀 Featured Projects

### ContactPilot — Grasp-and-Place Pipeline for Franka FR3
A production-quality pick-and-place pipeline for the Franka Panda robot that combines:
- **Contact-GraspNet** for 6-DoF grasp pose estimation from point clouds
- **Multi-camera point-cloud fusion** for robust scene representation
- **MuJoCo simulation** for policy validation before hardware deployment
- **Differential IK execution** for smooth, collision-aware motion
- A **benchmark harness** used to iteratively tune the pipeline from 38% to 90%+ grasp success

> `Python · MuJoCo · Contact-GraspNet · ROS 2 · PyTorch`

---

### AMR Odometry — MAD-ICP-Inspired 3D LiDAR Odometry (ROS 2)
An Eigen-only core odometry library with a ROS 2 Humble wrapper, supporting both offline and live RViz evaluation. Validated on a **Boston Dynamics SPOT** robot and handheld LiDAR hardware. Includes Docker support for reproducible deployment.

> `C++ · Eigen · ROS 2 Humble · Docker · LiDAR`

---

### Quadruped Manipulation — MuJoCo
Simulation and control stack for a quadruped robot performing manipulation tasks in MuJoCo. Explores locomotion stability combined with arm-based interaction tasks.

> `Python · MuJoCo · Pinocchio`

---

### Autonomous Indoor Delivery Robot
End-to-end autonomous navigation stack for indoor environments, covering mapping, localization, and task-level autonomy.

> `Python · ROS · Navigation Stack`

---

### Distributed Systems Chat Application
A fault-tolerant, decentralized chat application built from distributed systems fundamentals — message reliability, causal ordering, leader election, and dynamic scalability.

> `Python · Distributed Systems`

---

### Differential Drive Robot Simulation
A differential drive robot modeled in Fusion 360, exported to URDF, and simulated in Gazebo with full ROS control integration — including teleoperation and sensor integration.

> `ROS · Gazebo · URDF · CMake`

---

### Pythonic LiDAR Simulation
A LiDAR sensor simulated from scratch in Python — covering ray casting, distance measurement, and 2D map rendering — built to understand the underlying physics before using off-the-shelf libraries.

> `Python · Sensor Simulation`

---

### Robotic Arm Kinematics — MATLAB 3D Simulation
A MATLAB simulation of a multi-joint robotic arm using Denavit-Hartenberg (DH) parameters, covering forward kinematics, workspace visualization, and trajectory planning.

> `MATLAB · Robotics · Kinematics`

---

<a id="technical-skills"></a>

## 🛠️ Technical Skills

| Domain | Technologies |
|---|---|
| **Languages** | Python, C++, MATLAB, Java |
| **Robotics Frameworks** | ROS (Noetic), ROS 2 (Humble), MuJoCo, Gazebo, Pinocchio |
| **Perception & CV** | OpenCV, Open3D, MediaPipe, Point Cloud Processing |
| **ML / Deep Learning** | PyTorch, TensorFlow, scikit-learn, Contact-GraspNet |
| **Data & Analysis** | Pandas, NumPy, Seaborn, Matplotlib |
| **DevOps & Tools** | Git, Docker, Linux, CMake |
| **Databases** | PostgreSQL, MongoDB, MySQL |
| **Web / Backend** | Flask, HTML, JavaScript |
| **Hardware** | Franka FR3, Boston Dynamics SPOT, Arduino |

---

<a id="activity"></a>

## 📊 Activity

<p align="center">
  <a href="https://github.com/VivekSai07/VivekSai07/actions/workflows/snake.yml">
    <img src="https://github.com/VivekSai07/VivekSai07/actions/workflows/snake.yml/badge.svg" alt="Snake Animation Workflow"/>
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=VivekSai07&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VivekSai07&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph"/>
</p>

---

## Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake.svg" />
    <img alt="Contribution Snake Animation" src="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake.svg" />
  </picture>
</p>

---

<p align="center">
  Open to research collaborations, full-time robotics engineering roles, and interesting open-source projects.
</p>
