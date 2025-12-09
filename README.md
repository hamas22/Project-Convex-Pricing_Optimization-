# 📊 Pricing Optimization Project

## 🎯 Objective  
Develop a pricing model that **optimizes revenue or profit** while adhering to specific constraints, such as maximum production capacity or minimum acceptable profit margins.

---

## 📝 Tasks

### 1. Define the Pricing Model  
- Design a pricing model with an objective function (e.g., maximize revenue):

  \[
  \text{Revenue} = \sum_{i=1}^{n} p_i \cdot d_i(p_i)
  \]

  where:  
  - \( p_i \): price  
  - \( d_i(p_i) \): demand at that price  

- Add constraints such as:
  - Maximum price limit  
  - Maximum or minimum demand  
  - Production or budget constraints  

- Solve the optimization problem using **CVXPY**:
  - Use convex optimization techniques to maximize revenue or minimize costs.

---

### 2. Determine Convexity  
Check whether the revenue function is **convex** using:
- The Hessian matrix  
- CVXPY’s built-in convexity analysis  

Steps:
1. If the function is convex → **justify this mathematically**.  
2. If not convex → explain why.

---

### 3. Modify the Model (Non-Convexity)
Introduce modifications to intentionally make the model **non-convex**:
- Example: Add a non-linear term in the demand function to increase complexity.

---

### 4. Restore Convexity
Modify the model again to **restore convexity**, such as:
- Removing the non-linear term  
- Simplifying the demand function  
- Reformulating variables  

---

### 5. Visualization
Use **Matplotlib** or **Seaborn** to visualize relationships between price and revenue in the three scenarios:

1. Original (Convex)  
2. Modified (Non-Convex)  
3. Restored (Convex Again)

Recommended plots:
- Price vs Revenue  
- Demand curves  
- Profit curves  

---

## 🧾 Outcomes

### ✔ Python Script
A Python implementation that includes:
- Model setup (objective + constraints)  
- Convexity analysis  
- Non-convex modification  
- Restored convex version  
- Visualizations  

### ✔ Presentation / Report Summarizing:
- Problem setup and mathematical formulation  
- Key insights from analysis  
- Visualization comparison between convex, non-convex, and restored convex models  

---

## 🚀 Technologies Used
- **Python**
- **CVXPY** — Convex optimization
- **NumPy / Pandas** — Modeling & data
- **Matplotlib / Seaborn** — Visualizations

---

## 📧 Contact  
For questions or improvements, feel free to open an issue or submit a pull request!  
