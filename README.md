Quantum Hackathon Problems
Overview
This repository contains three quantum computing hackathon problems designed for CS/IT students. Each problem explores a key concept: superposition, entanglement, and quantum communication. Students should use Python and Qiskit for implementation, visualization, and explanation.

Problem 1 – Quantum Communication Simulator
Goal
Build a small simulation that demonstrates how quantum superposition and entanglement can be used to send and verify information securely between two users (Alice and Bob).

Tasks
Create a pair of entangled qubits shared between Alice and Bob.

Allow Alice to apply operations (X, Z, H) on her qubit.

Bob measures his qubit – show how his result depends on Alice's operation.

Visualize results using Bloch spheres or histograms.
Stretch Goal
Extend to 3 qubits (Alice, Bob, Charlie) or simulate quantum teleportation.

Problem 2 – Quantum Coin Game (Superposition)
Goal
Use quantum superposition to simulate a coin that is both heads and tails until measured.
Tasks
Create a qubit initialized in |0⟩ (Heads).

Apply a Hadamard gate (H) to create a superposition (Heads and Tails).

Measure the qubit multiple times (e.g., 1000 shots) and show the distribution.

Add bias using RY(θ) instead of H to make the coin unfair.

Stretch Goal
Turn it into a 2-player game (Alice vs Bob) and calculate who wins based on probabilities.
Problem 3 – Quantum Correlation Explorer (Entanglement)
Goal
Visualize and analyze entanglement correlations between two qubits when measured in different bases.

Tasks
Create a 2-qubit Bell state (H + CNOT).
Measure both qubits and show 00 or 11 outcomes.

Apply different rotations (H, S, T) before measurement to change the measurement basis.

Measure again and show that correlation persists even with basis changes.

Stretch Goal
Compare multiple Bell states (Φ⁺, Φ⁻, Ψ⁺, Ψ⁻) and calculate correlation coefficients.
Prerequisites
Python 3.8+

Qiskit

Jupyter Notebook (optional, for visualization)

Installation

# Clone the repository
git clone https://github.com/SyedaMaida/Quantum-Computing-Qiskit
cd quantum-hackathon
# Install required packages
pip install qiskit qiskit-aer qiskit-ibmq-provider matplotlib numpy
