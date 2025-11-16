# 📘 Multi-Agent Math Problem Solver

This project implements a **Multi-Agent System (MAS)** designed to solve math problems for students at different education levels.  
Each agent specializes in a unique explanation style and mathematical complexity:

- **Level 1 Agent — School Students**  
- **Level 2 Agent — College Students**  
- **Level 3 Agent — University Students**

The system is implemented entirely in a clean, modular, beginner-friendly **Jupyter Notebook**.

---

## 🚀 Features

### ✅ Multi-Agent Architecture

Each agent handles problems differently:

| Agent Level | Target User        | Capabilities |
|-------------|--------------------|--------------|
| **Level 1** | School students    | Basic arithmetic, simple equations, child-friendly explanations |
| **Level 2** | College students   | Algebra, calculus basics, step-by-step reasoning + learning hints |
| **Level 3** | University students | Differential equations, linear algebra, rigorous explanations |

---

### ✅ Automatic Routing

A custom **Orchestrator** and **Intake Module** automatically assign each problem to the correct agent based on:

- User’s academic level  
- Expected explanation style  
- Mathematical complexity  

---

### ✅ User Input System

The notebook includes a simple CLI-style input section where the user can type:

1. Their level → `school`, `college`, or `university`  
2. Any math problem  

The system outputs:

- **Which agent was used**
- **Answer**
- **Explanation**
- **Hint (for Level 2 agent)**

---

## 📂 Project Structure
├── Multi_Agent_Math_Solver.ipynb
├── README.md
└── /agents
├── level1_agent.py (optional modular version)
├── level2_agent.py
└── level3_agent.py

All essential code is also included inside the main notebook.

---

## 🧠 How the Agents Work

### **Level 1 — School Agent**
- Solves basic arithmetic  
- Uses simple real-world examples (apples, toys, money)  
- Avoids heavy mathematical notation  

---

### **Level 2 — College Agent**
- Solves algebra, calculus basics  
- Uses standard math notation  
- Provides step-by-step explanations + hints  
- Handles derivatives & quadratic equations  

---

### **Level 3 — University Agent**
- Solves advanced problems:
  - Differential equations  
  - Linear algebra  
  - Systems of equations  
  - Higher-level theoretical math  
- Provides rigorous, formal explanations  

---

## ▶️ Running the Notebook

1. **Clone the repository**
   ```bash
   git clone https://github.com/marufhasan-122/Multi-Agent-Math-Solver.git
   cd Multi-Agent-Math-Solver
# 🚀 How to Use

1. **Run all cells** in the notebook.
2. Go to the **User Input Section**.
3. Type your **level** + **math problem**.
4. The orchestrator will automatically choose the correct agent.

---

# 📦 Requirements

- **Python 3.8+**
- **Jupyter Notebook / Google Colab**
- No external libraries required  
  *(only built-in Python modules)*

---

# 🧪 Test Cases

## **Level 1 Tests (School Level)**
- `12 × 8`
- `15 − 7`
- Solve: `2x + 3 = 9`

## **Level 2 Tests (College Level)**
- Find derivative: `d/dx (3x² + 5x)`
- Solve quadratic: `x² − 5x + 6 = 0`
- Solve linear: `4x + 2 = 10`

## **Level 3 Tests (University Level)**
- Solve differential equation: `dy/dx + y = e^x`
- Solve system:  
  - `2x + 3y = 5`  
  - `x − y = 1`
- Higher-level theory problems

---

# 🛠 Future Improvements

- Add GUI with **Gradio** or **Streamlit**
- Add **ML-based automatic level detection**
- Add more agents  
  *(Statistics, Engineering Math, ML Math, etc.)*
- Add **LaTeX math rendering** for cleaner formatting

---

# 🤝 Contribution

Contributions are always welcome!  
Feel free to open an issue or submit a pull request to help improve the project.

---



