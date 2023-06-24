<!-- Shields: -->
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg?logo=paypal&style=flat-square)](https://www.paypal.me/CamponogaraViera/100)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-informational)
[![Python](https://img.shields.io/badge/Python-3.11.2-informational)](https://www.python.org/)
[![Qiskit](https://img.shields.io/badge/Qiskit-0.42.1-6133BD)](https://qiskit.org/)
[![Contributions](https://img.shields.io/badge/contributions-welcome-orange?style=flat-square)](https://github.com/QuCAI-Lab/open-quantum-systems/pulls)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/QuCAI-Lab/open-quantum-systems/graphs/commit-activity)
[![License](https://img.shields.io/github/license/QuCAI-Lab/adapt-qka.svg?logo=CreativeCommons&style=flat-square)](https://github.com/QuCAI-Lab/open-quantum-systems/blob/dev/LICENSE.md)

<!-- Logo: -->
<div align="center">
  <a href="https://qucai-lab.github.io/">
    <img src="https://github.com/QuCAI-Lab/qucai-lab.github.io/blob/main/assets/QuCAI-Lab.png" height="500" width="500" alt="Logo">
  </a>
</div>

<!-- Title: -->
<div align="center">
  <h1> Crash Course </h1>
  <h1> Open Quantum Systems </h1>
</div>

<!-- Author: -->
<div align="center">
  <b>Author: Lucas Camponogara Viera</a>
</div>

<!-- Dependencies: -->
# Dependencies
<a href="https://www.python.org/" target="_blank" rel="noopener noreferrer"><img height="27" src="https://www.python.org/static/img/python-logo.png"></a>
<a href="https://qiskit.org/" target="_blank" rel="noopener noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://qiskit.org/documentation/stable/0.19/_static/logo.png">
    <img alt="Shows Qiskit logo for light color mode and dark color mode." src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/51/Qiskit-Logo.svg/1200px-Qiskit-Logo.svg.png" height="27">
  </picture>
</a>
<br>

# Table of Contents

- [Postulates of Quantum Mechanics](notebooks/0_postulates.ipynb).
	- State Space.
	- Evolution.
	- Measurement.
	- Composite State.
- [Evolution in Close Quantum Systems](notebooks/1_evol_in_close_qsystems.ipynb).
  - Wave Mechanics formalism
  - Matrix Mechanics formalism
    - Schrödinger Picture (S-P)
    - Heisenberg Picture (H-P)
  - Density Matrix Formalism
- [Evolution in Open Quantum Systems.](notebooks/2_evol_in_open_qsystems.ipynb)
  - Unitary Representation.
  - Stinespring Representation.
  - Kraus Representation a.k.a Axiomatic Approach.
  - Lindblad Master Equation Approach.
- [Types of noise](notebooks/3_types_of_noise.ipynb)
  - Projection noise.
  - Measurement noise.
  - Coherent noise.
  - Incoherent noise.
- [Quantum Channels with Qiskit](notebooks/4_qchannels_with_qiskit.ipynb)
  - Coherent error channel.
  - Depolarizing error channel.
  - Amplitude damping channel.
  - Phase damping channel.
  - Phase-amplitude damping error channel.
  - Kraus error channel.

# References

\[1] Nielsen MA, Chuang IL. 2010. Quantum Computation and Quantum Information. New York: [Cambridge Univ. Press.](https://doi.org/10.1017/CBO9780511976667) 10th Anniv. Ed. Chapter 8: Quantum noise and quantum operations.

[2] M. M. Wilde, Quantum information theory (Cambridge University Press, 2013).

[3] John Preskill. "Course Information for Physics 219/Computer Science 219 Quantum Computation." [California Institute of Technology.](http://theory.caltech.edu/~preskill/ph229/)

[4] P. Krantz, M. Kjaergaard, F. Yan, T. P. Orlando, S. Gustavsson, W. D. Oliver; A quantum engineer's guide to superconducting qubits. [Applied Physics Reviews](https://doi.org/10.1063/1.5089550) 1 June 2019; 6 (2): 021318. 

[5] Sangil Kwon, Akiyoshi Tomonaga, Gopika Lakshmi Bhai, Simon J. Devitt, Jaw-Shen Tsai; Gate-based superconducting quantum computing. [Journal of Applied Physics](https://doi.org/10.1063/5.0029735) 28 January 2021; 129 (4): 041102. 

[6] [Calibrating qubits using Qiskit Pulse](https://learn.qiskit.org/course/quantum-hardware-pulses/calibrating-qubits-using-qiskit-pulse).

[7] Qiskit documentation.


<!-- License: -->
# License

This work is licensed under a [Apache License 2.0](LICENSE.md) license.

<hr>

Created and maintained by [@camponogaraviera][1].

[1]: https://github.com/camponogaraviera

