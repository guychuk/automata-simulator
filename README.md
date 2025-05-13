# 🤖 Automata Simulator

<p align="center">
  <a href="https://guychuk.github.io/automata-simulator/">
    <img src="public/images/favicon.png" alt="Logo" width="100" height="100">
  </a>
</p>

<p align="center">
  <strong>A simple automata simulator.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white">
</p>

---

## 🧠 Overview

This is a simulator for various types of automata, built with TypeScript. It allows you to **define**, **visualize**, and **simulate** the behavior of finite state machines:  
- ✅ *DFA* (Deterministic Finite Automaton)  
- 🔀 *NFA* (Non-deterministic Finite Automaton)

---

## ✨ Features

- 🔄 **Finite State Automata Simulation**  
  Supports both DFA and NFA simulations.

- 🎨 **Visualization**  
  See the automaton graphically and follow transitions live.

- ⏱️ **Step-by-step Execution**  
  Simulate your automaton one step at a time for better understanding.

- 🧾 **Clear Results**  
  Displays simulation results in a user-friendly format.

---

## 💻 Local Installation

1. **Prerequisites**  
   - [Node.js](https://nodejs.org/) (v14 or newer)  
   - [npm](https://www.npmjs.com/) (comes with Node.js)

2. **Clone the repository**
    ```bash
    git clone https://github.com/guychuk/automata-simulator.git
    cd automata-simulator
    ```

3. **Install dependencies**
    ```bash
    npm install
    ```

4. **Build the project**
    ```bash
    npm run build
    ```
    This creates a `dist` folder with compiled files.

5. **Run locally**
    - Open `dist/index.html` in your browser.

6. **Or start a local dev server**
    ```bash
    npm run serve
    ```
    - Visit [http://localhost:8080](http://localhost:8080)

---

## 🧪 Usage

1. **Define your automaton:**
   - Enter your alphabet, states, initial state, accepting states, and transitions.
   - Submit using the **"Submit Automaton"** button.
   - Use an empty string for ε-transitions: `q0,,q2`

2. **Run the simulator:**
   - Enter your input string.
   - (Optional) Adjust step duration.
   - Click **"Run"** to start simulation.

---

## 🎥 Demo

![demo](assets/demo.gif)

This shows an automaton checking if a binary number is divisible by 3.

- `1010` (10) → ❌ Not divisible  
- `1011` (11) → ❌ Not divisible  
- `1100` (12) → ✅ Divisible

---

## 🌐 Live Demo

Try it now on GitHub Pages 👉 [**Live Demo**](https://guychuk.github.io/automata-simulator/).
