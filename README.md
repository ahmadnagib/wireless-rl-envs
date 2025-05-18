# Reinforcement Learning Environments for Wireless Networks

This repository collects open-source reinforcement learning environments implemented in Python (typically Gym/Gymnasium-compatible) and focused on cellular network use cases. These environments are suitable for tasks such as 5G resource management, network slicing, traffic steering, and O-RAN control.

## Environments

### 1. ns3-gym
- **GitHub:** [tkn-tub/ns3-gym](https://github.com/tkn-tub/ns3-gym)
- **Use Case:** General networking (e.g., spectrum management, congestion control)
- **Paper:** ["ns-3 meets OpenAI Gym: The Playground for Machine Learning in Networking Research"](https://dl.acm.org/doi/10.1145/3345768.3355927), MSWiM 2019
- **Description:** Connects OpenAI Gym API with the ns-3 simulator. Offers flexible, scalable environments for RL in networking.
- **Reputation:** ⭐ 587 | Forks: 205 | Last update: 2023

### 2. MERLIN
- **GitHub:** [SAIC-MONTREAL/MERLIN](https://github.com/SAIC-MONTREAL/MERLIN)
- **Use Case:** Cellular control tasks like mobility load balancing
- **Paper:** No formal paper
- **Description:** Montreal Environment for Reinforcement Learning and Intelligent Networks. Python-based RL environments for cellular tasks, with plug-in agent architecture.
- **Reputation:** ⭐ 3 | Forks: 1 | Last update: 2024

### 3. RAN Slicing Gym Environment (UPCT)
- **GitHub:** [jjalcaraz-upct/network-slicing](https://github.com/jjalcaraz-upct/network-slicing)
- **Use Case:** 5G RAN slicing (resource allocation)
- **Paper:** ["Model-Based Reinforcement Learning with Kernels for Resource Allocation in RAN Slices"](https://ieeexplore.ieee.org/document/9806078), IEEE TWC 2022
- **Description:** Custom Gym environment for dynamic RB allocation across RAN slices. Supports model-based and model-free RL.
- **Reputation:** ⭐ 50 | Forks: 14 | Last update: Sep 2023

### 4. 5G Network Slicing Environment (Robustness Evaluation)
- **GitHub:** [aliahan/network-slicing-with-RL](https://github.com/aliahan/network-slicing-with-RL)
- **Use Case:** RL for slice-level resource allocation
- **Paper:** No direct paper (based on concepts from IEEE JSAC 2019)
- **Description:** Simulates 5G slicing with variable load and evaluates DQN/Dueling DQN robustness.
- **Reputation:** ⭐ 11 | Forks: 1 | Last update: 2023

### 5. ns-O-RAN Gym
- **GitHub:** [wineslab/ns-o-ran-gym](https://github.com/wineslab/ns-o-ran-gym)
- **Use Case:** Closed-loop O-RAN control (e.g., traffic steering, energy saving)
- **Paper:** ["Enabling Online Reinforcement Learning Training for Open RAN"](https://dl.ifip.org/db/conf/networking/networking2024/1570981793.pdf), IFIP Networking 2024
- **Description:** Gym-compatible API for ns-3-based O-RAN environments. Focuses on near-real-time RIC scenarios.
- **Reputation:** ⭐ 2 | Forks: 1 | Last update: 2024

### 6. NetworkGym
- **GitHub:** [IntelLabs/networkgym](https://github.com/IntelLabs/networkgym)
- **Use Case:** Multi-access traffic management (LTE/5G/Wi-Fi)
- **Paper:** ["NetworkGym: Reinforcement Learning Environments for Multi-Access Traffic Management"](https://arxiv.org/abs/2411.04138), NeurIPS D&B 2024
- **Description:** Simulation-as-a-service for multi-RAT traffic management via ns-3. Includes example datasets and performance benchmarks.
- **Reputation:** ⭐ 8 | Forks: 7 | Last update: 2024

### 7. GrGym
- **GitHub:** [tkn-tub/gr-gym](https://github.com/tkn-tub/gr-gym)
- **Use Case:** Wireless PHY/MAC tasks with GNU Radio (e.g., rate control)
- **Paper:** ["GrGym: When GNU Radio goes to (AI) Gym"](https://ieeexplore.ieee.org/document/9869492), EW 2022
- **Description:** Enables Gym-style RL with GNU Radio simulations. Example: adaptive MCS control in 802.11p.
- **Reputation:** ⭐ 14 | Forks: 4 | Last update: 2022




## License

This list is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


---

For additions or suggestions, please open an issue or submit a pull request!

