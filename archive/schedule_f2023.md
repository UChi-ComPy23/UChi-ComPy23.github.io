Be sure to refresh this page to see the most recent version.

# Schedule - Fall 2023

This course follows a Tuesday/Thursday schedule.  There is a section for each day, with materials for that day.  This schedule is subject to change before a class is held.

Schedule Archives: [Fall 2020](archive/schedule_f2020.md) [Fall 2021](archive/schedule_f2021.md) [Winter 2022](archive/schedule_w2022.md)

## System Setup
0. [Basic Bash](https://uchi-compy23.github.io/notes/09_computing/basic_bash.html) [[Video Walkthrough](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=8e4dcb80-5d0b-41a6-8386-ac3e011e86ca)]
1. [Install Anaconda Python](https://github.com/uchi-compy23/materials/blob/master/lectures/00/conda.md) [[Video Walkthrough](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=af0fb6d1-ff96-4ac3-8daa-ac38001795f8)]
2. [Install Jupyter notebooks](https://github.com/uchi-compy23/materials/blob/master/lectures/00/jupyter.ipynb) [[Video Walkthrough](https://uchicago.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d30f69a5-9599-4f5f-b7ca-ac3800ee0966)]
3. [Using Python](https://uchi-compy23.github.io/notes/00_python/using_python.html)

## Day 00 - 9/26
### Class Material

0. [Python Basics](https://uchi-compy23.github.io/notes/00_python/basics.html)
1. [Bits, Bytes, and Numbers](https://uchi-compy23.github.io/notes/00_python/bitsbytes.html)
2. [Basic Containers and Packages](https://uchi-compy23.github.io/notes/00_python/basic_packages.html)
3. [Python Scripts](https://uchi-compy23.github.io/notes/00_python/using_python.html#python-scripts)  [[Example Script](https://github.com/uchi-compy23/materials/blob/master/lectures/01/script.py)] [[Download Example](https://raw.githubusercontent.com/uchi-compy23/materials/master/lectures/01/script.py)]

### Reading

* [Discrete or Continuous?](https://archive.siam.org/pdf/news/1975.pdf) by N. Trefethen. **Required**
* [PEP 0020 - The Zen of Python](https://www.python.org/dev/peps/pep-0020/) **Required**
* [PEP 0008 - Style Guide](https://www.python.org/dev/peps/pep-0008) (just skim and read anything interesting) **Required**
* [Array Programming with NumPy](https://www.nature.com/articles/s41586-020-2649-2) by Harris, et al. **Recommended**
* [Top-10 Algorithms of the 20th Century](https://archive.siam.org/pdf/news/637.pdf) by B. Cipra. **Recommended** for those interested in the culture of scientific computing.
  

## Day 01 - 9/28
### Homework

* Homework 0 released.


## Day 02 - 10/3
### Class Material
0. [Decorators](https://uchi-compy23.github.io/notes/00_python/decorators.html)
1. [Vectorization, numpy ufuncs, numba](https://uchi-compy23.github.io/notes/09_computing/performance/numpy_ufuncs.html)
2. [Memory layout](https://uchi-compy23.github.io/notes/02_linear_algebra/memory.html)

### Reading
* [NumPy Ufuncs](https://numpy.org/doc/stable/reference/ufuncs.html) **Recommended**


## Day 03 - 10/5


### Class Material
0. [Dense Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/numpy_scipy_linalg.html)
1. [SciPy BLAS and LAPACK Interfaces](https://uchi-compy23.github.io/notes/02_linear_algebra/blas_lapack.html)
2. [Python Objects, OOP](https://uchi-compy23.github.io/notes/00_python/classes.html)
If you don't have much prior experience with matrix factorizations, it is highly recommended to go through the exercises in the notebook.

### Reading

* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 13 - 18 (Creation of matrices) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 28 - 38 (Basic Matrix Manipulation) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 38 - 41 (Matrix Factorizations) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 54 - 55 (Eigenvalue Decompositions) **required**

* [LAPACK on netlib](https://www.netlib.org/lapack/) **Optional**
* [BLAS on netlib](https://www.netlib.org/blas/) **Optional**

  
* [Classes](https://docs.python.org/3/tutorial/classes.html) **Required** at least through 9.5 (inheritance)
* [Class definitions](https://docs.python.org/3/reference/compound_stmts.html#class-definitions) **Recommended**


## Day 04 - 10/10
### Homework
* Homework 2 released
  
### Class Material

0. [Modules and Packages](https://uchi-compy23.github.io/notes/00_python/modules.html) [[GitHub repository](https://github.com/uchi-compy23/python-packages)]
1. [Convergence of Algorithms](https://uchi-compy23.github.io/notes/01_analysis/convergence.html)
2. [Root Finding](https://uchi-compy23.github.io/notes/04_functions/roots.html)
     
### Reading

* [Modules](https://docs.python.org/3/tutorial/modules.html) **Required**
* [Newton's Method](https://mathworld.wolfram.com/NewtonsMethod.html) on Wolfram Mathworld **Recommended**

## Day 05 - 10/12
### Homework
* Homework 1 due

### Class Material
0. [Linear operators](https://uchi-compy23.github.io/notes/02_linear_algebra/linearoperators.html)
1. [Sparse matrix formats, `scipy.sparse`](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse.html)
2. [Sparse Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse_linalg.html) (We'll start if there is time)

### Reading
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 19 - 28 (Creation of sparse matrices, linear operators) **Required**


## Day 06 - 10/17

### Class material
0. [Sparse Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse_linalg.html) (Continued)
1. [Differentiation](https://uchi-compy23.github.io/files/differentiation.ipynb)


### Reading
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 105 - 110 (Differentiation) **Required**
* [SciPy `solve_ivp`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.solve_ivp.html) **Required**
  
## Day 07 - 10/19
### Homework
* Homework 2 due
* Homework 3 released
* Project groups finalized

### Class material
0. [Initial Value Problems](https://uchi-compy23.github.io/notes/04_functions/ode_initial.html)
1. [Unit testing](https://uchi-compy23.github.io/notes/09_computing/unittest.html)
2. [More on Plotting](https://uchi-compy23.github.io/notes/00_python/pyplot.html)
3. [Sympy](https://uchi-compy23.github.io/notes/04_functions/sympy.html)
   
### Reading
* [`unittest` documentation](https://docs.python.org/3.8/library/unittest.html) **Required** at least skim it to see what is in there.
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 165 - 178 (Initial Value Problems) **Required**
* [Matplotlib tutorials](https://matplotlib.org/tutorials/index.html) **Recommended** take a look around

## Day 08 - 10/24
### Class material
0. [Interpolation](https://uchi-compy23.github.io/notes/04_functions/interpolation.html)
1. [Integration, Quadrature](https://uchi-compy23.github.io/notes/04_functions/integration.html)

### Reading

* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp. 61 - 104 (Interpolation and Approximation) **Required**
* [SciPy interpolation tutorial](https://docs.scipy.org/doc/scipy/reference/tutorial/interpolate.html) **Recommended**
* [PyPlot Use FAQ](https://matplotlib.org/faq/usage_faq.html) **Required** (first half)
* [Matplotlib tutorials](https://matplotlib.org/tutorials/index.html) **Recommended** take a look around
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp. 111-123 **Required**
* [`scipy.integrate.quad`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.quad.html#scipy.integrate.quad) **Recommended**

## Day 09 - 10/26
### Homework
* Homework 3 due
* Homework 4 released
  
### Class material
0. Condition numbers
1. [Python Iterators and Generators](https://uchi-compy23.github.io/notes/00_python/iterators.html)

## Reading
* [Python Tutorial on Iterators](https://docs.python.org/3/tutorial/classes.html#iterators) **Required**

## Day 10 - 10/31
### Homework
* Project proposal due

### Class material
0. [Agent-based modeling](https://uchi-compy23.github.io/notes/09_computing/agent_based_models.html)
1. [Python Iterators and Generators](https://uchi-compy23.github.io/notes/00_python/iterators.html)
2. [Optimization](https://uchi-compy23.github.io/notes/03_optimization/scipy_opt.html)
   
## Reading
* [Python Tutorial on Generators](https://docs.python.org/3/tutorial/classes.html#generators) **Required**


## Day 11 - 11/02
### Homework
* Homework 4 due
* Homework 5 released
  
### Class Material
0. [Optimization](https://uchi-compy23.github.io/notes/03_optimization/scipy_opt.html)


## Day 12 - 11/07
### Class Material
0. [Pandas](https://uchi-compy23.github.io/notes/07_data/pandas.html)
1. [Scikit Learn](https://uchi-compy23.github.io/notes/07_data/sklearn.html)
   
## Day 13 - 11/09
### Homework
* Homework 5 due
* Homework 6 released

### Class Material
Cancelled

## Day 14 - 11/14
### Homework
* Midterm checkpoint due 11/14

### Class Material
0. [Distances](https://uchi-compy23.github.io/notes/08_geometry/distances.html)
1. [Nearest Neighbor Queries](https://uchi-compy23.github.io/notes/08_geometry/nearestneighbor.html)
2. [Dimensionality Reduction, Plotly](https://uchi-compy23.github.io/notes/07_data/dimension_reduction.html)
3. [Linear Algebra in PyTorch](https://uchi-compy23.github.io/notes/02_linear_algebra/pytorch.html)
    
## Day 15 - 11/16
### Homework
* Homework 6 due
* Homework 7 released

### Class Material

0. [Basic Neural Networks in PyTorch](https://uchi-compy23.github.io/notes/07_data/pytorch.html)
1. [Scipy distributions](https://uchi-compy23.github.io/notes/06_probability_statistics/scipy_stats.html)
2. [Monte Carlo Methods](https://uchi-compy23.github.io/notes/06_probability_statistics/monte_carlo.html)

## Day 16 - 11/28
### Class Material
0. Fast Multipole Method
   
## Day 17 - 11/30
### Homework
* Homework 7 due
  
### Class Material
0. Fast Fourier Transform (FFT)
1. [Boundary Value Problems](https://uchi-compy23.github.io/notes/04_functions/bvp.html)
   
## Project

Groups finalized 10/19.

Project proposal due 10/31.

Midterm checkpoint due 11/14.

Final Project report due 12/7.

## Finals Period

College reading period is 12/2-12/4


