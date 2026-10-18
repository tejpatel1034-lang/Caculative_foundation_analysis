<!-- ===================== HEADER (animated waving banner) ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=240&section=header&text=Calculative%20Foundation&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Linear%20Algebra%20for%20Student%20Performance%20Analysis&descAlignY=58&descSize=20" alt="Calculative Foundation banner" />
</p>

<!-- ===================== TYPING ANIMATION ===================== -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=36BCF7&center=true&vCenter=true&multiline=false&width=760&lines=Vectors+%E2%86%92+Matrices+%E2%86%92+Covariance+%E2%86%92+Eigenvectors;5%2C000+Students+%C3%97+15+Subjects;Data+Science+%7C+AI%2FML+%7C+Linear+Algebra;Turning+student+marks+into+geometry+%F0%9F%93%90" alt="Typing animation" />
  </a>
</p>

<!-- ===================== BADGES ===================== -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-Linear%20Algebra-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-Plots-11557c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-Heatmap-4c8cbf?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tasks-10%2F10%20Completed-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Dataset-5000%20Students-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Features-15%20Subjects-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Type-Theory%20%2B%20Practical-purple?style=flat-square" />
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700" alt="divider" />
</p>

## ✨ About the Project

> **How can a student's marks become a mathematical object?**

This project applies **Linear Algebra** to a student performance dataset. Each student becomes a **15-dimensional vector**, and the whole class becomes a **5000 × 15 matrix**. On top of that, we compute norms, angles, projections, covariance and eigenvalues, and interpret what they mean for **Data Science & Machine Learning**.

<table align="center">
  <tr>
    <td align="center"><h2>👩‍🎓 5,000</h2><sub>Students</sub></td>
    <td align="center"><h2>📚 15</h2><sub>Subject Features</sub></td>
    <td align="center"><h2>🧮 10</h2><sub>Tasks Completed</sub></td>
    <td align="center"><h2>📐 15×15</h2><sub>Covariance Matrix</sub></td>
  </tr>
</table>

---

## 🗺️ Project Roadmap

```mermaid
flowchart LR
    A[📄 CSV Dataset<br/>5000 × 15] --> B[➡️ Vectors<br/>& Norms]
    B --> C[📏 Dot Product<br/>& Angle]
    C --> D[✖️ Cross Product<br/>& Projection]
    D --> E[🔢 Matrix<br/>Operations]
    E --> F[📈 Line · Plane<br/>Hyperplane]
    F --> G[🔥 Covariance<br/>Heatmap]
    G --> H[🎯 Eigenvalues<br/>& Eigenvectors]
    H --> I[🏁 Conclusion]
    style A fill:#0f2027,color:#fff,stroke:#36BCF7
    style H fill:#2c5364,color:#fff,stroke:#36BCF7
    style I fill:#1b998b,color:#fff,stroke:#fff
```

---

## 📦 Dataset

| Item | Detail |
|---|---|
| 📁 File | `ds_ai_ml_full_subjects_5000.csv` |
| 👥 Rows | 5,000 students (one row = one student) |
| 📊 Features | 15 numerical subject scores |
| 🧾 Extra columns | `Student_ID`, `Average_Marks`, `Result` (not used in the feature matrix) |
| 🧱 Matrix | $X \in \mathbb{R}^{5000 \times 15}$ |

<details>
<summary><b>📚 Click to see all 15 subject features</b></summary>

<br/>

| # | Subject | # | Subject | # | Subject |
|---|---|---|---|---|---|
| 1 | Python | 6 | Mathematics_Advanced_Statistics | 11 | RM |
| 2 | SQL | 7 | DPF | 12 | SP |
| 3 | Excel | 8 | DSA | 13 | SL |
| 4 | Power_BI | 9 | DCI | 14 | ULP |
| 5 | Business_Case_Study | 10 | GenAI_AI_ML | 15 | NLP |

</details>

---

## 🧩 What's Inside

| # | Task | Core Idea | Status |
|:-:|---|---|:-:|
| 1 | **Vectors** | Student marks as a 15-D vector | ✅ |
| 2 | **L1 & L2 Norms** | Magnitude of a score vector | ✅ |
| 3 | **Dot Product & Angle** | Similarity of two students | ✅ |
| 4 | **Cross Product** | Perpendicular vector (3 subjects) | ✅ |
| 5 | **Projection** | Component of A along B | ✅ |
| 6 | **Matrix Operations** | Add, multiply, transpose, determinant, inverse | ✅ |
| 7 | **Line · Plane · Hyperplane** | 2D, 3D and 15D geometry | ✅ |
| 8 | **Covariance Matrix** | How subjects vary together + heatmap | ✅ |
| 9 | **Eigenvalues & Eigenvectors** | Directions of maximum variance | ✅ |
| 10 | **Summary & Conclusion** | Link to Data Science / ML | ✅ |

