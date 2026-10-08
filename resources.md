# Resources

Software used in the hands-on sessions, and general background reading. Per-topic reading lists are in the [syllabus](syllabus.md) and will be added before the semester starts.

## Compilers and toolkits

- [Qiskit](https://quantum.cloud.ibm.com/docs) ([source](https://github.com/Qiskit/qiskit)): IBM's open-source quantum SDK, including its transpiler.
- [Pennylane](https://docs.pennylane.ai/en/stable/): Xanadu's open-source quantum SDK.
- [pytket and tket](https://docs.quantinuum.com/tket/) ([source](https://github.com/quantinuum/tket)): Quantinuum's optimising compiler and its Python interface. The [user guide](https://docs.quantinuum.com/tket/user-guide/) is a good place to start.
- [Munich Quantum Toolkit (MQT)](https://mqt.readthedocs.io) ([source](https://github.com/munich-quantum-toolkit)): design automation tools from the Technical University of Munich, including circuit mapping (QMAP), equivalence checking (QCEC), error-correcting codes (QECC), benchmarks (Bench, also available as a [web interface](https://www.cda.cit.tum.de/mqtbench/)), and compilation-option prediction (Predictor).
- [BQSKit](https://bqskit.readthedocs.io/) ([source](https://github.com/BQSKit/BQSKit)): the Berkeley Quantum Synthesis Toolkit, a compiler framework built around circuit synthesis.
- [Qiskit addon: circuit cutting](https://qiskit.github.io/qiskit-addon-cutting/): tools for cutting circuits into smaller pieces and reconstructing the result.

## Background reading

These are general references, not a required reading list.

- M. A. Nielsen and I. L. Chuang, *Quantum Computation and Quantum Information*, Cambridge University Press.
- J. Preskill, "Quantum Computing in the NISQ era and beyond", *Quantum* 2, 79 (2018).
- Noson S. Yanofsky and Mirco A. Mannucci, *Quantum computing for Computer Scientisits*, Cambridge University Press.
- Oswaldo Zapata, "A Short Introduction to Quantum Computing for Physicists", [https://arxiv.org/pdf/2306.09388](https://arxiv.org/pdf/2306.09388).
- Marco Maronese, Lorenzo Moro, Lorenzo Rocutto, and Enrico
Prati, "Quantum Compiling", [https://arxiv.org/pdf/2112.00187](https://arxiv.org/pdf/2112.00187).
- D. Gottesman, "Stabilizer Codes and Quantum Error Correction", PhD thesis, Caltech (1997), [arXiv:quant-ph/9705052](https://arxiv.org/abs/quant-ph/9705052).
- S. Aaronson and D. Gottesman, "Improved simulation of stabilizer circuits", *Physical Review A* 70, 052328 (2004), [arXiv:quant-ph/0406196](https://arxiv.org/abs/quant-ph/0406196).
- G. Li, Y. Ding, and Y. Xie, "Tackling the qubit mapping problem for NISQ-era quantum devices", ASPLOS 2019, [arXiv:1809.02573](https://arxiv.org/abs/1809.02573).
- T. Peng, A. W. Harrow, M. Ozols, and X. Wu, "Simulating large quantum circuits on a small quantum computer", *Physical Review Letters* 125, 150504 (2020), [arXiv:1904.00102](https://arxiv.org/abs/1904.00102).
- "The MQT Handbook: A Summary of Design Automation Tools and Software for Quantum Computing", [arXiv:2405.17543](https://arxiv.org/abs/2405.17543).