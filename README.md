# Assignment 01 — Visualization and Analysis of Activation Functions

This notebook is part of my **Deep Learning learning journey**.  
It focuses on the implementation, derivatives, and visualization of commonly used activation functions.

---

## 📂 Contents
- **Implemented Activation Functions**
  1. Step  
  2. Sigmoid  
  3. ReLU  
  4. Leaky ReLU (α = 0.01)  
  5. PReLU (α = 0.25)  
  6. ELU (α = 1.0)  
  7. Swish  
  8. Linear  
  9. Softmax (vector-wise)  
  10. Tanh  

- **For each function:**
  - Python implementation  
  - Analytical derivative  
  - Plots showing the **activation** and its **derivative**  
  - Short description with formula, intuition, and typical use cases  

---

## 🖼️ Example Output
Each function is visualized with **two plots**:  

- **Left:** Activation output  
- **Right:** Derivative  

Example — *ReLU Function*:  

f(x) = max(0, x)

yaml
Copy code

- Activation: flat at 0 for negatives, linear for positives  
- Derivative: 0 for x < 0, 1 for x > 0, undefined at x = 0  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/deep-learning.git
Open Activation_Functions_Assignment.ipynb in Jupyter Notebook or Google Colab.

Run all cells to generate plots and outputs.

📌 Requirements
Python 3.x

NumPy

Matplotlib

🎯 Learning Outcomes
Understanding the role of activation functions in neural networks

Comparing their behavior and gradients

Identifying strengths/limitations of each function

👤 Author
Arslan Ali
BS Computer Science, Sukkur IBA University
Learning Deep Learning & AI

