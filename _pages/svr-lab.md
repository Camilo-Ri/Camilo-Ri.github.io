---
title: "Space Vehicles and Robotics (SVR) Lab"
permalink: /svr-lab/
author_profile: true
---

# The SVR lab @ Florida Tech

The **SVR lab** specializes in the design, development and implementation of novel Guidance Navigation and Control (GNC) strategies for robots and space vehicles.

Our research is focused on improving the reliability and robustness of critical GNC algorithms for space missions by applying nonlinear adaptive control, machine learning strategies or a combination of both. These robust algorithms are relevant for several applications in the growing space industry.

Although the theoretical development is fundamental part of SVR lab’s research. We also believe that thorough on-ground testing of these algorithms using state-of-the-art testbeds is necessary. Therefore, we also work on designing and building testing equipment.

---

## Research Focus Areas

The SVR Lab conducts research in the following interconnected areas:

- **Spacecraft Guidance, Navigation, and Control**
  - Attitude and orbit control
  - Relative motion and proximity operations
  - Multi-spacecraft and distributed systems

- **Adaptive and Learning-Based Control**
  - Adaptive control for uncertain and time-varying systems
  - Integration of machine learning with control frameworks
  - Data-driven modeling and estimation

- **Fault Detection, Isolation, and Recovery (FDIR)**
  - Reaction wheel fault detection and health monitoring
  - Safe autonomy under component degradation

- **On-ground Testing and Validation**
  - MIL - SIL - HIL
  - Simulated spacecraft attitude motion
  
---

## Projects

- **Improving Robustness to Actuator Failures/Degradation**
  - This project considers a spacecraft equipped with a redundant reaction wheel array that over time loses performance of one or more of its main attitude control actuators. System identification algorithms, along with control allocation strategies are combined to maintain performance in the presence of degradation or actuator loss.

- **Using Adaptive COntrol and Machine Learning to Estimate Drag-Related Parameters**
  - This project considers a set of propelant-less spacecraft maneuvering with respect to an unknown object in the Low-Earth-Orbit by means of atmospheric drag. The agents use Integral Concurrent Learning for online estimation of atmospheric density and physical parameters of the unknown object. Although estimations are better than a-priori information, residual errors are present due to approximations in the dynamics. Machine learning techniques are explored to improve the estimation of these parameters given independent estimations from each agent.

- **Post-capture Attitude Control**
  - In the context of Space Situational Awareness applications, multiple strategies have been proposed to capture a non-cooperative object in orbit for a subsequent disposal. This project focus on the post-capture scenario where a small module equipped with Reaction Wheels (RW) and a 2 DOF propulsion system, is attached to a larger object. The new rigid body has uncertain physical parameters, making it difficult to maintain attitude due to RW saturation if the thrust vector is not correctly aligned. Adaptive control and/or machine learning techniques are explored to address this problem.
 
- **Three-DoF Spacecraft Attitude Testbed
  - This project will use Florida Tech’s Helmholtz cage and air bearing to design and build a satellite attitude testbed. The testbed will have an onboard Jetson nano computer, four reaction wheels and three magnetorquers. An attitude determination algorithm based on magnetometer and gyro measurements will be implemented, as well as a Lyapunov-based attitude controller. This testbed will serve as the last validation stage for SVR’s GNC algorithms.

---



