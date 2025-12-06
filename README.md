🌾 Grain Growth Simulation in Metals



https://github.com/user-attachments/assets/36f602d8-e231-42f4-b18d-19096cbc322a







## 📖 Project Overview
An interactive simulation of grain growth phenomenon in metals during heat treatment. This educational tool visualizes how metal microstructure evolves with temperature and time, using the p5.js library.

## 🎯 Scientific Background

### What is Grain Growth?
Grain growth is a metallurgical process where larger grains grow at the expense of smaller ones to reduce interfacial energy. This occurs during annealing and significantly affects mechanical properties like strength and ductility.

### Physical Principles:
- Energy minimization: System reduces total grain boundary area
- Temperature dependence: Higher temperature = faster growth
- Statistical nature: Random grain boundary movement

### Mathematical Model:
The simulation uses a Monte Carlo algorithm based on the Boltzmann distribution:


P = exp(-ΔE / kT)

Where:
- P: Probability of grain boundary movement
- ΔE: Energy difference between states
- k: Boltzmann constant
- T: Temperature

## 🚀 Features

### 🎮 Interactive Controls:
- Play/Pause: Control simulation in real-time
- Temperature adjustment: See how heat affects growth rate
- Reset: Start fresh with new random seeds
- Click to add: Add new grains anywhere on the grid

Controls Reference:
Control Action Shortcut
Play/Pause Start/stop simulation Spacebar
Reset Restart simulation R key
Increase Temp Speed up growth + key
Decrease Temp Slow down growth - key
Add Grain Click on empty grid Mouse click
Random Grain Add random grain C key

📈 Simulation Results

Expected Behavior:

1. Initial Stage: Many small grains (high boundary energy)
2. Growth Phase: Grains merge, boundaries move
3. Mature Stage: Few large grains (low boundary energy)
4. Stable State: Minimal boundary movement

Temperature Effects:

· Low Temp (0.1-0.5): Slow, controlled growth
· Medium Temp (0.5-1.5): Natural grain evolution
· High Temp (1.5-3.0): Rapid, chaotic growth

Here is an example illustrating the type of simulation Cellular


<img width="754" height="682" alt="image" src="https://github.com/user-attachments/assets/1c92c10d-696f-4a1b-86dd-7a3d4468a0a6" />




Here is an example illustrating the type of simulation Voronoi

<img width="761" height="687" alt="image" src="https://github.com/user-attachments/assets/3678b6ee-abe4-4449-bbb7-347a2429c368" />


🏆 Achievements

This project successfully demonstrates:

· ✅ Complete simulation of grain growth phenomenon
· ✅ Interactive user interface with real-time controls
· ✅ Scientific accuracy based on metallurgical principles
· ✅ Educational value for material science students
· ✅ Code quality with proper structure and documentation

name : mohammad alsaleh
https://editor.p5js.org/ghaithaa-ib/sketches/uwyRjbk_H
