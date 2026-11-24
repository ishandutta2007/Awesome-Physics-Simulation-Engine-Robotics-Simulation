# Awesome-Physics-Simulation-Engine-Robotics-Simulation

# Top Physics Simulation Engine & Robotics Simulation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Rigid/Soft-Body Physics Engines, Differentiable Simulators, Embodied AI, GPU-Accelerated RL Environments & Digital Twins*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Physics Simulation Engine & Robotics Simulation**. These tools power high-fidelity multi-body dynamics, soft-body/fluid physics, sim-to-real reinforcement learning, ROS 2 digital twins, autonomous vehicle testing, and real-time collision detection.

**Examples** include MuJoCo, NVIDIA PhysX Cloud, Bullet Physics, Havok Cloud, Chrono, ODE Physics, Webots, CoppeliaSim, DART Sim, Genesis Physics, and `google-deepmind/mujoco` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for GPU-parallelized physics engines, differentiable robotics simulators, ROS 2 Gazebo environments, and C++/Rust/Python dynamics solvers — ideal for robotics engineers, embodied AI researchers, game physics programmers, and digital twin architects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NVIDIA Omniverse Cloud & Isaac Sim Cloud](https://nvidia.com)**  
  Cloud-hosted OpenUSD digital twin and GPU-accelerated PhysX simulation platform for training, testing, and validating physical AI and robotics fleets.

- **[Havok Physics & Cloud Services (Microsoft)](https://havok.com)**  
  Commercial real-time collision detection, rigid-body dynamics, and destruction physics engine powering AAA games and cloud simulation pipelines.

- **[CoppeliaSim Edu/Pro (Coppelia Robotics)](https://coppeliarobotics.com)**  
  Versatile commercial/educational robotics simulation platform supporting multiple physics backends (MuJoCo, Bullet, ODE, Newton), ROS 2, and remote APIs.

- **[Cognite / SimScale Cloud Simulation](https://simscale.com)**  
  Cloud-native engineering simulation platform offering browser-based Finite Element Analysis (FEA), Computational Fluid Dynamics (CFD), and thermal solvers.

- **[Ansys Autonomy & Digital Twin Cloud](https://ansys.com)**  
  Enterprise multi-physics, sensor simulation (LiDAR/Radar/Camera), and hardware-in-the-loop (HIL) cloud validation suite for autonomous systems.

- **[MathWorks Simscape & MATLAB Online](https://mathworks.com)**  
  Cloud-accessible multi-domain physical modeling and multibody robotics simulation environment with automated code generation.

- **[Applied Intuition (Simian / Spectral)](https://appliedintuition.com)**  
  Enterprise cloud simulation and sensor-physics platform built for autonomous vehicle, defense, and industrial robotics validation at scale.

- **[Formant / InOrbit Cloud Digital Twin](https://inorbit.ai)**  
  Cloud robot operations and digital twin observability platform integrating live fleet telemetry with simulated physics playback.


## Open-Source GitHub Projects

- **[google-deepmind/mujoco](https://github.com)**  
  Multi-Joint dynamics with Contact — fast, accurate open-source C/Python physics engine with MJX (JAX GPU/TPU acceleration) widely used in robotics and biomechanics.

- **[Genesis Physics (Genesis-Embodied-AI)](https://github.com)**  
  Next-generation open-source generative and universal physics platform written in pure Python, unifying rigid body, MPM, SPH fluids, FEM soft bodies, and differentiable simulation at ultra-high GPU speeds.

- **[NVIDIA Isaac Lab](https://github.com)**  
  Unified, modular open-source framework for robot learning built on NVIDIA Isaac Sim and GPU-accelerated PhysX for massively parallel reinforcement and imitation learning.

- **[NVIDIA PhysX SDK (Open-Source)](https://github.com)**  
  NVIDIA's flagship open-source real-time rigid-body, soft-body, cloth, and GPU-accelerated particle physics engine.

- **[Bullet Physics & PyBullet](https://github.com)**  
  Classic open-source C++ collision detection and multi-body dynamics library featuring `PyBullet` for robotics manipulation, inverse kinematics, and RL training.

- **[Project Chrono](https://github.com)**  
  High-performance open-source C++ multi-physics simulation engine specializing in wheeled/tracked vehicles, granular terrain (DEM), FEA, and robotics.

- **[Webots (Cyberbotics)](https://github.com)**  
  Complete open-source 3D mobile robot simulator powered by an enhanced ODE physics engine with built-in sensor models, ROS 2 support, and cross-platform export.

- **[Gazebo (Open Robotics — Harmonic / Ionic)](https://github.com)**  
  The standard open-source 3D robotics simulator tightly integrated with ROS 2, offering pluggable physics engines (`DART`, `Bullet`, `TPE`) and realistic sensor rendering.

- **[DART (Dynamic Animation and Robotics Toolkit)](https://github.com)**  
  Open-source C++ physics and kinematics library utilizing generalized coordinates and Featherstone's algorithm for accurate, drift-free articulated robot dynamics.

- **[ODE (Open Dynamics Engine)](https://bitbucket.org)**  
  Veteran, lightweight open-source C/C++ library for simulating articulated rigid-body dynamics and collision detection in robotics and vehicles.

- **[Brax (Google)](https://github.com)**  
  Massively parallel, open-source differentiable physics engine written in JAX enabling millions of physics steps per second on GPUs and TPUs.

- **[Warp (NVIDIA)](https://github.com)**  
  Open-source Python framework for writing high-performance differentiable spatial computing and custom physics/FEM/MPM simulation kernels on GPUs.

- **[Taichi Lang](https://github.com)**  
  Open-source domain-specific language embedded in Python for high-performance parallel physics, MPM snow/sand, fluid, and differentiable robotics simulations.

- **[Drake (MIT / Toyota Research Institute)](https://github.com)**  
  Open-source C++ and Python toolbox for model-based design, contact-rich multi-body dynamics, trajectory optimization, and verification of dynamical systems.

- **[Pinocchio](https://github.com)**  
  Ultra-fast open-source C++/Python rigid-body dynamics library implementing analytical derivatives for legged locomotion, manipulation, and optimal control.

- **[Rapier (Dimforge)](https://github.com)**  
  Fast, cross-platform, deterministic 2D and 3D open-source physics engine written in Rust with first-class WebAssembly, Bevy, and JavaScript bindings.

- **[Jolt Physics](https://github.com)**  
  Modern, multi-core friendly open-source C++ rigid-body physics and collision detection engine engineered for high-throughput simulations and games.

### Additional Strong Open-Source Options

- **[SAPIEN](https://github.com)** and **[ManiSkill](https://github.com)** for open-source GPU-parallelized articulated object manipulation and Embodied AI benchmarks.
- **[SOFA Framework](https://github.com)** for real-time open-source Finite Element Method (FEM) soft-tissue, medical robotics, and deformable object simulation.
- **[Box2D](https://github.com)** for the foundational open-source 2D rigid-body physics engine used across robotics path-planning prototypes and 2D games.
- **[MuJoCo Menagerie](https://github.com_menagerie)** for an open-source collection of high-quality, ready-to-simulate MJCF robot models (humanoids, quadrupeds, arms, hands).
- Many community **URDF/MJCF/USD robot asset converters**, **ROS 2 `ros2_control` hardware-in-the-loop bridges**, and **Sim2Real domain randomization suites**.

**Frameworks for building custom systems**: Combine **MuJoCo (MJX)** or **Genesis Physics**, **Isaac Lab / Gazebo**, **Pinocchio / Drake**, and **MuJoCo Menagerie** with **ROS 2** for scalable, sim-to-real robotics and embodied AI pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Simulation fidelity ("the sim-to-real gap") varies across contact solvers, friction models, and actuator latency; always validate policies and control loops with safety limits, domain randomization, and progressive hardware testing before deploying on physical robots.

---

**Made for robotics engineers, embodied AI researchers, physics programmers, and digital twin builders.**  
Let's make physics simulation and robotics engineering faster, reproducible, and open.
