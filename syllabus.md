# Syllabus

The seminar covers twelve topics, numbered in teaching order. Each topic is introduced by the instructor through a few key papers or established tools, then explored in a hands-on session and in student presentations. The [schedule](schedule.md) shows how topics map to weeks.

**TBD:** a short reading list for each topic will be added before the semester starts.

### 1. Introduction to quantum compilation

The stack from algorithm to pulse: which transformation happens at each layer, and which hardware constraints (connectivity, gate set, noise) each layer has to respect.

Tools: Qiskit, MQT Bench

Reference paper for student presentation: Marco Maronese, Lorenzo Moro, Lorenzo Rocutto, and Enrico Prati, "Quantum Compiling, [https://arxiv.org/pdf/2112.00187](https://arxiv.org/pdf/2112.00187).

### 2. Circuit synthesis and unitary decomposition

How a target unitary is turned into a sequence of gates from a hardware gate set, and how to check that the result is still equivalent.

Tools: Qiskit, BQSKit, MQT QCEC

Reference paper for student presentation: V. V. Shende, S. S. Bullock, I. L. Markov, "Synthesis of quantum-logic circuits", IEEE Transactions on Computer-Aided Design 25, 1000 (2006), [https://arxiv.org/pdf/quant-ph/0406176](https://arxiv.org/pdf/quant-ph/0406176).

### 3. Qubit mapping and routing

Placing logical qubits on physical ones and inserting SWAP gates so that every two-qubit gate respects the device connectivity.

Tools: Qiskit, MQT QMAP, pytket

Reference paper for student presentation: G. Li, Y. Ding, Y. Xie, "Tackling the qubit mapping problem for NISQ-era quantum devices", ASPLOS 2019, [https://arxiv.org/pdf/1809.02573](https://arxiv.org/pdf/1809.02573).

### 4. Gate scheduling and circuit depth optimisation

Reordering and parallelising gates to shorten the circuit and reduce the time qubits spend exposed to noise.

Tools: Qiskit, pytket

Reference paper for student presentation: G. G. Guerreschi, J. Park, "Two-step approach to scheduling quantum circuits", [https://arxiv.org/pdf/1708.00023](https://arxiv.org/pdf/1708.00023).

### 5. Noise-aware compilation

Using device calibration data to choose layouts and gates that suit the actual hardware, rather than an idealised one.

Tools: Qiskit, Qiskit Aer

Reference paper for student presentation: P. Murali et al., "Noise-adaptive compiler mappings for noisy intermediate-scale quantum computers", ASPLOS 2019, [https://arxiv.org/abs/1901.11054](https://arxiv.org/abs/1901.11054)

### 6. Error mitigation

Noise is one of the major hurdle in scaling quantum computers, so researchers developed intresting tricks to mitigate noise until error correction and fault-tolerance becomes practical. In this module, we dive deeper into the various techniques for this.

Tools: Qiskit, Pennylane

Reference paper for student presentation: Endo, Suguru, et al. "Hybrid quantum-classical algorithms and quantum error mitigation." Journal of the Physical Society of Japan 90.3 (2021): 032001. [https://arxiv.org/abs/2011.01382](https://arxiv.org/abs/2011.01382)

### 7. Machine-learning-assisted compilation

Where learned models can support compilation decisions, such as choosing compilation options for a given circuit and device.

Tools: MQT Predictor

Reference paper for student presentation: Fösel, Thomas, et al. "Quantum circuit optimization with deep reinforcement learning." arXiv preprint arXiv:2103.07585 (2021). [https://arxiv.org/abs/2103.07585](https://arxiv.org/abs/2103.07585)

### 8. Basics of QEC and FTQC

The ideas behind quantum error correction and fault-tolerant quantum computing, and why they change what compilation has to do.

Tools: Stim

Reference paper for student presentation: Chatterjee, Avimita, Koustubh Phalak, and Swaroop Ghosh. "Quantum error correction for dummies." 2023 IEEE International Conference on Quantum Computing and Engineering (QCE). Vol. 1. IEEE, 2023. [https://arxiv.org/abs/2304.08678](https://arxiv.org/abs/2304.08678)

### 9. Logical compilation for Clifford circuits

Compiling Clifford circuits at the logical level, on top of an error-correcting code.

Tools: Stim, Qiskit

Reference paper for student presentation: Chao, Rui, and Ben W. Reichardt. "Fault-tolerant quantum computation with few qubits." npj Quantum Information 4.1 (2018): 42. [https://arxiv.org/abs/1705.05365](https://arxiv.org/abs/1705.05365)

### 10. Introduction to circuit cutting

Splitting a large circuit into smaller pieces that can be run separately and recombined, to fit the limits of current devices.

Tools: Qiskit circuit cutting add-on

Reference paper for student presentation: T. Peng, A. W. Harrow, M. Ozols, X. Wu, "Simulating large quantum circuits on a small quantum computer", Physical Review Letters 125, 150504 (2020), [https://arxiv.org/abs/1904.00102](https://arxiv.org/abs/1904.00102)

### 11. Compilation for distributed quantum computing

Compilation strategies when a computation is spread across several quantum processors.

Tools: Qiskit, pytket

Reference paper for student presentation: D. Ferrari, A. S. Cacciapuoti, M. Amoretti, M. Caleffi, "Compiler design for distributed quantum computing", IEEE Transactions on Quantum Engineering 2 (2021), [https://arxiv.org/abs/2012.09680](https://arxiv.org/abs/2012.09680).