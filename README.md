<h1 align="center">Vivek Sai</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=720&lines=Robotics+%26+AI+Engineer;Perception%2C+Manipulation+%26+Robot+Learning;Building+Reliable+Robots+Beyond+the+Demo" alt="Typing SVG"/>
</p>

<p align="center">
  <strong>Robotics &amp; AI Engineer · Stuttgart, Germany</strong><br/>
  M.Sc. Computer Science (Autonomous Systems) · University of Stuttgart
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivek-sai-5b363221a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://vivek-portfolio-mocha.vercel.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:viveksaisurya07@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=VivekSai07&label=Profile+Views&color=0e75b6&style=for-the-badge" alt="Profile Views"/>
</p>

<p align="center">
  <a href="#about">About</a> · <a href="#current-work">Current work</a> · <a href="#featured-projects">Projects</a> · <a href="#technical-skills">Skills</a> · <a href="#activity">Activity</a>
</p>

---

<a id="about"></a>

## 🧭 About

I am a Master's student in Computer Science (Autonomous Systems) at the University of Stuttgart, focused on building robotic systems that are perception-driven, reliable, and deployable in real environments. My work sits at the intersection of robot perception, motion planning, and AI, with hands-on experience taking projects from simulation through to hardware execution.

My technical interests include:

- **Robot Perception** — 3D LiDAR odometry, visual SLAM, point-cloud processing
- **Manipulation & Grasping** — grasp pose estimation, motion planning, sim-to-real transfer
- **Robot Learning** — vision-language-action policies, deep reinforcement learning, reproducible evaluation
- **Embodied AI** — systems that connect perception, decision-making, and action

---

<a id="current-work"></a>

## 🔭 Current Work

- **Humanoid robotics, development & validation** — contributing to perception, localization, object detection, and human-facing robot capabilities on mobile robot platforms.
- **Master's thesis (in progress)** — investigating proactive robot assistance for construction-style collaborative work: intent estimation, affordance reasoning, consequence prediction, and deciding when to wait, ask, or help.
- **Vision-language-action policies** — studying robust instruction-following manipulation with controlled data collection and reproducible evaluation.

---

<a id="featured-projects"></a>

## 🚀 Featured Projects

### ⭐ [ContactPilot](https://github.com/VivekSai07/ContactPilot) — Vision-Guided Grasping & Sorting for Franka

A full sim-to-manipulation pipeline for Franka Panda that combines multi-camera RGB-D fusion, promptable object selection, grasp-pose prediction, differential IK execution, and bin placement.

- Built reproducible pick-and-place benchmarks across Contact-GraspNet and GraspGen backends.
- Reached **30/30 successful placements** in a three-object simulated placement evaluation.
- Added natural-language task execution and vision-based scene understanding for object routing.

> Python · MuJoCo · PyTorch · ROS 2 · Contact-GraspNet · GraspGen · SAM 3

---

### ⭐ [Franka VLA Generalization](https://github.com/VivekSai07/franka-vla-generalization) — Instruction-Following Manipulation

A rigorously evaluated research project on VLA policy generalization for Franka manipulation in simulation.

- Designed held-out layouts and instruction pairs to test language grounding instead of shortcut learning.
- Built reproducibility safeguards around data, model, and evaluation artifacts.
- Ongoing experiments examine instruction-driven sorting under layout variation and distractors.

> Python · X-VLA · SmolVLA · MuJoCo · robosuite · Docker

---

### ⭐ [AMR Odometry](https://github.com/VivekSai07/amr_odom) — MAD-ICP-Inspired 3D LiDAR Odometry

An Eigen-only core odometry library with a ROS 2 Humble wrapper, supporting offline and live RViz evaluation. Evaluated on handheld LiDAR and Boston Dynamics SPOT datasets, with Docker support for reproducible deployment.

- Achieved **0.014 m ATE RMSE** on the handheld dataset.

> C++ · Eigen · ROS 2 Humble · Docker · LiDAR · RViz

---

### Quadruped Manipulation — MuJoCo

Simulation and control stack for a quadruped robot performing manipulation tasks in MuJoCo. Explores locomotion stability combined with arm-based interaction tasks.

> Python · MuJoCo · Pinocchio

---

### Autonomous Indoor Delivery Robot

End-to-end autonomous navigation stack for indoor environments, covering mapping, localization, and task-level autonomy.

> Python · ROS · Navigation Stack

---

### Distributed Systems Chat Application

A fault-tolerant, decentralized chat application built from distributed systems fundamentals: message reliability, causal ordering, leader election, and dynamic scalability.

> Python · Distributed Systems

---

### Differential Drive Robot Simulation

A differential drive robot modeled in Fusion 360, exported to URDF, and simulated in Gazebo with full ROS control integration, including teleoperation and sensor integration.

> ROS · Gazebo · URDF · CMake

---

### Pythonic LiDAR Simulation

A LiDAR sensor simulated from scratch in Python, covering ray casting, distance measurement, and 2D map rendering, built to understand the underlying physics before using off-the-shelf libraries.

> Python · Sensor Simulation

---

### Robotic Arm Kinematics — MATLAB 3D Simulation

A MATLAB simulation of a multi-joint robotic arm using Denavit-Hartenberg parameters, covering forward kinematics, workspace visualization, and trajectory planning.

> MATLAB · Robotics · Kinematics

---

<a id="technical-skills"></a>

## 🛠️ Technical Skills

| Domain | Technologies |
|---|---|
| **Languages** | Python, C++, MATLAB, Java |
| **Robotics Frameworks** | ROS, ROS 2, MuJoCo, Gazebo, Pinocchio, Nav2 |
| **Perception & CV** | OpenCV, Open3D, RGB-D, Point Cloud Processing, Visual Odometry |
| **ML / Deep Learning** | PyTorch, TensorFlow, scikit-learn, VLA Policies, Contact-GraspNet |
| **DevOps & Tools** | Git, Docker, Linux, CMake |
| **Hardware** | Franka FR3/Panda, Unitree Go2 & G1, Intel RealSense, Jetson Orin NX |

---

<a id="activity"></a>

## 📊 Activity

<p align="center">
  <a href="https://github.com/VivekSai07/VivekSai07/actions/workflows/snake.yml"><img src="https://github.com/VivekSai07/VivekSai07/actions/workflows/snake.yml/badge.svg" alt="Snake Animation Workflow"/></a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=VivekSai07&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=VivekSai07&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph"/>
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake.svg" />
    <img alt="Contribution Snake Animation" src="https://raw.githubusercontent.com/VivekSai07/VivekSai07/output/github-snake.svg" />
  </picture>
</p>

---

<p align="center">Open to research collaborations, robotics engineering roles, and interesting open-source projects.</p>
