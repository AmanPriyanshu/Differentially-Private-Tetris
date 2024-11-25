# Differentially Private Tetris 👾

![demo-dp-tetris](/assets/tetris_demo.gif)

A unique twist on the classic Tetris game that teaches Differential Privacy (DP) concepts through interactive gameplay. Play Tetris while learning about privacy-preserving data analysis!

## Educational Goals

This game helps players understand:
- How differential privacy works in practice
- The privacy-utility tradeoff through epsilon budgeting
- Randomized response as a privacy mechanism
- How noise can protect individual data while maintaining usability

## How It Works

### 1. Privacy Mechanism
- Each Tetris block is protected using randomized response
- Players must spend their privacy budget (epsilon) to see blocks clearly
- Higher epsilon = clearer view but less privacy
- Lower epsilon = more privacy but harder gameplay

### 2. Learning Through Play
- **Privacy Budget Management**: Players learn to balance between privacy and utility
- **Randomized Response**: Experience how random noise can protect information
- **Visual Privacy**: See how different epsilon values affect data visibility
- **Real-world Parallel**: Similar to how companies can protect user data while maintaining functionality

### 3. Difficulty Levels
- **Easy Mode** (ε=150): Learn the basics with a generous privacy budget
- **Medium Mode** (ε=100): Balance privacy and gameplay
- **Hard Mode** (ε=10): Experience high-privacy constraints

---

Built to help people learn about privacy-preserving computation through interactive gameplay.
