# Hi, I'm Apurv Patel 👋

## Robotics ML Engineer · Robot Learning · Simulation · Dexterous Manipulation

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Robot%20Learning-2f80ed?style=for-the-badge" alt="Focus: Robot Learning"/>
  <img src="https://img.shields.io/badge/Simulation-Isaac%20Lab%20%7C%20Isaac%20Sim-76b900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Simulation: Isaac Lab and Isaac Sim"/>
  <img src="https://img.shields.io/badge/Robotics-ROS2%20%7C%20MoveIt-22314e?style=for-the-badge&logo=ros&logoColor=white" alt="Robotics: ROS2 and MoveIt"/>
  <img src="https://img.shields.io/badge/ML-PyTorch-ee4c2c?style=for-the-badge&logo=pytorch&logoColor=white" alt="Machine Learning: PyTorch"/>
  <img src="https://img.shields.io/badge/Location-Stuttgart%2C%20Germany-111827?style=for-the-badge" alt="Location: Stuttgart, Germany"/>
  <img src="https://img.shields.io/badge/Open%20To-Robotics%20ML%20Roles-16a34a?style=for-the-badge" alt="Open to Robotics ML roles"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/apurv-patel-891475167">
    <img src="https://img.shields.io/badge/LinkedIn-Apurv%20Patel-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:engr.apurv@gmail.com">
    <img src="https://img.shields.io/badge/Email-engr.apurv%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

I am a Robotics ML Engineer based in Stuttgart, Germany, focused on **robot learning, dexterous manipulation, physics simulation, and sim-to-real transfer**.

My work sits at the intersection of **Deep Reinforcement Learning, NVIDIA Isaac Lab / Isaac Sim, ROS2, PyTorch, MoveIt, Newton Physics, MuJoCo, computer vision, CAD-to-simulation workflows, and industrial robotics**. I am especially interested in building robotic systems that not only move, but reason about contact, adapt to uncertainty, and transfer reliably from simulation to real hardware.

Currently, I am looking for full-time opportunities in **Robotics ML, Robot Learning, Robotics Software, Simulation Engineering, Autonomous Systems, and Humanoid Robotics** across Germany and Europe.

---

## What I Work On

At **Fraunhofer IPA**, my master’s thesis focused on:

> **Digital Twin-Driven Deep Reinforcement Learning for Dexterous Pick-and-Place in Smart Manufacturing**

The challenge was to make dexterous robotic manipulation learnable for high-mix, low-volume manufacturing, where robots must handle diverse objects without costly reconfiguration.

I built a high-fidelity **NVIDIA Isaac Lab** digital twin of a **UR5e robot with an underactuated Inspire Hand** and compared two approaches:

- **End-to-End DRL:** one PPO policy controls the full manipulation task
- **Hybrid RL + Inverse Kinematics:** IK handles deterministic transport, while RL focuses on contact-rich grasping and precision placement

The hybrid approach achieved **100% success at 5 mm placement tolerance within 10–13 hours of training**, while the pure end-to-end baseline reached only partial success after 44+ hours.

One novel contribution was **GraspAtlas**, a grasp planner that computes object-specific optimal grasping points for dexterous grasping and provides structured grasp targets before policy execution.

Key idea:

> **Learning works better when combined with structure, physical priors, and well-designed control interfaces.**

---

## Thesis Demo

### GraspAtlas Planner

<div align="center">
  <img src="assets/Cube_grasp_planner.gif" alt="GraspAtlas cube grasp planning demo" width="45%"/>
  <img src="assets/Cylinder_grasp_planner.gif" alt="GraspAtlas cylinder grasp planning demo" width="45%"/>
  <p><em>GraspAtlas computes optimal grasping points for dexterous grasping before policy execution</em></p>
</div>

### Policy Execution

<div align="center">
  <img src="assets/cube_hybrid.gif" alt="Cube Pick-and-Place Demo" width="45%"/>
  <img src="assets/cylinder_hybrid.gif" alt="Cylinder Pick-and-Place Demo" width="45%"/>
  <p><em>Dexterous pick-and-place in NVIDIA Isaac Lab: cube and cylinder test objects</em></p>
</div>

---

## Featured Projects

