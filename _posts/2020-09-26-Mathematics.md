---
title: Basic Mathematics
# tags: TeXt
# article_header:
#   type: cover
#   image:
#     src: /Images/Mathematics/IMG_1027.png
---

## Basic Fomula

![Hi](/Images/Mathematics/IMG_1027.png)

Given a mapping: $f: R^N \rightarrow R^M$ and input X with dimension N, output with dimension M,
we we call the matrix with following form a Jocobian Matrix:
$$
\frac{\partial{y}}{\partial{x}} = \begin{bmatrix}
    \frac{\partial{y_1}}{\partial{x_1}} & \frac{\partial{y_1}}{\partial{x_2}} & \cdots & \frac{\partial{y_1}}{\partial{x_N}} \\
    \frac{\partial{y_2}}{\partial{x_1}} & \frac{\partial{y_2}}{\partial{x_2}} & \cdots & \frac{\partial{y_2}}{\partial{x_N}} \\
    \vdots & \vdots & \ddots & \vdots \\
    \frac{\partial{y_M}}{\partial{x_1}} & \frac{\partial{y_M}}{\partial{x_2}} & \cdots & \frac{\partial{y_M}}{\partial{x_N}} \\
\end{bmatrix}
$$
