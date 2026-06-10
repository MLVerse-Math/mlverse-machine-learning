---
noteId: "0da3b610649a11f1817b978734a592d7"
tags: []
---

# Tensors in Artificial Intelligence

## Deep Learning

Neural networks process tensors at every layer.

Input:

\[
X
\]

Weight Tensor:

\[
W
\]

Output:

\[
Y
\]

---

## Computer Vision

Image:

\[
224\times224\times3
\]

Tensor Shape:

```python
(224,224,3)
```

Batch of Images:

```python
(32,224,224,3)
```

---

## Natural Language Processing

Sentence:

```text
I love AI
```

Embeddings:

```python
(3,768)
```

---

## Transformers

Input Tensor:

```python
(batch_size,
 sequence_length,
 embedding_dimension)
```

Example:

```python
(32,512,768)
```

---

## Large Language Models

GPT processes tensors with billions of parameters.

Every attention mechanism uses tensor operations.

---

## Reinforcement Learning

States, actions, and rewards are represented as tensors.

---

## Robotics

Sensor streams:

- Cameras
- LiDAR
- IMU

are stored as tensors.

---

## Generative AI

Images, text, audio, and video generation all rely on tensor computations.
