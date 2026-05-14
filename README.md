# Two-D-Transformation-Visualiser
Interactive Linear Alegbra Visualiser for AI
## Overview
This project is an interactive visualisation tool developed using Python and mathematical concepts to demonstrate how linear algebra transformations work in a simple 2D space.

This project visualises:
-Rotation
-Scaling
-Shearing
-Animated Transformation
-Combined Transformations

using matrix multiplication and geometric visualisation.

The idea behind this project is to build an intutitive understanding of how linear algebra forms the mathematical foundation of Artifical Interlligence, Machine Learning, Computer Graphics, and Robotics.

---

#Problem Statement
While learning linear algebra, I realized that concepts like matrix multiplication and transformations are much easier to understand when visualized.

I also found out that these same concepts are heavily used in Artificial Inteeligence, Computer Graphics, Robotics and Computer Vision.

So instead of only solving textbook questions, I wanted to build something interactive that could help me see what matrices are actually doing geometrically.

---

# Shapes Used

I experimented with multiple shapes to test how different objects respond to transformations:

- Square
- Star
- Letter A

One thing I found interesting was that the same transformation functions worked for every shape simply by changing the coordinate points.

That helped me understand how reusable transformation systems work in programming and graphics.

# Tools used 
-Python
-Numpy
-Matplotlib


---

#Objectives
-Visualise 2D linear transformations
- Show matrix multiplication graphically
- Build an interactive educational tool
- Understand the role of transformations in AI and graphics
- Apply linear algebra concepts using Python

---

# Mathematical Background

A linear transformation maps vectors from one coordinate system to another using matrix multiplication.

General transformation equation:

A(x) where A is a transformation matrix.


## Rotation Matrix

Rotation changes the orientation of an object while preserving distances and angles.

R = [[cosθ, -sinθ],
     [sinθ,  cosθ]]

---

## Scaling Matrix

Scaling changes the size of an object along coordinate axes.

S = [[a, 0],
     [0, b]]

---

## Shearing Matrix

Shearing distorts the shape along one axis.

H = [[1, k],
     [0, 1]]


# Some Personal Observations

A few things I noticed while building this project:

- Rotation preserves the overall geometry of the object.
- Shearing creates a surprisingly different visual effect compared to scaling.
- Animation made transformations much easier to intuitively understand.
- Even simple matrix multiplication can create complex geometric behavior.
- Building visualizations helped me understand linear algebra far better than solving equations alone


---

# Applications in AI

While building this project, I also explored how linear algebra connects to AI and Machine Learning.

Some areas where these concepts are used:
- Neural networks
- Image transformations
- Computer vision
- Vector embeddings
- Graphics rendering

This project helped me better understand why matrices are such an important part of AI systems.

---

# Future Improvements

Some things I would like to add later:
- 3D transformations
- Reflection transformations
- User-defined matrices
- Eigenvector visualization
- PCA visualization
- Streamlit web app version

---
# Project Structure

```plaintext
interactive-linear-algebra-visualizer/

├── linear_algebra_visualizer.ipynb
├── README.md
├── images/
```

---
Screenshots
