# Syllabus

The seminar covers twelve topics, numbered in teaching order. Each topic is introduced by the instructor through a few key papers or established tools, then explored in a hands-on session and in student presentations. The [schedule](schedule.md) shows how topics map to weeks.

**TBD:** a short reading list for each topic will be added before the semester starts.

### 1. Introduction to quantum compilation

The stack from algorithm to pulse: which transformation happens at each layer, and which hardware constraints (connectivity, gate set, noise) each layer has to respect.

Tools: Qiskit, MQT Bench

### 2. Circuit synthesis and unitary decomposition

How a target unitary is turned into a sequence of gates from a hardware gate set, and how to check that the result is still equivalent.

Tools: Qiskit, BQSKit, MQT QCEC

### 3. Qubit mapping and routing

Placing logical qubits on physical ones and inserting SWAP gates so that every two-qubit gate respects the device connectivity.

Tools: Qiskit, MQT QMAP, pytket

### 4. Gate scheduling and circuit depth optimisation

Reordering and parallelising gates to shorten the circuit and reduce the time qubits spend exposed to noise.

Tools: Qiskit, pytket

### 5. Noise-aware compilation

Using device calibration data to choose layouts and gates that suit the actual hardware, rather than an idealised one.

Tools: Qiskit, Qiskit Aer

### 6. Error mitigation

Noise is one of the major hurdle in scaling quantum computers, so researchers developed intresting tricks to mitigate noise until error correction and fault-tolerance becomes practical. In this module, we dive deeper into the various techniques for this.

Tools: Qiskit, Pennylane

### 7. Machine-learning-assisted compilation

Where learned models can support compilation decisions, such as choosing compilation options for a given circuit and device.

Tools: MQT Predictor

### 8. Basics of QEC and FTQC

The ideas behind quantum error correction and fault-tolerant quantum computing, and why they change what compilation has to do.

Tools: Stim

### 9. Logical compilation for Clifford circuits

Compiling Clifford circuits at the logical level, on top of an error-correcting code.

Tools: Stim, Qiskit

### 10. Introduction to circuit cutting

Splitting a large circuit into smaller pieces that can be run separately and recombined, to fit the limits of current devices.

Tools: Qiskit circuit cutting add-on

### 11. Compilation for distributed quantum computing

Compilation strategies when a computation is spread across several quantum processors.

Tools: Qiskit, pytket