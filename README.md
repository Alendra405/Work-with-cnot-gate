### Bell State Generation using Qiskit 🔔

This project demonstrates one of the most famous quantum phenomena: **quantum entanglement**.

Using only two fundamental gates:
- **Hadamard (H)** → creates superposition  
- **CNOT** → creates entanglement between qubits

We prepare the maximally entangled Bell state:
(|00⟩ + |11⟩)/√2

Key properties:
- After measurement, the two qubits always yield the **same result** (both 0 or both 1)
- Yet before measurement, they exist in superposition of both possibilities simultaneously
- This correlation holds instantly, even if the qubits are separated by large distances (Einstein called it "spooky action at a distance")

Results (1024 shots):  
≈ 50% '00' and ≈ 50% '11' → '01' and '10' never appear!

A perfect example of quantum entanglement in action.
