## Clément Dumeril

Robotics and controls engineer, MEng in Control of Robotic & Autonomous Systems at UC Berkeley (graduating May 2027). I work on model-based control and physics-informed learning for robots, with a mechanical engineering background in simulation, dynamics and prototyping.

At the Agile Robotics and Perception Lab (Prof. Giuseppe Loianno) I am developing an energy-aware nonlinear MPC for fixed-wing dynamic soaring as my MEng capstone. That code stays private while the work is in progress.

### Robotics and learning

- [ur5e-neural-kinematics](https://github.com/clementdumeril/ur5e-neural-kinematics): neural inverse kinematics for a UR5e, trained through a differentiable forward-kinematics model in PyTorch. 0.19 mm on held-out test targets and 0.53 ms per solve inside a camera-guided Webots pick-and-place loop, benchmarked on the same pose problem against closed-form, damped-least-squares and IKPy solvers. [Preprint](https://github.com/clementdumeril/ur5e-neural-kinematics/blob/main/paper/main.pdf).

### Simulation and verification

- [helmholtz-resonator-solver](https://github.com/clementdumeril/helmholtz-resonator-solver): two independent finite-difference solvers for an open Helmholtz resonator, verified by manufactured solutions and grid convergence, compared with published measurements. [Preprint](https://github.com/clementdumeril/helmholtz-resonator-solver/blob/main/paper/main.pdf).
- [copv-type4-multifidelity](https://github.com/clementdumeril/copv-type4-multifidelity): a CalculiX composite-shell model of a Type IV hydrogen vessel run on 384 designs and an MLP corrector for a fast sizing model in an existing genetic-algorithm optimizer, followed by an audit showing the learned dome peak was not mesh-converged. [Preprint](https://github.com/clementdumeril/copv-type4-multifidelity/blob/main/paper/main.pdf).
- [ducted-fan-aeroacoustics](https://github.com/clementdumeril/ducted-fan-aeroacoustics) and [ventilator-modal-analysis-petgcf](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf): URANS with Ffowcs Williams-Hawkings acoustics in OpenFOAM, and modal and impact analysis in Code_Aster, for a fan studied at Polytechnia, computed on the small Linux cluster I set up. [Acoustics preprint](https://github.com/clementdumeril/ducted-fan-aeroacoustics/blob/main/paper/main.pdf).

### Fall 2026 at Berkeley

Predictive Control Systems (Borrelli), Introduction to Robotics (Horowitz), Drone Digital Twins (Zohdi), Physics-Inspired Machine Learning (Krishnapriyan).

### Elsewhere

[Portfolio](https://clement.dumeril.net) · [CV](https://clement.dumeril.net/assets/docs/Clement_Dumeril_Fall2026.pdf) · [LinkedIn](https://www.linkedin.com/in/cl%C3%A9ment-dumeril-aab768327/)
