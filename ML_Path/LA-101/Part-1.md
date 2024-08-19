


# Part 1 of Linear Algebra 101 Notes

## Basic Definitions:
Scalar - Single numerical value that represents a quantity. But, does not tell you which way it is pointing. Scalars hold a single number, like an integer or float. 

Vector - ordered list of scalars. Ordered because the position of the scalar in the vector matters. 

$$\vec{y} = \begin{bmatrix}
0.99 \\
0.52 \\
0.45 \\
0.10 \\
0.26
\end{bmatrix} \begin{matrix}
\text{action} \\
\text{comedy} \\
\text{drama} \\
\text{horror} \\
\text{romance}
\end{matrix} \bigg\} 5 \text{ rows}$$

$$\vec{y} \\
\text{Is a vector that represents the movie *Avengers: Endgame*.} \\
\text{The vector contains five  numbers stacked on top of each other in a single column.} \\
\text{Each number describes a specific attribute of the movie.}$$

### Order Matters for Vectors!
- 0.99 for Action
- 0.10 for Horror 

This means that the movie is more an **ACTION** movie than **HORROR movie**

Vectors either have **one row or one column**.
To display values in multiple rows and columns
you use a **matrix**. 

Matrix - a two-dimensional array of scalars. 

Example: 
$${\color{blue}X} = \begin{bmatrix}
{\color{purple}3} & {\color{orange}3} \\
{\color{purple}4} & {\color{orange}3} \\
{\color{purple}5} & {\color{orange}3} \\
{\color{purple}5} & {\color{orange}4}
\end{bmatrix}
\begin{matrix}
\text{123 Maple Grove Lane} \\
\text{888 Ocean View Terrace} \\
\text{100 Birch Street} \\
\text{987 Sunflower Court}
\end{matrix} $$

Each row corresponds to the address. 
$$\text{The {\color{purple} first column} represents the number of {\color{purple} bedrooms} in the home.}$$
$$\text{The {\color{orange} second column} represents the number of {\color{orange} bathrooms.}}$$


### Concept Check!
1. How many bathrooms are in the home located at 100 Birch Street?
   
Answer: 3

2. How many elements does *M* contain?

$$\mathbf{M} \in \mathbb{R}^{1000 \times 80}$$

*M* has 1000 rows and 80 columns. 1000 * 80 = 80,000 elements.

3. How to write a matrix in python?

import torch

a = torch.tensor([[3,4],[5,5]])














