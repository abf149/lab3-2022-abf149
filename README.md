# Due date: March 14, 2022 at 11:59 P.M.

# Lab 3: Matrix Multiplication - Tiling & Caches

At this point in the course, we have seen how neural networks are trained and evaluated from an algorithmic perspective. In this lab, we will see how these algorithms are optimized for performance on CPUs. Our goal is to get a more complete understanding of how software interacts with the CPU at an architectural level, and then optimize it so that it is cache-friendly.

In this lab, we will analyze how matrix multiplication can be optimized for caching. We simplified the behavior of caches in [./workspace/lab3/cache.py](./workspace/lab3/cache.py), and we will simulate cache hit/miss throughout matrix multiplication. Our final objective will be optimizing matrix multiplication for small cache energy and size. For detailed instructions, please read [./workspace/lab3/README.md](./workspace/lab3/README.md). 

## Using Docker

Please start the Docker (and the Jupyter server) same as in Lab 1 and 2, please pull the docker first and then start with `docker-compose up`. 
```
cd <your-git-repo-for-lab3>
docker-compose pull
docker-compose up
```
After finishing the lab, please commit all changes and push back to this repository.