---

## 🔬 Highlights & Key Formulas

<details open>
<summary><b>➡️ 1–2 · Vectors & Norms</b></summary>

<br/>

First student (`DSAI0001`):

```
v₁ = [83, 49, 75, 59, 46, 63, 55, 72, 51, 66, 66, 58, 48, 53, 52]
```

$$\|v\|_1 = \sum |v_i| = 896 \qquad \|v\|_2 = \sqrt{\sum v_i^2} = \sqrt{55184} \approx 234.91$$

</details>

<details>
<summary><b>📏 3 · Dot Product & Angle</b></summary>

<br/>

$$\cos\theta = \frac{A \cdot B}{\|A\|_2 \, \|B\|_2}$$

| Pair | Dot Product | Angle |
|---|---|---|
| Student 1 & 2 | 69,939 | ≈ 10.61° |

A small angle means the two score vectors point in a similar direction. It does **not** mean the students perform identically.

</details>

<details>
<summary><b>✖️ 4–5 · Cross Product & Projection</b></summary>

<br/>

Using Python, SQL, Excel marks: $A=[83,49,75]$, $B=[91,82,82]$

$$A \times B = [-2132,\ 19,\ 2347] \quad\Rightarrow\quad A\cdot(A\times B)=0,\ \ B\cdot(A\times B)=0$$

$$\text{proj}_B A = \frac{A\cdot B}{B\cdot B}\,B = \frac{17721}{21729}\,B \approx [74.215,\ 66.875,\ 66.875]$$

</details>

<details>
<summary><b>🔢 6 · Matrix Operations</b></summary>

<br/>

$$A = \begin{bmatrix} 83 & 49 \\ 91 & 82 \end{bmatrix} \qquad \det(A) = 83(82) - 49(91) = 2347$$

$$A^{-1} = \frac{1}{2347}\begin{bmatrix} 82 & -49 \\ -91 & 83 \end{bmatrix}$$

> ℹ️ The full $5000 \times 15$ matrix is rectangular, so it has no ordinary determinant or inverse. Determinant/inverse are demonstrated on small square matrices (and on $X^TX$, which is $15 \times 15$).

</details>

<details>
<summary><b>📈 7 · Line, Plane & Hyperplane</b></summary>

<br/>

| Space | Equation | Use here |
|---|---|---|
| 2D line | $y = mx + c$ | SQL ≈ 0.72 · Python + 11.659 |
| 3D plane | $ax + by + cz = d$ | (Python, SQL, Excel) scatter |
| 15D hyperplane | $w_1x_1 + \dots + w_{15}x_{15} + b = 0$ | Concept of a decision boundary |

> ⚠️ The hyperplane is **illustrative**. No Pass/Fail classifier is trained in this project.

</details>

<details>
<summary><b>🔥 8 · Covariance Matrix</b></summary>

<br/>

$$\text{Cov}(X) = \frac{1}{n-1}(X-\bar{X})^T(X-\bar{X}) \qquad (n-1 = 4999)$$

| Quantity | Value |
|---|---|
| Var(Python) | 323.65 |
| Var(SQL) | 332.02 |
| Var(Excel) | 321.38 |
| Var(Power_BI) | 327.71 |
| Cov(Python, SQL) | 232.98 |
| Cov(Python, Excel) | 227.52 |
| Cov(SQL, Excel) | 233.94 |

Positive covariance means scores tend to move together. It is not causation, and it is not correlation (it depends on scale).

</details>

<details>
<summary><b>🎯 9 · Eigenvalues & Eigenvectors</b></summary>

<br/>

$$A v = \lambda v$$

| Rank | Eigenvalue | Rank | Eigenvalue |
|:-:|---:|:-:|---:|
| 1 | **3551.63** | 9 | 93.43 |
| 2 | 101.52 | 10 | 91.80 |
| 3 | 101.17 | 11 | 90.50 |
| 4 | 99.49 | 12 | 89.89 |
| 5 | 98.69 | 13 | 89.33 |
| 6 | 97.28 | 14 | 87.50 |
| 7 | 95.81 | 15 | 86.36 |
| 8 | 94.69 | | |

