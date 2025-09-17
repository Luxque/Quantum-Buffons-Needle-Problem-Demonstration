# Quantum Buffons Needle Problem Demonstration

## Repository Description

This repository contains a technical demonstration of quantum randomness using IBM Qiskit.
It simulates Buffon's Needle Problem to estimate the value of $\pi$ and illustrates the conversion of quantum-generated bit strings into uniformly distributed floating-point numbers.
The demonstration includes both classical and qubit simulation.
The demonstration file is available [here](./buffon.ipynb).


## Abstract

Quantum computers promise numerous advantages, including quantum parallelism, quantum simulation, and quantum cryptography.
Since the theory of local hidden variables has been disproven, it is established that quantum systems are capable of generating truly random outputs.
By preparing qubits in superposition states, one can obtain uniformly distributed random outputs.
This notebook presents a demonstration of quantum randomness through Buffon's needle problem, a probabilistic method for estimating the value of $\pi$.
In this problem, needles of fixed length are randomly dropped onto a plane with evenly spaced parallel lines, and the ratio between the number of intersections and the total number of throws converges to $\pi$.
The random positions and orientations of the needles are generated using a quantum computer, effectively simulating the experiment.
The purpose of this work is not to accelerate the computation of $\pi$, but rather to illustrate the quality of randomness obtainable from quantum processes and to highlight their potential in probabilistic simulations.
This demonstration connects a mathematical conclusion to modern quantum technology, offering both pedagogical value and an example of the interplay between probability and quantum computation.


## References

* Bernhardt, C. *Quantum Computing for Everyone*. MIT Press, 2019.
* “Buffon’s Needle Problem,” *MathWorld — A Wolfram Web Resource*. Available at: https://mathworld.wolfram.com/BuffonsNeedleProblem.html
* “Introduction of Floating Point Representation,” *GeeksforGeeks*. Available at: https://www.geeksforgeeks.org/digital-logic/introduction-of-floating-point-representation/#
* IEEE Standard for Binary Floating-Point Arithmetic (IEEE 754-1985). Available at: https://www.ime.unicamp.br/~biloti/download/ieee_754-1985.pdf


## Contribution

You are more than welcome to contribute by helping fix any mistakes.
Please feel free to open an issue or submit a pull request to this repository.


## License

MIT License.