| Project | What it demonstrates | Tech Stack |
|---|---|---|
| **DRL Dexterous Manipulation Thesis** | GraspAtlas grasp planning, hybrid RL + IK, dexterous grasping, precision placement, sim-to-real transfer | Isaac Lab, PyTorch, RSL-RL, PPO, UR5e, Inspire Hand |
| **Physics-Driven Grasp Validation** | Grasp candidate validation, contact modelling, force-closure reasoning, physics simulation debugging | Newton Physics, MuJoCo, Python, USD assets |
| **ROS2 Dual-Arm Teleoperation** | Real-time dual-arm teleoperation with hand tracking and safety-aware robot control | ROS2 Humble, MoveIt Servo, OpenCV, MediaPipe, RViz |
| **SynthData Factory** | Synthetic data generation pipeline for robotic perception and object detection | Isaac Sim, Replicator API, YOLOv8, Python |
| **3D Bounding Box Prediction** | RGB-D perception, point-cloud processing, and 3D object localization | PyTorch, Open3D, NumPy, RGB-D |
| **ZMP Humanoid Control** | Balance control and walking-pattern exploration for humanoid robotics | MuJoCo, Python, IK, ZMP |
| **Configurable ROS/Gazebo Data Generator** | Robotic safety analysis, fault injection, time-series data generation | ROS, Gazebo, MoveIt, PyQt5 |

---

## Technical Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599c?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/ROS2-22314e?style=flat-square&logo=ros&logoColor=white" alt="ROS2"/>
  <img src="https://img.shields.io/badge/NVIDIA%20Isaac-76b900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA Isaac"/>
  <img src="https://img.shields.io/badge/MuJoCo-111827?style=flat-square" alt="MuJoCo"/>
  <img src="https://img.shields.io/badge/OpenCV-5c3ee8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Linux-fcc624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
</p>

**Robot Learning & AI**<br>
Deep Reinforcement Learning · PPO · RSL-RL · PyTorch · reward design · curriculum learning · sim-to-real transfer · domain randomization

**Robotics & Simulation**<br>
NVIDIA Isaac Lab · Isaac Sim · Newton Physics · MuJoCo · ROS/ROS2 · Gazebo · MoveIt · CoppeliaSim · RViz

**Physics, Contact & Digital Twins**<br>
Contact modelling · collision debugging · force-closure analysis · robot asset validation · URDF/USD workflows · CAD-to-simulation preparation

**Perception & Geometry**<br>
OpenCV · RGB-D perception · point clouds · object detection · 6-DOF pose estimation · grasp synthesis · 3D geometry processing

**Software & Tools**<br>
Python · C/C++ · MATLAB/Simulink · Git · Docker · Linux · PyQt5

**CAD, Mechatronics & Hardware**<br>
SolidWorks · Altium Designer · LTspice · tactile sensing · force-torque feedback · gripper control · motor/VFD commissioning · CAN/CANoe · oscilloscope-based debugging

---

## Research & Publications

- **A Time-series Data Generation Tool for Risk Assessment of Robotic Applications**<br>
  ESREL–SRA-E 2025, Singapore

- **Operational Amplifier Based Low Power DC-AC Converter for Domestic Applications**<br>
  ICOEI 2020

---

## Education & Experience

**MSc Electrical Engineering – Smart Systems**<br>
University of Stuttgart, Germany<br>
Focus: robotics, smart systems, automation, simulation, control, and machine learning

**Research Assistant – Fraunhofer IPA**<br>
Robotics simulation, robot-object interaction, adaptive gripper design, Isaac Lab environments, dexterous manipulation, and physics-based grasp validation

**Commissioning & Maintenance Engineer – JK Cement Ltd**<br>
Industrial electrical systems, motors, VFDs, protection relays, and hardware troubleshooting

---

## How I Work

I enjoy turning complex robotics problems into working prototypes. My approach is solution-oriented and iterative: break the problem into possible directions, test ideas quickly, debug deeply, and improve the system until it behaves reliably.

I am especially motivated by problems at the interface of **simulation, control, perception, mechanical design, and hardware**, where real progress comes from understanding both what the model assumes and what the robot actually does.

---

## Open To

I am currently open to roles in:

- Robotics ML Engineering
- Robot Learning
- Robotics Software Engineering
- Robotics Simulation Engineering
- Humanoid Robotics
- Autonomous Systems
- Robot Manipulation and Grasping
- Sim-to-Real and Digital Twin Development

Location: Stuttgart, Germany<br>
Open to relocation within Germany / Europe

---

## Contact

- LinkedIn: [linkedin.com/in/apurv-patel-891475167](https://www.linkedin.com/in/apurv-patel-891475167)
- Email: [engr.apurv@gmail.com](mailto:engr.apurv@gmail.com)
- GitHub: You are already here 🙂
