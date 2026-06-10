---
noteId: "f3226ed0649911f1817b978734a592d7"
tags: []
---

# Tensor Theory

## What is a Tensor?

A tensor is a multidimensional array.

It generalizes:

Scalar → Vector → Matrix → Tensor

---

## 0D Tensor (Scalar)

\[
5
\]

Shape:

\[
()
\]

---

## 1D Tensor (Vector)

\[
[1,2,3]
\]

Shape:

\[
(3)
\]

---

## 2D Tensor (Matrix)

\[
\begin{bmatrix}
1&2\\
3&4
\end{bmatrix}
\]

Shape:

\[
(2,2)
\]

---

## 3D Tensor

Example:

```text
[
 [
  [1,2],
  [3,4]
 ],
 [
  [5,6],
  [7,8]
 ]
]
```

Shape:

\[
(2,2,2)
\]

---

## Tensor Rank

Rank refers to the number of dimensions.

Examples:

Scalar → Rank 0

Vector → Rank 1

Matrix → Rank 2

3D Array → Rank 3

---

## Tensor Shape

Shape describes the size of each dimension.

Example:

\[
(32,224,224,3)
\]

means:

- 32 Images
- Height 224
- Width 224
- RGB Channels
