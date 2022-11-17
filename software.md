---
layout: page
title: Software
---

Some of our projects aim to facilitate the research workflow itself and make it more
reproducible. These will be found in the section [Workflow Tools](#workflow-tools).
Others try to facilitate research by providing methodological tools and graphical
assistance. These will be found in the section
[Methodological Tools](#methodological-tools). Many of these tools are used in our
research. In the section [Research Software](#research-software) we list packages that
implement economic models.

## <ins>*General purpose tools*<ins>

### estimagic
estimagic is a Python package to fit large-scale empirical models to data and make
inferences about the estimated model parameters. It is especially suited to solve
difficult optimization problems. It provides several advantages over similar packages,
including a unified interface that supports a large number of local and global
optimization algorithms and the possibility of monitoring the optimization procedure via
a beautiful interactive dashboard. It provides tools for nonlinear optimization,
numerical differentiation, and statistical inference.
[(Documentation)](https://estimagic.readthedocs.io){:target="_blank"}

### pybaum
pybaum provides tools to work with pytrees which is a concept borrowed from JAX.
Pytree's refer to tree-like structures built out of container-like Python objects. We
use pybaum in several of our packages. One notable example is estimagic.
[(Documentation)](https://pybaum.readthedocs.io){:target="_blank"}

### dags
dags provides tools to create executable dags from interdependent functions.
[(Documentation)](https://dags.readthedocs.io){:target="_blank"}

## <ins>*Economic models and applications*</ins>

### sid
sid is an agent-based simulation model for infectious diseases like COVID-19. It scales
from simple examples to complex models which makes it an ideal tool for prototyping,
educational purposes, and research.
[(Documentation)](https://sid-dev.readthedocs.io/en/latest/){:target="_blank"}
> Gabler J., Raabe T., Röhrl K. & von Gaudecker H. (2022) [**The Effectiveness of Strategies to Contain SARS-CoV-2: Testing, Vaccinations, and NPIs**](https://arxiv.org/abs/2106.11129),  *arXiv preprint arXiv:2106.11129*, submitted.

### respy
respy is an open-source framework written in Python for the simulation and
estimation of some finite-horizon discrete choice dynamic programming models. The group
of models which can be currently represented in `respy` are called Eckstein–Keane–Wolpin
models. [(Documentation)](https://respy.readthedocs.io){:target="_blank"}
> Eisenhauer P., Gabler J. & Janys L. (2021) [**Structural models for policy-making: Coping with parametric uncertainty**](https://arxiv.org/abs/2103.01115), *arXiv preprint 	arXiv:2103.01115*, submitted.

### pydsge
pydsge is a Python package that allows to simulate, filter, and estimate DSGE models
with occasionally binding constraints. As such, it allows to conduct full-blown Bayesian
estimations (including Bayesian filtering) of macroeconomic models featuring an
endogenous zero lower bound on nominal interest rates.
[(Documentation)](https://pydsge.readthedocs.io){:target="_blank"}
> Boehl G. (2022) [**Efficient Solution and Computation of Models with Occasionally Binding Constraints**](https://gregorboehl.com/live/obc_boehl.pdf), working paper.

### skillmodels
skillmodels a Python implementation of estimators for skill formation models. 
[(Documentation)](https://skillmodels.readthedocs.io){:target="_blank"}

### econsieve
econsive is a collection of nonlinear Bayesian filters, in particular for high
dimensional models. The filters are implemented in python. It provides the
Transposed-Ensemble Kalman Filter (TEnKF) for state and likelihood inference, and the
Nonlinear Path-Adjusting Smoother (NPAS) for exact smoothed states.
[(Documentation)](https://econsieve.readthedocs.io){:target="_blank"}

### ruspy
ruspy is an open-source package for the simulation and estimation of a prototypical
infinite-horizon dynamic discrete choice model based on [Rust
(1987)](https://doi.org/10.2307/1911259){:target="_blank"}.
[(Documentation)](https://ruspy.readthedocs.io){:target="_blank"}
> Blesch M. & Eisenhauer P. (2021) [**Robust decision-making under risk and ambiguity**](https://arxiv.org/abs/2104.12573), *arXiv preprint arXiv:2104.12573*, submitted 


### grmpy
grmpy is an open-source Python package for the simulation and estimation of the
generalized Roy model. It serves as a teaching tool to promote the conceptual framework
of the generalized Roy model, illustrate a variety of issues in the econometrics of
policy evaluation, and showcases basic software engineering practices.
[(Documentation)](https://grmpy.readthedocs.io){:target="_blank"}

## <ins>*Workflow Tools*</ins>

### pytask
pytask is a workflow management system which facilitates reproducible data analyses. Its
features include: automatic discovery of tasks, a debug mode, repetition of a task with
different inputs, and many more.  Further, it is easily extensible with plugins. Plugins
are available for parallelization, LaTeX, Stata, R, Julia and more.
[(Documentation)](https://pytask-dev.readthedocs.io/en/stable/){:target="_blank"}

### econ-project-templates
With pytask as it's backbone, econ-project-templates aims to provide project templates
for economists that make it easy to produce reproducible research using one or more of
the most frequently used programming languages in economics (i.e., Python, Stata, R,
Julia).
[(Documentation)](https://econ-project-templates.readthedocs.io){:target="_blank"}

## <ins>*Archived Packages*</ins>

- [econsa](https://econsa.readthedocs.io){:target="_blank"}
- [robupy](https://robupy.readthedocs.io){:target="_blank"}
- [temfpy](https://temfpy.readthedocs.io){:target="_blank"}
