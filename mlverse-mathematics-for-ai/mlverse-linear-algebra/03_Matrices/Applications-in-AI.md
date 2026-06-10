---
noteId: "7d2545b0649711f1817b978734a592d7"
tags: []
---

# Matrices in Artificial Intelligence

## Machine Learning

Datasets are matrices.

Example:

| Age | Salary | Experience |
| --- | ------ | ---------- |
| 25  | 50000  | 2          |
| 30  | 70000  | 5          |

becomes:

\[
X=
\begin{bmatrix}
25&50000&2\\
30&70000&5
\end{bmatrix}
\]

---

## Deep Learning

Neural networks use:

\[
Y=WX+b
\]

where:

W = Weight Matrix

---

## Computer Vision

Images are matrices.

Grayscale:

\[
Height \times Width
\]

RGB:

\[
Height\times Width\times3
\]

---

## Transformers

Attention computation:

\[
QK^T
\]

is matrix multiplication.

---

## Robotics

Transformation matrices describe:

- Rotation
- Translation
- Scaling

---

## Recommendation Systems

User-item interactions are stored in matrices.

---

## Reinforcement Learning

State transitions can be represented using matrices.

---

## Large Language Models

Every transformer block performs massive matrix operations.

Without matrices:

- GPT
- BERT
- Gemini
- Llama

could not exist.
