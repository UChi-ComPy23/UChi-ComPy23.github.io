Be sure to refresh this page to see the most recent version.

# Schedule - Fall 2024

This course follows a Tuesday/Thursday schedule.  There is a section for each day, with materials for that day.  This schedule is subject to change before a class is held.

Schedule Archives: [Fall 2020](archive/schedule_f2020.md) [Fall 2021](archive/schedule_f2021.md) [Winter 2022](archive/schedule_w2022.md) [Fall 2023](archive/schedule_f2023.md)

## System Setup
0. [Basic Bash](https://uchi-compy23.github.io/notes/09_computing/basic_bash.html)
1. [Install Anaconda Python](https://uchi-compy23.github.io/notes/00_python/conda.html)
2. [Install Jupyter notebooks](https://uchi-compy23.github.io/notes/00_python/jupyter.html)
3. [Using Python](https://uchi-compy23.github.io/notes/00_python/using_python.html)
   
## Day 00 - 10/01
### Class Material
[Intro Slides](https://uchi-compy23.github.io/files/Course_intro_2024.key)

0. [Python Scripts](https://uchi-compy23.github.io/notes/00_python/using_python.html#python-scripts)  [[Example Script](https://github.com/uchi-compy23/materials/blob/master/lectures/01/script.py)] [[Download Example](https://raw.githubusercontent.com/uchi-compy23/materials/master/lectures/01/script.py)]
1. [Python Basics](https://uchi-compy23.github.io/notes/00_python/basics.html)

3. [Basic Containers and Packages](https://uchi-compy23.github.io/notes/00_python/basic_packages.html)

### Reading

* [Discrete or Continuous?](https://archive.siam.org/pdf/news/1975.pdf) by N. Trefethen. **Required**
* [PEP 0020 - The Zen of Python](https://www.python.org/dev/peps/pep-0020/) **Required**
* [PEP 0008 - Style Guide](https://www.python.org/dev/peps/pep-0008) (just skim and read anything interesting) **Required**
* [Array Programming with NumPy](https://www.nature.com/articles/s41586-020-2649-2) by Harris, et al. **Recommended**
* [Top-10 Algorithms of the 20th Century](https://archive.siam.org/pdf/news/637.pdf) by B. Cipra. **Recommended** for those interested in the culture of scientific computing.
  

## Day 01 - 10/03
### Homework
* Homework 0 released.
* See the [git tutorial](https://github.com/caam37830/git-tutorial) if you are not familiar with git version control.
  
### Class Material

0. [Functions in Python](https://uchi-compy23.github.io/notes/00_python/functions.html)
1. [Recursion](https://uchi-compy23.github.io/notes/01_analysis/recursion.html)
2. [Bits, Bytes, and Numbers](https://uchi-compy23.github.io/notes/00_python/bitsbytes.html)
3. [Asymptotic notation](https://uchi-compy23.github.io/notes/01_analysis/asymptotic_notation.html)


### Reading

* [Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) **Required**
* [More on defining functions](https://docs.python.org/3/tutorial/controlflow.html#more-on-defining-functions) **Required**
* [Function definitions](https://docs.python.org/3/reference/compound_stmts.html#function-definitions) **Recommended**

## Day 02 - 10/08
### Class Material
0. [Decorators](https://uchi-compy23.github.io/notes/00_python/decorators.html)
1. [Vectorization, numpy ufuncs, numba](https://uchi-compy23.github.io/notes/09_computing/performance/numpy_ufuncs.html)
2. [Memory layout](https://uchi-compy23.github.io/notes/02_linear_algebra/memory.html)

### Reading
* [NumPy Ufuncs](https://numpy.org/doc/stable/reference/ufuncs.html) **Recommended**



## Day 03 - 10/10
### Homework
* Homework 0 due.
* Homework 1 released.

### Class Material
0. [Dense Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/numpy_scipy_linalg.html) If you don't have much prior experience with matrix factorizations, it is highly recommended to go through the exercises in the notebook.
2. [Python Objects, OOP](https://uchi-compy23.github.io/notes/00_python/classes.html)


### Reading

* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 13 - 18 (Creation of matrices) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 28 - 38 (Basic Matrix Manipulation) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 38 - 41 (Matrix Factorizations) **required**
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 54 - 55 (Eigenvalue Decompositions) **required**

* [LAPACK on netlib](https://www.netlib.org/lapack/) **Optional**
* [BLAS on netlib](https://www.netlib.org/blas/) **Optional**

  
* [Classes](https://docs.python.org/3/tutorial/classes.html) **Required** at least through 9.5 (inheritance)
* [Class definitions](https://docs.python.org/3/reference/compound_stmts.html#class-definitions) **Recommended**


## Day 04 - 10/15
### Homework
* Homework 2 released
  
### Class Material

0. [SciPy BLAS and LAPACK Interfaces](https://uchi-compy23.github.io/notes/02_linear_algebra/blas_lapack.html)
1. [Modules and Packages](https://uchi-compy23.github.io/notes/00_python/modules.html) [[GitHub repository](https://github.com/uchi-compy23/python-packages)]
2. [Convergence of Algorithms](https://uchi-compy23.github.io/notes/01_analysis/convergence.html)
3. [Root Finding](https://uchi-compy23.github.io/notes/04_functions/roots.html)
     
### Reading

* [Modules](https://docs.python.org/3/tutorial/modules.html) **Required**
* [Newton's Method](https://mathworld.wolfram.com/NewtonsMethod.html) on Wolfram Mathworld **Recommended**


## Day 05 - 10/22
### Class Material
0. [Linear operators](https://uchi-compy23.github.io/notes/02_linear_algebra/linearoperators.html)
1. [Sparse matrix formats, `scipy.sparse`](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse.html)
2. [Sparse Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse_linalg.html) (We'll start if there is time)

### Reading
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 19 - 28 (Creation of sparse matrices, linear operators) **Required**

## 10/26
### Homework
* Homework 2 due

## Day 06 - 10/24

### Class material
0. [Sparse Linear Algebra](https://uchi-compy23.github.io/notes/02_linear_algebra/sparse_linalg.html) (Continued)
1. [Differentiation](https://uchi-compy23.github.io/files/differentiation.ipynb)


### Reading
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 105 - 110 (Differentiation) **Required**
* [SciPy `solve_ivp`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.solve_ivp.html) **Required**
  
## Day 07 - 10/29
### Homework
* Homework 3 released

### Class material
0. [Initial Value Problems](https://uchi-compy23.github.io/notes/04_functions/ode_initial.html)
1. [Unit testing](https://uchi-compy23.github.io/notes/09_computing/unittest.html)
2. [Sympy](https://uchi-compy23.github.io/notes/04_functions/sympy.html)
   
### Reading
* [`unittest` documentation](https://docs.python.org/3.8/library/unittest.html) **Required** at least skim it to see what is in there.
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp 165 - 178 (Initial Value Problems) **Required**


## Day 08 - 10/21

### Class material
0. [More on Plotting](https://uchi-compy23.github.io/notes/00_python/pyplot.html)
1. [Interpolation](https://uchi-compy23.github.io/notes/04_functions/interpolation.html)
2. [Integration, Quadrature](https://uchi-compy23.github.io/notes/04_functions/integration.html)


### Reading
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp. 61 - 104 (Interpolation and Approximation) **Required**
* [SciPy interpolation tutorial](https://docs.scipy.org/doc/scipy/reference/tutorial/interpolate.html) **Recommended**
* [PyPlot Use FAQ](https://matplotlib.org/faq/usage_faq.html) **Required** (first half)
* [Matplotlib tutorials](https://matplotlib.org/tutorials/index.html) **Recommended** take a look around
* [Mastering SciPy](https://catalog.lib.uchicago.edu/vufind/Record/11908913) pp. 111-123 **Required**
* [`scipy.integrate.quad`](https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.quad.html#scipy.integrate.quad) **Recommended**


## Day 09 - 11/05
### Homework
* Homework 3 due
* Homework 4 released
* Project proposal due


### Class material
0. [Integration, Quadrature](https://uchi-compy23.github.io/notes/04_functions/integration.html) (continued)
1. [Python Iterators and Generators](https://uchi-compy23.github.io/notes/00_python/iterators.html)
2. Condition numbers


## Reading
* [Python Tutorial on Iterators](https://docs.python.org/3/tutorial/classes.html#iterators) **Required**
* [Python Tutorial on Generators](https://docs.python.org/3/tutorial/classes.html#generators) **Required**

## Day 10 - 11/07
### Class material
0. [Agent-based modeling](https://uchi-compy23.github.io/notes/09_computing/agent_based_models.html)
2. [Optimization](https://uchi-compy23.github.io/notes/03_optimization/scipy_opt.html)
   

## Day 11 - 11/02
### Homework
* Homework 4 due
* Homework 5 released
  
### Class Material
0. [Optimization](https://uchi-compy23.github.io/notes/03_optimization/scipy_opt.html)


 
## Project

Groups finalized 10/21.

Project proposal due 11/5.

Midterm checkpoint due 11/19.

Final Project report due 12/11.

## Finals Period

College reading period is 12/7-12/9
