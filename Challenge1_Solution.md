# IBM Quantum Challenge 1 – Solution Document

## Participant
- Naveen (Solo)

---

## Note
I had many doubts while completing this challenge, and with the help of AI assistance , I was able to organize my solutions and clearly explain my work. All code, observations, and results reflect my own understanding and effort.

---

## Overview
This document explains my work for Challenge 1. I completed three IBM Quantum notebooks, documented my approach, and prepared visualizations to demonstrate my understanding.

The three notebooks are:  
1. **Notebook 1 – Qiskit Fundamentals Lab 2**  
2. **Notebook 2 – DiVincenzo Criteria Lab**  
3. **Notebook 3 – Single-Qubit Dynamics Lab**

---

## Notebook 1 – Qiskit Fundamentals Lab 2

**What I did:**  
- Learned about Pauli operators and basic quantum gates.  
- Applied X, Y, Z, and Hadamard gates to |0⟩.  
- Used `Statevector` to check the qubit state and plotted it on the Bloch sphere.

**Observations:**  
- Gates worked as expected.  
- Bloch sphere plots clearly showed rotations and superpositions.

**Challenges & Solutions:**  
- Colab didn’t support `Aer`, so I used `Statevector`.  
- `execute` didn’t work, so I computed probabilities directly from `Statevector`.

---

## Notebook 2 – DiVincenzo Criteria Lab

**What I did:**  
- Studied the criteria for physical quantum computers: initialization, decoherence, universal gates, and measurement.  
- Simulated circuits to demonstrate each criterion.  

**Observations:**  
- Gates transformed qubit states correctly.  
- Measurement probabilities matched theoretical expectations.

**Challenges & Solutions:**  
- Accessing real backend properties required IBMQ account → focused on simulation.  
- Visualization issues fixed with `Statevector` + matplotlib.

---

## Notebook 3 – Single-Qubit Dynamics Lab

**What I did:**  
- Represented qubits on the Bloch sphere.  
- Applied X, Y, Z rotations and arbitrary rotations.  
- Created superposition with Hadamard gate and measured probabilities.  

**Observations:**  
- Bloch sphere visualizations matched theoretical expectations.  
- Arbitrary rotations helped understand single-qubit dynamics.

**Challenges & Solutions:**  
- Could not import `Aer` → solved using `Statevector`.  
- `execute` errors avoided by using `Statevector` methods.

---

## Conclusion

- Completed all three notebooks successfully.  
- Learned how quantum gates affect qubit states and superpositions.  
- Visualized single-qubit dynamics on the Bloch sphere.  

---

## Video Presentation

**Google Drive Link 
[https://drive.google.com/file/d/1RlYqAylyZ5oAw94bTLXrdx0cc--rN-1e/view?usp=drivesdk]

---

**End of Document**