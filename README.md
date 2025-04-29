# Agent Decision-Making Framework

This project implements and compares a range of intelligent agent architectures designed to perceive environments and take actions based on different decision-making mechanisms. It covers reactive, goal-oriented, utility-maximizing, and learning agents through structured Python examples and visual simulations.

## 🧠 Agent Types Included

### 🔹 Simple Reflex Agent
- Responds to current percept only.
- Stateless and rule-based.
- Example: Thermostat that turns heating on/off.

### 🔹 Model-Based Reflex Agent
- Tracks internal state based on perception history.
- Better for partially observable environments.
- Example: Room-cleaning robot that updates room status.

### 🔹 Goal-Based Agent
- Makes decisions based on achieving defined goals.
- Supports action planning.
- Example: GPS system choosing a path to destination.

### 🔹 Utility-Based Agent
- Selects actions that maximize overall utility.
- Balances conflicting objectives.
- Example: Smart home system managing comfort and energy cost.

### 🔹 Learning Agent
- Learns from past actions and feedback.
- Improves behavior and adapts over time.
- Example: Product recommendation engine adapting to user interest.

## ⚙️ Features

- Full implementations of each agent model
- Realistic environment simulation using `GridWorld`
- Decision-making simulations via `ipywidgets`
- Visual performance comparison:
  - Response time
  - Success rate
  - Overall decision efficiency

## 📦 Dependencies

Install required libraries with:

```bash
pip install numpy matplotlib pandas ipywidgets
'''

##Clone the repository:


```bash
git clone https://github.com/NimnadiDNWA/Agent-Decision-Making-Framework.git
cd Agent-Decision-Making-Framework


📊 Agent Comparison Summary



| Agent Type         | Memory | Planning | Learning | Speed                | Intelligence |
|--------------------|--------|----------|----------|-------------         |--------------|
| Simple Reflex      | ❌     | ❌       | ❌       | ⭐⭐⭐⭐⭐⭐     | ⭐            |
| Model-Based        | ✅     | ❌       | ❌       | ⭐⭐⭐⭐          | ⭐⭐           |
| Goal-Based         | ✅     | ✅       | ❌       | ⭐⭐⭐            | ⭐⭐⭐          |
| Utility-Based      | ✅     | ✅       | ❌       | ⭐⭐              | ⭐⭐⭐⭐         |
| Learning           | ✅     | ✅       | ✅       | ⭐                 | ⭐⭐⭐⭐⭐⭐      |
