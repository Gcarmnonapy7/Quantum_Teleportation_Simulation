📌 Project Plan: Quantum Teleportation Simulation
1. Objective

Simulate quantum teleportation — transmitting the state of one qubit to another without physically sending the qubit, using entanglement and classical communication.
2. Required Tools

    Python 3.10+

    Qiskit (pip install qiskit)

    Jupyter Notebook (recommended for visualizations)

    Optional: matplotlib for plotting Bloch spheres.

3. Theoretical Steps

    Alice has a qubit in an unknown state |ψ⟩.

    Alice and Bob share an entangled pair.

    Alice:

        Performs quantum gates & measurement.

        Sends the result (two classical bits) to Bob.

    Bob:

        Applies corrective gates (X, Z) based on Alice’s bits.

        Now Bob’s qubit is exactly |ψ⟩.

4. Implementation Plan

We’ll split the code into these blocks:

    Initialize Qiskit and basic imports.

    Create a random qubit state |ψ⟩.

    Set up the entangled pair between Alice and Bob.

    Perform Alice’s operations (CNOT + H + measurements).

    Apply Bob’s correction gates based on classical bits.

    Verify the teleportation (compare final states).

    Visualize the process with Bloch spheres.

5. Possible Enhancements

    Add a step-by-step diagram of the circuit.

    Animate the state transfer on a Bloch sphere.

    Compare with a "no teleportation" scenario for educational purposes.
