## Clément Dumeril

Robotics and controls engineer, MEng in Control of Robotic & Autonomous Systems at UC Berkeley (graduating May 2027). I work on model-based control and physics-informed learning for robots, with a mechanical engineering background in simulation, dynamics and prototyping.

At the Agile Robotics and Perception Lab (Prof. Giuseppe Loianno) I am developing an energy-aware nonlinear MPC for fixed-wing dynamic soaring as my MEng capstone. That code stays private while the work is in progress.

### Robotics and learning

- [ur5e-neural-kinematics](https://github.com/clementdumeril/ur5e-neural-kinematics): neural inverse kinematics for a UR5e, trained through a differentiable forward-kinematics model in PyTorch. 0.185 mm on held-out targets, 0.54 ms per solve, run inside a camera-guided Webots pick-and-place loop and benchmarked against closed-form, damped-least-squares and IKPY solvers.

### Simulation and verification

- [helmholtz-resonator-solver](https://github.com/clementdumeril/helmholtz-resonator-solver): two independent finite-difference solvers for an open Helmholtz resonator, verified by manufactured solutions and grid convergence, within 0.9 to 2.2% of published measurements.
- [copv-type4-multifidelity](https://github.com/clementdumeril/copv-type4-multifidelity): a CalculiX composite-shell model of a Type IV hydrogen vessel run on 384 designs, and a NumPy MLP that corrects a fast sizing model inside a genetic-algorithm optimizer (cross-validated R² 0.862).
- [ducted-fan-aeroacoustics](https://github.com/clementdumeril/ducted-fan-aeroacoustics) and [ventilator-modal-analysis-petgcf](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf): URANS with Ffowcs Williams-Hawkings acoustics in OpenFOAM, and modal and impact analysis in Code_Aster, for a fan studied at Polytechnia. Both were computed on the small Linux cluster I set up.

### Fall 2026 at Berkeley

Predictive Control Systems (Borrelli), Introduction to Robotics (Horowitz), Drone Digital Twins (Zohdi), Physics-Inspired Machine Learning (Krishnapriyan).

### Elsewhere

[Portfolio](https://clement.dumeril.net) · [CV](https://clement.dumeril.net/assets/docs/Clement_Dumeril_Fall2026.pdf) · [LinkedIn](https://www.linkedin.com/in/cl%C3%A9ment-dumeril-aab768327/)
