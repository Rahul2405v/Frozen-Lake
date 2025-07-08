# Frozen Lake - Q-Learning & Policy-Based RL

This project demonstrates how an agent learns to solve the **Frozen Lake** environment using two reinforcement learning approaches: **Q-Learning** (value-based) and **Policy-Based Learning**.

## 🧠 Techniques Implemented

* **Q-Learning:**
  Learns a Q-table mapping state-action pairs to expected rewards.
  Uses ε-greedy exploration.

* **Policy-Based Learning:**
  Learns a policy directly using gradient-based updates.
  Suitable for larger/continuous environments.

## 🧪 Environment

* OpenAI Gym's `FrozenLake-v1`
* 4x4 grid with slippery movement
* Start `S`, Goal `G`, Frozen tiles `F`, Holes `H`

## 📁 Project Structure

```
Frozen-Lake/
├── q_learning.py         # Q-Learning implementation
├── policy_gradient.py    # Policy-Based Learning implementation
└── README.md             # Project documentation
```

## ▶️ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/Rahul2405v/Frozen-Lake.git
   cd Frozen-Lake
   ```
2. Install dependencies:
3. Run Q-Learning:

   ```bash
   python q_learning.py
   ```

4. Run Policy-Based:

   ```bash
   python policy_gradient.py
   ```

## ✅ Output

* Learns optimal actions to reach the goal.
* Shows performance improvement over episodes.

## 🛠️ Tools Used

* Python
* OpenAI Gym
* NumPy

## 📌 Author

**Rahul Vudathu**
GitHub: [@Rahul2405v](https://github.com/Rahul2405v)
