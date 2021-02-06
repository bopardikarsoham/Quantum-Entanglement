# Quantum-Entanglement
In this repository, I have programmed The Quantum Teleportation Algorithm with the help of Qiskit.

-->Quantum Entanglement : The quantum correlation between two objects that cannot be desrcibed using classical mechanics.

-->Why do we use this algorithm ? It has awesome applications like Quantum Teleportation, Quantum Cryptography, Superdense Coding and Quantum speedups. This property of a quantum computer makes it better than a classical computer.

-->How will we use it ? In order to implement this algorithm, we will be creating the following circuit below.

![entangledcircuit](https://user-images.githubusercontent.com/77266161/107123986-d584de00-68c6-11eb-8e68-ef4ff2e07705.jpg)



-->Aim : Entangling qubits(q0 and q1) to form a Bell state : ![bellstate](https://user-images.githubusercontent.com/77266161/107127322-5cdc4c80-68db-11eb-8e9d-b572b1545049.png)



-->Bell State : This state has 50% probability of being measured in the state  |00⟩ , and 50% chance of being measured in the state  |11⟩ . Most interestingly, it has a 0% chance of being measured in the states  |01⟩  or  |10⟩ . 

-->How will I run the circuit ? There are many ways to run the algorithm but in this particular case I have used the QASM Simulator to run my circuit and have shown a histogram to convey the results.

-->Note :- You will not get a perfect 50% probability of |00> and |11> due to QASM simulator running in our classical computer. But, it will always be near 50%.

![EntangleHistogram](https://user-images.githubusercontent.com/77266161/107127528-ac6f4800-68dc-11eb-820f-bdd6b8b3f1ff.jpg)
