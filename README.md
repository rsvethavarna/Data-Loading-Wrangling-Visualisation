# LINEAR ALGEBRA – COMPLETE RANKER MASTER NOTES

## 1. Scalars, Vectors, Matrices

* **Scalar**: single real number (ℝ)
* **Vector**: ordered list of numbers (column vector by default)
* **Matrix**: rectangular array of numbers

[
\mathbf{x} =
\begin{bmatrix}
x_1\
x_2\
x_3
\end{bmatrix},
\quad
A =
\begin{bmatrix}
a_{11} & a_{12}\
a_{21} & a_{22}
\end{bmatrix}
]

---

## 2. Vector Operations (CORE)

### Vector Addition

[
\mathbf{a} + \mathbf{b} =
\begin{bmatrix}
a_1 + b_1\
a_2 + b_2
\end{bmatrix}
]

### Scalar Multiplication

[
c\mathbf{a} =
\begin{bmatrix}
ca_1\
ca_2
\end{bmatrix}
]

### Dot Product (VERY IMPORTANT)

[
\mathbf{a}\cdot\mathbf{b} = |\mathbf{a}||\mathbf{b}|\cos\theta
]

Uses:

* Angle between vectors
* Orthogonality
* Projections

### Cross Product (3D only)

* Gives vector perpendicular to both vectors
* Magnitude = area of parallelogram

---

## 3. Norm (Length of a Vector)

[
|\mathbf{x}| = \sqrt{x_1^2 + x_2^2 + \dots + x_n^2}
]

Properties:

* Always ≥ 0
* Zero **iff** vector = zero vector

---

## 4. Linear Independence

Vectors (\mathbf{v}_1, \mathbf{v}_2, \dots) are linearly independent if:
[
c_1\mathbf{v}_1 + c_2\mathbf{v}_2 + \dots = 0 \Rightarrow c_1=c_2=\dots=0
]

**Exam shortcut**:

* Determinant ≠ 0 ⇒ independent

---

## 5. Matrix Operations

### Addition

* Same order matrices only

### Multiplication (NON‑COMMUTATIVE)

[
AB \ne BA
]

Dimension rule:
[
(m\times n)(n\times p) = (m\times p)
]

---

## 6. Identity & Zero Matrix

[
I = \begin{bmatrix}1 & 0\0 & 1\end{bmatrix}
]

[
AI = IA = A
]

---

## 7. Transpose

[
(A^T)*{ij} = A*{ji}
]

Key property:
[
(AB)^T = B^T A^T
]

---

## 8. Determinant (EXAM FAVORITE)

For 2×2:
[
|A| = ad - bc
]

Uses:

* Invertibility
* Area / volume scaling
* Linear independence

**Ultra‑Topper Insights**:

* det = 0 → rows lie in same plane
* det < 0 → orientation reversal
* |det| → scaling factor

---

## 9. Inverse of a Matrix

For 2×2:
[
A^{-1} = \frac{1}{|A|}
\begin{bmatrix} d & -b\ -c & a \end{bmatrix}
]

Exists **only if** det(A) ≠ 0.

---

## 10. System of Linear Equations

[
AX = B
]

Cases:

1. Unique solution → det(A) ≠ 0
2. Infinite solutions
3. No solution

Methods:

* Gaussian elimination
* Inverse method
* Cramer’s rule

**Ranker move**: decide det ≠ 0 or det = 0 in first 10 seconds.

---

## 11. Rank of a Matrix

* Number of linearly independent rows or columns
* Rank ≤ min(rows, columns)

Consistency condition:
[
\text{rank}(A) = \text{rank}([A|B])
]

---

## 12. Eigenvalues & Eigenvectors (HIGH YIELD)

[
A\mathbf{x} = \lambda\mathbf{x}
]

Steps:

1. Solve (|A-\lambda I|=0)
2. Find eigenvectors

**Power results**:

* Sum of eigenvalues = trace(A)
* Product of eigenvalues = det(A)
* Eigenvectors are not unique

---

## 13. Orthogonality

[
\mathbf{a}\cdot\mathbf{b} = 0
]

Orthogonal matrix:
[
Q^TQ = I
]

Preserves length and angles.

---

## 14. Diagonalization

[
A = PDP^{-1}
]

Possible **iff** sufficient independent eigenvectors exist.

---

## 15. Vector Spaces

A set V is a vector space if:

* Closed under addition
* Closed under scalar multiplication
* Contains zero vector

Examples:

* ℝⁿ
* Polynomial spaces
* Solution spaces

---

## 16. Basis & Dimension

* **Basis**: minimum spanning set
* **Dimension**: number of basis vectors

---

## 17. Column Space, Row Space, Null Space

* Column space → output directions
* Row space → constraints
* Null space → lost information

**Rank–Nullity Theorem**:
[
\text{rank}(A) + \text{nullity}(A) = \text{number of columns}
]

---

## 18. Geometric Interpretation (TOPPER EDGE)

* Vector → arrow
* Matrix → linear transformation
* Determinant → volume scaling
* Eigenvector → unchanged direction

---

## 19. Exam Traps (VERY IMPORTANT)

❌ Assuming AB = BA
❌ Forgetting det = 0 ⇒ no inverse
❌ Mixing span and basis
❌ Thinking eigenvectors are unique
❌ Over‑reducing matrices unnecessarily

---

## 20. Must‑Memorize Results (NO DERIVATION)

* Rank(A) = Rank(Aᵀ)
* Similar matrices have same eigenvalues
* Row space ⟂ null space
* Orthogonal matrices preserve norms

---

## 21. High‑Yield Question Types

1. Rank depending on parameter k
2. Eigenvalues of 2×2 / 3×3 matrix
3. Inverse using adjoint
4. Consistency of system
5. Basis of null space
6. Diagonalizability check
7. Orthogonality verification
8. Determinant geometry interpretation

---

## 22. One‑Line Ultra‑Revision Sheet

* det ≠ 0 → invertible
* rank → information
* null space → freedom
* eigen → scaling & stability
* transpose → mirror
* orthogonal → 90°

---

## 23. Ranker Revision Strategy

**Before exam**:

* Only formulas
* Only traps
* Only solved examples

**In exam**:

* Decide method instantly
* Avoid brute force
* Write clean final answers

---

### This document = FULL LINEAR ALGEBRA FIREPOWER
