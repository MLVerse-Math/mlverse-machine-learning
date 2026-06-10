---
noteId: "01ae3010649a11f1817b978734a592d7"
tags: []
---

# Mathematics of Tensors

## Tensor Representation

Tensor:

\[
T\_{ijk}
\]

where:

- i = first dimension
- j = second dimension
- k = third dimension

---

## Tensor Addition

For tensors:

\[
A+B
\]

Shapes must match.

Example:

\[
A\_{2\times2\times2}

- B\_{2\times2\times2}
  \]

  ***

## Scalar Multiplication

\[
kT
\]

Every element is multiplied by k.

---

## Tensor Product

Given vectors:

\[
u=
\begin{bmatrix}
u_1\\
u_2
\end{bmatrix}
\]

\[
v=
\begin{bmatrix}
v_1\\
v_2
\end{bmatrix}
\]

Outer Product:

\[
u\otimes v
\]

Result:

\[
\begin{bmatrix}
u_1v_1 & u_1v_2\\
u_2v_1 & u_2v_2
\end{bmatrix}
\]

---

## Tensor Reshaping

Example:

\[
(2,3)
\rightarrow
(3,2)
\]

without changing data.

---

## Tensor Transpose

Dimensions can be reordered.

Example:

\[
(32,224,224,3)
\]

becomes

\[
(32,3,224,224)
\]

for PyTorch.

---

## Broadcasting

TensorFlow and NumPy automatically expand dimensions when compatible.

Example:

\[
(3,3)

- (1,3)
  \]

Broadcasts the smaller tensor.
