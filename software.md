---
layout: page
title: Software
---

We maintain several software packages in support of our research and educational
activities. Some of our projects are of methodological nature or aim to facilitate
research itself and make it more reproducible. These will be found in section
[Tools](#Tools). In our other projects we use these tools to implement economic models.
These will be found in the section [Economic Modelling Packages](#economic-modelling-packages).

## <ins>*Tools*</ins>

``econ-project-templates`` aims to provide project templates for economists that make it
easy to produce reproducible research using one or more of the most frequently used
programming languages in economics (i.e., Python, Stata, R, Julia).
{:.sansserif}
&ensp;**Documentation:** [econ-project-templates.readthedocs.io](https://econ-project-templates.readthedocs.io){:target="_blank"}

``estimagic`` is a Python package that helps to build high-quality and user friendly
implementations of (structural) econometric models. It is designed with large structural
models in mind. However, it is also useful for any other estimator that numerically
minimizes or maximizes a criterion function. Examples include maximum likelihood,
generalized method of moments, method of simulated moments and indirect inference.

{:.sansserif}
&ensp;**Documentation:** [estimagic.readthedocs.io](https://estimagic.readthedocs.io){:target="_blank"}

``pybaum`` provides tools to work with pytrees which is a concept burrowed from JAX.
Pytree's refer to tree-like structures built out of container-like Python objects. We
use pybaum in several of our packages. One notable example is estimagic.

{:.sansserif}
&ensp;**Documentation:** [pybaum.readthedocs.io](https://pybaum.readthedocs.io){:target="_blank"}

``dags`` provides tools to create executable dags from interdependent functions.

{:.sansserif}
&ensp;**Documentation:** [dags.readthedocs.io](https://dags.readthedocs.io){:target="_blank"}

``econsieve`` is a collection of nonlinear Bayesian filters, in particular for high
dimensional models. The filters are implemented in python. It provides the
Transposed-Ensemble Kalman Filter (TEnKF) for state and likelihood inference, and the
Nonlinear Path-Adjusting Smoother (NPAS) for exact smoothed states.

{:.sansserif}
&ensp;**Documentation:** [econsieve.readthedocs.io](https://econsieve.readthedocs.io){:target="_blank"}


<!-- New section starting here -->


## <ins>*Economic Modelling Packages*</ins>

``respy`` is an open-source framework written in Python for the simulation and
estimation of some finite-horizon discrete choice dynamic programming models. The group
of models which can be currently represented in `respy` are called Eckstein–Keane–Wolpin
models.

{:.sansserif}
&ensp;**Documentation:** [respy.readthedocs.io](https://respy.readthedocs.io){:target="_blank"}


``pydsge`` is a Python package that allows to simulate, filter, and estimate DSGE models
with occassionaly binding constraints. As such, it allows to conduct full-blown Bayesian
estimations (including Bayesian filtering) of macroeconomic models featuring an
endogenous zero lower bound on nominal interest rates.

{:.sansserif}
&ensp;**Documentation:** [pydsge.readthedocs.io](https://pydsge.readthedocs.io){:target="_blank"}


``skillmodels`` a Python implementation of estimators for skill formation models. 

{:.sansserif}
&ensp;**Documentation:** [skillmodels.readthedocs.io](https://skillmodels.readthedocs.io){:target="_blank"}


``ruspy`` is an open-source package for the simulation and estimation of a prototypical
infinite-horizon dynamic discrete choice model based on [Rust
(1987)](https://doi.org/10.2307/1911259){:target="_blank"}.

{:.sansserif}
&ensp;**Documentation:** [ruspy.readthedocs.io](https://ruspy.readthedocs.io){:target="_blank"}


``grmpy`` is an open-source Python package for the simulation and estimation of the
generalized Roy model. It serves as a teaching tool to promote the conceptual framework
of the generalized Roy model, illustrate a variety of issues in the econometrics of
policy evaluation, and showcases basic software engineering practices.

{:.sansserif}
&ensp;**Documentation:** [grmpy.readthedocs.io](https://grmpy.readthedocs.io){:target="_blank"}


<!-- New section starting here -->


## <ins>*Other Notable Packages*</ins>

- [``econsa``](https://econsa.readthedocs.io){:target="_blank"}
- [``robupy``](https://robupy.readthedocs.io){:target="_blank"}