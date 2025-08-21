# 📘 Linear Algebra for Machine Learning

This folder contains Jupyter notebooks demonstrating the use of **Linear Algebra concepts in Machine Learning**.  
Each notebook includes **explanations**, **code examples**, and **visualizations** to build intuition.

---

## 📂 Index of Notebooks

| #  | Notebook Name | Summary | Key Concepts |
|----|--------------|---------|--------------|
| 00 | [Use of Linear Algebra in ML](./00.%20Use-of-linear-algebra-in-ml.ipynb) | Demonstrates how vectors, matrix equations, and the normal equation are applied in regression and classification. | Training data vs hypothesis vs regression line, vector form `h(x) = θᵀx`, decision boundary in classification |

---


### 00 — Use of Linear Algebra in ML
**Goal:**  
Turn conceptual math notes into runnable demos showing:  
- **Training data (dots)** vs **hypothesis function (dashed line)** vs **final regression line (solid)**.  
- The **vector form** `h(x) = θᵀ x` where `θ = [b, w]` (bias and weight).  
- **Decision boundary** example for classification (`θᵀx = 0`).  

**Key Steps Covered:**
1. **Data points:** Represent features and labels, with natural noise.  
2. **Hypothesis function:** Initial guess with arbitrary parameters.  
3. **Regression line:** Computed using the **normal equation** (closed-form least squares).  
4. **Vector form:** Compact representation for predictions.  
5. **Decision boundary:** For classification, separates classes with a linear function.

**Takeaways:**
- The normal equation finds the optimal parameters without iterative methods.  
- Including bias in the feature vector (`x = [1, feature]`) simplifies computation.  
- Decision boundaries are where the linear model output equals zero.

---


## 📌 Template for Adding Future Notebooks

When you add a new `.ipynb` in this folder, document it like this:

### NN — Notebook Title
**Goal:**  
_Explain what the notebook demonstrates in 2–3 lines._

**Key Steps Covered:**
1. _Step 1_
2. _Step 2_
3. _Step 3_

**Takeaways:**
- _Point 1_
- _Point 2_
