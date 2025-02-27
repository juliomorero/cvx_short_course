# SciPy 2022 CVXPY tutorial

CVXPY is an open source Python-embedded modeling language for convex optimization problems. It lets you express your problem in a natural way that follows the math, rather than in the restrictive standard form required by solvers. This tutorial will cover the basics of convex optimization, and how to use CVXPY to specify and solve convex optimization problems, with an emphasis on real-world applications. No prior knowledge of convex optimization is assumed.

## Getting started

1. Clone this repository
   ```
   > git clone git@github.com:juliomorero/cvx_short_course.git
   ```
2. After installing [python](https://www.python.org/downloads/release/python-3910/), create and activate a virtual environment
   ```
   > python -m venv <name_of_venv>
   > source <name_of_venv>/bin/activate
   ```
3. Inside the virtual environment install `pip-tools`
   ```
   > python -m pip install pip-tools
   ```
4. Compile dependencies
   ```
   > pip-compile --allow-unsafe
   ```
5. Install dependencies
   ```
   > pip-sync
   ```
6. Test your CVXPY installation by running `test.py` in the repository
   ```
   > python test.py
   ```

## Tutorial schedule

1. Convex optimization overview

- Mathematical optimization
- Convex optimization
- Solvers & modeling languages
- CVXPY example
- Real-world applications

2. Hello world

- Participants will install CVXPY and solve their first convex optimization problem. Participants will get experience
  with basic CVXPY syntax.
- [Hello world exercise](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/hello_world.ipynb)
- [Extra exercise](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/Lasso.ipynb)

3. Constructive convex analysis

- Mathematically define convex, concave, and affine functions. Give many examples.
- Introduce the composition rule for convex, concave, and affine functions, which generates the grammar for
  CVXPY.
- Introduce Disciplined Convex Programming (DCP).
- Learn how to construct convex optimization problems using DCP in CVXPY.

4. DCP exercises

- Participants will solve their first convex optimization problem with CVXPY, getting experience with basic CVXPY
  syntax.
- [DCP exercise](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/DCP_analysis.ipynb)
- [DCP site](https://dcp.stanford.edu/)
- [DCP quiz](https://dcp.stanford.edu/quiz)

5. Applications of convex optimization

- Present applications in finance, machine learning, vehicle control, and risk analysis.
- For each application, the instructors will give a motivating overview, and participants will then code up and solve
  a problem arising in the application using CVXPY. Concretely, exercises will consist of notebooks with missing
  sections, which the participants need to fill in with code constructing and solving a CVXPY problem.
- [Simple portfolio optimization](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/13.3.ipynb)
- [Portfolio rebalancing](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/13.21.ipynb)
- [Multiple risk models](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/13.22.ipynb)
- [Risk budget allocation](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/13.20.ipynb)
- [Energy storage](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/16.9.ipynb)
- [Vehicle scheduling](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/3.20.ipynb)
- [Flux balance analysis](https://github.com/cvxgrp/cvx_short_course/blob/master/exercises/17.3.ipynb)

6. If extra time, survey of advanced features

- Quasiconvex programming.
- Log-log convex programming.
- Differentiation through problems.
- Code generation.

7. Conclusion

- Recap.
- References for next steps in learning about and applying convex optimization.
