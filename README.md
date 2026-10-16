## Clément Dumeril

MEng in Control of Robotic & Autonomous Systems at UC Berkeley (May 2027), after a mechanical engineering background in simulation and dynamics. I work on model-based control and physics-informed learning for robots.

My capstone, at the Agile Robotics and Perception Lab (Prof. Giuseppe Loianno), is an energy-aware nonlinear MPC for fixed-wing dynamic soaring. That code stays private for now.

### Robotics and learning

- [quadrotor-ros2](https://github.com/clementdumeril/quadrotor-ros2): my C++ ROS 2 control stack for a DJI Mavic 2 Pro in Webots. In gusty wind, the nonlinear MPC (acados) roughly halves the tracking error of a geometric controller: 3.1 against 7.3 cm RMSE. Simulation only so far.
- [ur5e-neural-kinematics](https://github.com/clementdumeril/ur5e-neural-kinematics): neural inverse kinematics for a UR5e, trained through differentiable forward kinematics. 0.19 mm on held-out targets. [Preprint](https://github.com/clementdumeril/ur5e-neural-kinematics/blob/main/paper/main.pdf).
- [Djembe](https://github.com/clementdumeril/Djembe): a graph model of Malian jembe micro-timing that predicts stroke timing better than the best reference model on 13 of 15 held-out takes (one seed so far).

### Simulation and verification

- [copv-type4-multifidelity](https://github.com/clementdumeril/copv-type4-multifidelity): CalculiX model of a Type IV hydrogen vessel on 384 designs, with an MLP corrector; an audit with over 220 more runs showed the learned dome peak was not mesh-converged. [Preprint](https://github.com/clementdumeril/copv-type4-multifidelity/blob/main/paper/main.pdf).
- [helmholtz-resonator-solver](https://github.com/clementdumeril/helmholtz-resonator-solver): two verified finite-difference solvers that match published measurements to 0.9–2.2%. [Preprint](https://github.com/clementdumeril/helmholtz-resonator-solver/blob/main/paper/main.pdf).
- [ducted-fan-aeroacoustics](https://github.com/clementdumeril/ducted-fan-aeroacoustics) and [ventilator-modal-analysis-petgcf](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf): OpenFOAM aeroacoustics and Code_Aster modal analysis of a fan, run on a small Linux cluster I set up. [Acoustics preprint](https://github.com/clementdumeril/ducted-fan-aeroacoustics/blob/main/paper/main.pdf) · [Structural preprint](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf/blob/main/paper/main.pdf).

### Fall 2026 at Berkeley

Predictive Control Systems (Borrelli), Introduction to Robotics (Horowitz), Drone Digital Twins (Zohdi), Physics-Inspired Machine Learning (Krishnapriyan).

### Elsewhere

[Portfolio](https://clement.dumeril.net) · [CV](https://clement.dumeril.net/assets/docs/Clement_Dumeril_Fall2026.pdf) · [LinkedIn](https://www.linkedin.com/in/cl%C3%A9ment-dumeril-aab768327/)
