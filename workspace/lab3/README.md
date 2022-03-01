# Due date: March 14, 2022 at 11:59 P.M.

# Lab 3: Matrix Multiplication - Tiling & Caches

At this point in the course, we have seen how neural networks are trained and evaluated from an algorithmic perspective. In this lab, we will see how these algorithms are optimized for performance on CPUs. Our goal is to get a more complete understanding of how software interacts with the CPU at an architectural level, and then optimize it so that it is cache-friendly.

## Part 1: Cache Baiscs

In the first part, we will go through the basic concepts about caches, such as direct mapped caches and set associative caches, using a simple matrix multiplication example. Answer Questions 1 ~ 7 in the notebook `1_cache_basics.ipynb`. 

## Part 2: Tiled Matrix Multiplication

The second part of this lab analyzes tiled matrix multiplication. We are using [Fibertree](https://github.com/Fibertree-Project/fibertree) to visualize each step in matrix multiplication. You will analyze how tiling changes memory access pattern. Answe Question 8 in the notebook `2_cache_tiling.ipynb`.

## Part 3: Optimize Matrix Multiplication & Caches

Finally, we will optimize matrix multiplication between large matrices to minimize the total area and energy consumed by caches. You can design your own caches and optimize matrix multiplication with tiling. Answer Question 9 in the notebook `3_cache_design.ipynb`. 
