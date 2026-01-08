# 🔢 Matrix Computation Toolkit

A Python-based toolkit implementing fundamental matrix operations using numerical and linear algebra techniques, with a focus on algorithmic understanding rather than black-box library calls.

---

## 📌 Overview

This project provides a set of utilities for performing core matrix computations commonly used in linear algebra and numerical methods.  
The toolkit emphasizes **manual algorithmic implementation**, including **Gaussian elimination**, to strengthen conceptual understanding of matrix operations.

---

## ⚙️ Features

- Determinant computation  
- Matrix inverse calculation  
- Rank determination  
- Reduced Row Echelon Form (RREF)  
- Solving linear systems \( A\mathbf{x} = \mathbf{b} \)  
- Gaussian elimination implementation  

---

## 🧠 Methodology

- Implemented row operations and elimination steps explicitly
- Avoided high-level solver shortcuts to preserve numerical insight
- Verified correctness using known matrix identities and test cases

---

## 🧪 Example Usage

```python
A = [[2, 1, -1],
     [-3, -1, 2],
     [-2, 1, 2]]

b = [8, -11, -3]

x = solve_linear_system(A, b)
print(x)
