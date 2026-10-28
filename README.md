<h1 align="center">Vivek Sai</h1>

<p align="center">
  <strong>Robotics & AI Engineer · Stuttgart, Germany</strong><br/>
  M.Sc. Computer Science (Autonomous Systems) · University of Stuttgart
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivek-sai-5b363221a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://vivek-portfolio-mocha.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:viveksaisurya07@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <a href="#current-focus">Current focus</a> · <a href="#selected-work">Selected work</a> · <a href="#toolkit">Toolkit</a>
</p>

## Current focus

I build perception-driven robotic systems that hold up beyond a demo: from sensing and localization through manipulation, evaluation, and deployment.

- **Humanoid robotics, development & validation** — working with perception, localization, object detection, and human-facing robot capabilities on mobile robot platforms.
- **Master's thesis (in progress)** — investigating proactive robot assistance for construction-style collaborative work: estimating intent, reasoning about affordances, predicting consequences, and deciding when a robot should wait, ask, or help.
- **Vision-language-action policies** — studying reliable instruction-following manipulation, with controlled data collection and reproducible evaluation.

## Selected work

### [ContactPilot](https://github.com/VivekSai07/ContactPilot) — vision-guided grasping and sorting

A sim-to-manipulation pipeline for Franka Panda that combines multi-camera RGB-D fusion, promptable object selection, grasp-pose prediction, differential IK, and bin placement.

- Built reproducible pick-and-place benchmarks across Contact-GraspNet and GraspGen backends.
- Reached **30/30 successful placements** in a three-object simulated placement evaluation.
- Added natural-language task execution and vision-based scene understanding for object routing.

Python · MuJoCo · PyTorch · ROS 2 · Contact-GraspNet · GraspGen · SAM 3

### [Franka VLA Generalization](https://github.com/VivekSai07/franka-vla-generalization) — instruction-following manipulation

A rigorously evaluated research project on VLA policy generalization for Franka manipulation in simulation.

- Designed held-out layouts and instruction pairs to test language grounding instead of shortcut learning.
- Built reproducibility safeguards around data, model, and evaluation artifacts.
- Current work examines instruction-driven sorting under layout variation and distractors.

Python · X-VLA · SmolVLA · MuJoCo · robosuite · Docker

### [AMR Odometry](https://github.com/VivekSai07/amr_odom) — 3D LiDAR odometry for ROS 2

A MAD-ICP-inspired odometry stack with an Eigen-only C++ core and ROS 2 Humble integration, including offline evaluation, RViz visualization, and Docker-based deployment.

- Evaluated on handheld LiDAR and Boston Dynamics SPOT datasets.
- Achieved **0.014 m ATE RMSE** on the handheld dataset.

C++ · Eigen · ROS 2 Humble · Docker · LiDAR · RViz

## Toolkit

| Area | Tools & technologies |
|---|---|
| Robotics | ROS 2, MuJoCo, Gazebo, Pinocchio, Nav2 |
| Perception | RGB-D, point clouds, visual odometry, 3D reconstruction, object detection |
| Learning | PyTorch, VLA policies, deep reinforcement learning, vision-language models |
| Systems | Python, C++, Docker, Linux, Git, CMake |
| Hardware | Franka FR3/Panda, Unitree Go2 & G1, Intel RealSense, Jetson Orin NX |

## Beyond the repositories

I have published work in deep reinforcement learning and machine learning, and I am interested in research and engineering roles in embodied AI, robot learning, perception, and manipulation.

<p align="center"><i>Open to collaborations and conversations around reliable, deployable robot intelligence.</i></p>
