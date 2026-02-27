# 🚦 Signal-Controlled Multi-Path Autonomous Navigation in Grid Environment

## 📌 Project Overview

This project simulates an intelligent robot navigating a 30×30 grid environment containing randomly placed obstacles and multiple valid paths.  

The system demonstrates:

- Multi-path visualization (6 distinct colored routes)
- Obstacle-aware navigation
- Automatic shortest path selection
- Traffic signal-controlled junction decision
- Direction override (Left / Right turn logic)
- Animated robot movement simulation

The robot autonomously selects the shortest available path and follows it to reach the destination. At a defined junction, the robot can be instructed to change direction (e.g., turn right or left) based on signal logic.

---

## 🧠 Key Concepts Implemented

- Grid-based path planning
- Deterministic path selection
- Multi-route comparison
- Obstacle exclusion from valid paths
- Junction-based control logic
- Traffic-signal simulation
- Real-time animation using Matplotlib
- Decision-based path override

---

## 🗺️ Environment Details

- Grid Size: 30 × 30
- Start Position: (0, 0)
- Goal Position: (29, 29)
- Number of Paths: 6
- Obstacle Placement: Random (excluding valid path cells)
- Background: White
- Robot: White block
- Obstacles: Black
- Traffic Signal: Red block
- Goal: Yellow
- Start: Green

---

## 🎨 Path Colors

| Path Number | Color  |
|-------------|--------|
| Path 1      | Red    |
| Path 2      | Blue   |
| Path 3      | Purple |
| Path 4      | Cyan   |
| Path 5      | Orange |
| Path 6      | Green  |

---

## 🚀 Features

### ✅ Multi-Path Generation
Six structurally different valid paths are created between start and goal.

### ✅ Shortest Path Selection
The robot computes the length of each valid path and selects the shortest route automatically.

### ✅ Obstacle-Aware Environment
Random obstacles are placed only outside the valid path regions to maintain route feasibility.

### ✅ Junction Traffic Control
A signal is placed at a predefined junction where multiple paths intersect.  
At this junction:
- The robot pauses.
- Direction can be overridden (Left or Right).

### ✅ Animated Simulation
The robot moves step-by-step using time delay for clear visual representation.

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Matplotlib
- IPython Display (for animation)

---

## ▶️ How to Run (Google Colab)

1. Open Google Colab.
2. Copy the project code into a new notebook.
3. Run the cell.
4. Watch the animated simulation.

No additional installations are required.

---

## 📊 Algorithm Logic

1. Define 6 distinct valid paths.
2. Store all path coordinates.
3. Place random obstacles excluding valid path cells.
4. Compute path lengths.
5. Select the minimum-length path.
6. Animate robot movement.
7. Apply directional override at junction if required.

---

## 🎯 Learning Outcomes

- Understanding grid-based navigation
- Implementing path comparison logic
- Visualizing multi-path systems
- Designing junction-based decision models
- Simulating autonomous robot control

---

## 📌 Possible Extensions

- Implement A* algorithm for dynamic path generation
- Add diagonal movement
- Introduce dynamic obstacles
- Implement reinforcement learning for decision-making
- Add multiple traffic signals
- Add real-time cost comparison display

---

## 👨‍💻 Author

Kusuma.B
BTech – Computer Science Engineering (AI & ML)

---

## 📜 License

This project is developed for academic and demonstration purposes.
