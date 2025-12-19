 Quantum Hackathon Problems
This document includes three quantum computing hackathon problems designed for CS/IT
students. Each problem explores a key concept: superposition, entanglement, and quantum
communication. Students should use Python and Qiskit for implementation, visualization, and
explanation.
Problem 1 – Quantum Communication Simulator
Goal: Build a small simulation that demonstrates how quantum superposition and entanglement can
be used to send and verify information securely between two users (Alice and Bob).
Tasks:
1 Create a pair of entangled qubits shared between Alice and Bob.
2 Allow Alice to apply operations (X, Z, H) on her qubit.
3 Bob measures his qubit – show how his result depends on Alice’s operation.
4 Visualize results using Bloch spheres or histograms.
Stretch Goal:
Extend to 3 qubits (Alice, Bob, Charlie) or simulate quantum teleportation.
Problem 2 – Quantum Coin Game (Superposition)
Goal: Use quantum superposition to simulate a coin that is both heads and tails until measured.
Tasks:
1 Create a qubit initialized in |0 (Heads).
2 Apply a Hadamard gate (H) to create a superposition (Heads and Tails).
3 Measure the qubit multiple times (e.g., 1000 shots) and show the distribution.
4 Add bias using RY(θ) instead of H to make the coin unfair.
Stretch Goal:
Turn it into a 2-player game (Alice vs Bob) and calculate who wins based on probabilities.
Problem 3 – Quantum Correlation Explorer (Entanglement)
Goal: Visualize and analyze entanglement correlations between two qubits when measured in
different bases.
Tasks:
1 Create a 2-qubit Bell state (H + CNOT).
2 Measure both qubits and show 00 or 11 outcomes.
3 Apply different rotations (H, S, T) before measurement to change the measurement basis.
4 Measure again and show that correlation persists even with basis changes.
Stretch Goal:
Compare multiple Bell states (Φ , Φ , Ψ ) and calculate correlation coefficients.
Scoring Criteria (All Problems): Correctness 40% • Visualization 30% • Creativity 30%.
Good luck, and have fun exploring the quantum world!