$$\frac{\lambda_1}{\sum \lambda_i} = \frac{3551.63}{4869.09} \times 100 \approx 72.94\%$$

The first eigenvector has almost equal weights (≈ 0.26) on all 15 subjects. It acts like an **overall performance direction**.

> ⚠️ 72.94% is the share of total variance along the first direction. It is **not** model accuracy, and an eigen-decomposition alone is not a full PCA workflow.

</details>

---

## 📊 Variance Along Each Direction (Eigenvalues)

```
λ1  ████████████████████████████████████████████████████  3551.63
λ2  ██                                                      101.52
λ3  ██                                                      101.17
λ4  ██                                                       99.49
λ5  ██                                                       98.69
...
λ15 ██                                                       86.36
```

One dominant direction explains most of the variance. Students mostly differ in *overall level*, not in a subject-specific way.

---

## 💻 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook Calculative_Foundation_Student_Performance.ipynb
```

<details>
<summary><b>🧪 Core code snippet</b></summary>

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv("ds_ai_ml_full_subjects_5000.csv")

subjects = [
    "Python", "SQL", "Excel", "Power_BI",
    "Business_Case_Study", "Mathematics_Advanced_Statistics",
    "DPF", "DSA", "DCI", "GenAI_AI_ML",
    "RM", "SP", "SL", "ULP", "NLP"
]

X = df[subjects].to_numpy()          # shape: (5000, 15)

# Covariance matrix + heatmap
cov_matrix = np.cov(X, rowvar=False)
cov_df = pd.DataFrame(cov_matrix, index=subjects, columns=subjects)

plt.figure(figsize=(12, 8))
sns.heatmap(cov_df, cmap="RdYlGn", center=0)
plt.title("Covariance Matrix of Student Subject Scores")
plt.tight_layout()
plt.show()

# Eigenvalues & eigenvectors
eigenvalues, eigenvectors = np.linalg.eigh(cov_matrix)
order = np.argsort(eigenvalues)[::-1]
eigenvalues = eigenvalues[order]
eigenvectors = eigenvectors[:, order]

explained = eigenvalues[0] / eigenvalues.sum() * 100
print(f"First direction explains {explained:.2f}% of total variance")
```

</details>

---

## 🗂️ Repository Structure

```
📦 Calculative-Foundation
 ┣ 📓 Calculative_Foundation_Student_Performance.ipynb
 ┣ 📊 ds_ai_ml_full_subjects_5000.csv
 ┣ 📝 Calculative_Foundation_Linear_Algebra_Roughwork.docx
 ┣ 📝 Calculative_Foundation_Roughwork_Calculations.docx
 ┣ 📄 PR. 4 Calculative Foundation.pdf
 ┗ 📘 README.md
```

---

## 🤖 Why This Matters for Data Science & ML

| Concept | Where it shows up |
|---|---|
| Vectors & norms | Feature representation, regularization (L1 / L2) |
| Dot product & angle | Cosine similarity, recommendation systems |
| Projection | Least squares, dimensionality reduction |
| Matrices | Datasets, neural network layers |
| Hyperplane | Linear classifiers, SVM decision boundaries |
| Covariance | Feature relationships, data exploration |
| Eigen-decomposition | PCA, variance analysis |

---

## ⚠️ Notes & Limitations

- Numerical values are the **recorded project results**. Re-run the notebook to reproduce them on your machine.
- Covariance shows association, **not causation**.
- The hyperplane section is **conceptual**; no Pass/Fail model is trained.
- The 72.94% figure is a **variance share**, not prediction accuracy.
- The dataset was generated with an approximate 82% pass / 18% fail target. Verify the actual split with `df["Result"].value_counts(normalize=True)`.

---

## 🚀 Possible Next Steps

- [ ] Verify all results directly against the CSV
- [ ] Run the notebook top to bottom and fix any errors
- [ ] Add a full PCA transformation (project onto top-k eigenvectors)
- [ ] Train a Pass/Fail classifier and compare with the hyperplane idea
- [ ] Prepare a short presentation / viva script

---

## 🙌 Author

<p align="center">
  <b>Made with ❤️ and Linear Algebra</b><br/>
  <a href="https://github.com/YOUR_USERNAME"><img src="https://img.shields.io/badge/GitHub-YOUR__USERNAME-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" /></a>
</p>

<p align="center">⭐ If you liked this project, give it a star! ⭐</p>

<!-- ===================== FOOTER (animated wave) ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=140&section=footer&animation=twinkling" alt="footer" />
</p>
