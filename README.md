# 🏋️ Chaos Simulator in a Gym

## 📌 Project Description

This project simulates the behavior of gym users returning dumbbells to their storage positions. It models how disorder ("chaos") increases when users place weights in the wrong slots. The objective is to quantify and visualize the level of disorganization after multiple user sessions, based on their discipline level.

---

## 🧠 Key Concepts

- **Dumbbell Rack Simulation**: A rack with dumbbells ranging from 10kg to 34kg (even numbers only) is created.
- **Chaos Metric**: Calculated by comparing the current position of each dumbbell to its original designated slot.
- **User Behavior**:
  - Type 1: Tries to return the dumbbell to the correct place; if not available, chooses randomly.
  - Type 2: Always places the dumbbell randomly.

---

## 🧩 Components

### 🔧 Classes

- `Academia`:
  - Manages dumbbells, their slots, and chaos calculation.
- `Usuario`:
  - Represents a gym user with type (1 or 2) and weight behavior.

### 🌀 Workflow

1. Initialize the gym with dumbbells.
2. Create 10 disciplined and 1 undisciplined user.
3. Users train by picking and returning weights.
4. Simulate 10 rounds of user activity.
5. Measure and output the final level of chaos.

---

## 📊 Output Example

- Final dumbbell arrangement
- Chaos value: a float between 0 and 1 indicating the proportion of misplaced dumbbells

---

## 📁 File Structure

- `simulador_caos.py`: Core simulation logic

---

## 🚀 How to Run

```bash
python simulador_caos.py
```

---
