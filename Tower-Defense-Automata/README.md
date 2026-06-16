# 🏰 Tower Defense Game - Theory of Automata (TOA) Model

A mathematical system engineering and game design project modeling a tactical Tower Defense Game utilizing **Formal Language Theory** and **Deterministic Finite Automata (DFA)** state machines. The project translates abstract computational states into concrete game loop mechanics and strategy rules.

## 📐 Automata Modeling & Formal Definition
The core application mechanics are explicitly modeled as a state machine using a formal mathematical definition 5-tuple ($Q, \Sigma, \delta, q_0, F$):
* **Set of States ($Q$):** Defines operational stages including game menus, tower placement matrices, wave execution states ($q_0, q_1, q_2, q_5 \dots$), resource accounting adjustments, and end-game boundary conditions.
* **Transition Tables ($\delta$):** Maps exact state adjustments triggered by inputs like enemy tracking metrics, tower configurations (Archer/Cannon/Mage), resource variations, and player health deductions.
* **Algorithmic Pathing:** Simulates structural waves of increasing difficulty where creeps follow strict grid coordinate trajectories, computing intercept fields and damage vectors recursively.

## 🛡️ Cybersecurity & SOC Operations Relevance
* **Stateful Firewalls:** The transition logic engineered here directly mirrors stateful packet filtering. Firewalls evaluate connection flags sequentially against strict transition matrices to distinguish legitimate data streams from spoofed attack sequences.
* **Signature-Based Intrusion Detection (IDS):** Modern IDS platforms utilize finite state automata (NFAs/DFAs) to run high-speed regex processing across packet payloads, scanning raw binary patterns for matches against known exploit fingerprints.

## 🛠️ Technical Focus
* **Computational Models:** Deterministic Finite Automata (DFA) & Transition Matrices
* **Language:** Python
* **Concepts:** Formal Grammars, State Machine Architecture, Resource Allocation Loops, Pathing Intercept Graphs
