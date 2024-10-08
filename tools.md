---
layout: page
title: General Purpose Tools
---

### optimagic
optimagic is a Python package for numerical optimization. It is a unified interface to
optimizers from SciPy, NlOpt, and many other Python packages. optimagic’s `minimize`
function works just like SciPy’s, but you get more optimizers for free. On top you get
powerful diagnostic tools, parallel numerical derivatives, and more. We started
developing optimagic under the name estimagic out of a need to robustify estimation of
nonlinear economic models, including statistical inference. That functionality is now a
subpackage of optimagic, which is still called estimagic. Optimagic now has its own
organization on Github: [optimagic-dev](https://github.com/optimagic-dev).
[(Documentation)](https://optimagic.readthedocs.io){:target="_blank"}

### pybaum
pybaum provides tools to work with pytrees which is a concept borrowed from JAX.
Pytrees refer to tree-like structures built out of container-like Python objects.
[(Documentation)](https://pybaum.readthedocs.io){:target="_blank"}

### dags
dags provides tools to create executable dags from interdependent functions.
[(Documentation)](https://dags.readthedocs.io){:target="_blank"}

