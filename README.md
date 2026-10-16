## Clément Dumeril

I'm doing an MEng in Control of Robotic & Autonomous Systems at UC Berkeley (graduating May 2027), after a mechanical engineering background in simulation, dynamics and prototyping. I work on model-based control and physics-informed learning for robots.

For my MEng capstone, at the Agile Robotics and Perception Lab (Prof. Giuseppe Loianno), I'm developing an energy-aware nonlinear MPC for fixed-wing dynamic soaring. That code stays private while the work is in progress.

### Robotics and learning

- [quadrotor-ros2](https://github.com/clementdumeril/quadrotor-ros2): my own C++ control stack in ROS 2 Jazzy for a DJI Mavic 2 Pro in Webots, with a nonlinear MPC (acados, real-time iteration) benchmarked against a cascaded geometric controller with flatness feedforward. The MPC solves in about 0.5 ms (median) at 100 Hz on a 2016 laptop CPU and roughly halves the tracking error in gusty wind: 3.1 against 7.3 cm RMSE on a figure eight at 5 m/s. Simulation only so far.

- [ur5e-neural-kinematics](https://github.com/clementdumeril/ur5e-neural-kinematics): neural inverse kinematics for a UR5e, trained through a differentiable forward-kinematics model in PyTorch. 0.19 mm on held-out test targets and 0.53 ms per solve inside a camera-guided Webots pick-and-place loop, benchmarked on the same pose problem against closed-form, damped-least-squares and IKPy solvers. [Preprint](https://github.com/clementdumeril/ur5e-neural-kinematics/blob/main/paper/main.pdf).

- [Djembe](https://github.com/clementdumeril/Djembe): a generative model of Malian jembe micro-timing on the IEMP corpus (15 takes, 41,072 strokes), with take-level splits so nothing leaks between train and test. The piece can be recognized from the jembe timing alone (balanced accuracy 0.86 over 4 cycles, 0.78 with tempo regressed out). A graph model of the 12-pulse cycle now predicts stroke timing better than the best reference model on 13 of 15 held-out takes (one seed; three seeds pending). Along the way I found a mislabeled file in the published corpus.

### Simulation and verification

- [copv-type4-multifidelity](https://github.com/clementdumeril/copv-type4-multifidelity): a CalculiX composite-shell model of a Type IV hydrogen vessel run on 384 designs, and an MLP corrector for a fast sizing model in an existing genetic-algorithm optimizer. An audit with over 220 further CalculiX runs then showed that the learned dome peak was not mesh-converged. [Preprint](https://github.com/clementdumeril/copv-type4-multifidelity/blob/main/paper/main.pdf).
- [helmholtz-resonator-solver](https://github.com/clementdumeril/helmholtz-resonator-solver): two independent finite-difference solvers for an open Helmholtz resonator, verified by manufactured solutions and grid convergence. They agree with each other to 0.6% and with published measurements to 0.9–2.2%. [Preprint](https://github.com/clementdumeril/helmholtz-resonator-solver/blob/main/paper/main.pdf).
- [ducted-fan-aeroacoustics](https://github.com/clementdumeril/ducted-fan-aeroacoustics) and [ventilator-modal-analysis-petgcf](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf): URANS with Ffowcs Williams-Hawkings acoustics in OpenFOAM, and modal and impact analysis in Code_Aster, for a fan studied at Polytechnia, computed on the small Linux cluster I set up. [Acoustics preprint](https://github.com/clementdumeril/ducted-fan-aeroacoustics/blob/main/paper/main.pdf) · [Structural preprint](https://github.com/clementdumeril/ventilator-modal-analysis-petgcf/blob/main/paper/main.pdf).

### Fall 2026 at Berkeley

Predictive Control Systems (Borrelli), Introduction to Robotics (Horowitz), Drone Digital Twins (Zohdi), Physics-Inspired Machine Learning (Krishnapriyan).

### Elsewhere

[Portfolio](https://clement.dumeril.net) · [CV](https://clement.dumeril.net/assets/docs/Clement_Dumeril_Fall2026.pdf) · [LinkedIn](https://www.linkedin.com/in/cl%C3%A9ment-dumeril-aab768327/)
