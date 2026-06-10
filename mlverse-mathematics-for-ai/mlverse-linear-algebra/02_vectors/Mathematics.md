---
noteId: "c3f99020648011f1b8695f9ef6312315"
tags: []
---

# Mathematics of Vectors

# Definition

A vector is represented as:

\[
\mathbf{v}
=
\begin{bmatrix}
v_1\\
v_2\\
\vdots\\
v_n
\end{bmatrix}
\]

where:

\[
v_i \in \mathbb{R}
\]

---

# Vector Magnitude

For

\[
\mathbf{v}
=
\begin{bmatrix}
x\\
y
\end{bmatrix}
\]

Magnitude:

\[
||v||
=
\sqrt{x^2+y^2}
\]

Example:

\[
v=
\begin{bmatrix}
3\\
4
\end{bmatrix}
\]

\[
||v||
=
\sqrt{3^2+4^2}
=
5
\]

---

# Vector Addition

Given

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

Then

\[
u+v=
\begin{bmatrix}
u_1+v_1\\
u_2+v_2
\end{bmatrix}
\]

Example:

\[
\begin{bmatrix}
1\\
2
\end{bmatrix}

- \begin{bmatrix}
  3\\
  4
  \end{bmatrix}
  =
  \begin{bmatrix}
  4\\
  6
  \end{bmatrix}
  \]

  ***

# Vector Subtraction

\[
u-v
=
\begin{bmatrix}
u_1-v_1\\
u_2-v_2
\end{bmatrix}
\]

---

# Scalar Multiplication

\[
k
\begin{bmatrix}
x\\
y
\end{bmatrix}
=
\begin{bmatrix}
kx\\
ky
\end{bmatrix}
\]

Example:

\[
3
\begin{bmatrix}
2\\
4
\end{bmatrix}
=
\begin{bmatrix}
6\\
12
\end{bmatrix}
\]

---

# Dot Product

For vectors

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

Dot Product:

\[
u\cdot v
=
u_1v_1+u_2v_2
\]

Example:

\[
[2,3]\cdot[4,5]
=
23
\]

---

# Angle Between Vectors

\[
\cos\theta
=
\frac{u\cdot v}
{||u||\,||v||}
\]

Used heavily in:

- Similarity Search
- NLP
- Recommendation Systems

---

# Unit Vector

A unit vector has magnitude 1.

\[
\hat v
=
\frac{v}{||v||}
\]

Example:

\[
v=
\begin{bmatrix}
3\\
4
\end{bmatrix}
\]

\[
\hat v
=
\begin{bmatrix}
0.6\\
0.8
\end{bmatrix}
\]

---

# Distance Between Two Vectors

Euclidean Distance:

\[
d(u,v)
=
||u-v||
\]

Example:

\[
u=[1,2]
\]

\[
v=[4,6]
\]

\[
d=5
\]

---

# Key Takeaways

- Vectors store multiple values.
- Vectors possess magnitude and direction.
- Dot product measures similarity.
- Unit vectors normalize direction.
- Vectors form the basis of AI data representation.
