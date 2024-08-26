---
layout: page
title: General Purpose Tools
---

### optimagic
optimagic is a Python package for numerical optimization. It is a unified interface to
optimizers from SciPy, NlOpt and many other Python packages. optimagic’s `minimize`
function works just like SciPy’s, but you get more optimizers for free. On top you get
powerful diagnostic tools, parallel numerical derivatives and more. optimagic was
formerly called estimagic, because it also provides functionality to perform statistical
inference on estimated parameters. estimagic is now a subpackage of optimagic.
[(Documentation)](https://optimagic.readthedocs.io){:target="_blank"}

### pybaum
pybaum provides tools to work with pytrees which is a concept borrowed from JAX.
Pytree's refer to tree-like structures built out of container-like Python objects. We
use pybaum in several of our packages. One notable example is optimagic.
[(Documentation)](https://pybaum.readthedocs.io){:target="_blank"}

### dags
dags provides tools to create executable dags from interdependent functions.
[(Documentation)](https://dags.readthedocs.io){:target="_blank"}

