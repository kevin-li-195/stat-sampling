stochastic
=====

Version 0.1.0

Haskell library for monadic composition of probabilistic functions 
and construction of stochastic processes.

Resulting computations can then be run to generate data.

Blog [post](http://kevinl.io/posts/2016-08-24-sampling-monad.html) has some along with examples.

TODO
-----
- See where performance can be improved.
- Check if compiling with -O2 really gives a performance improvement.
- Upload charts with profiled tests and memory usage.
- Add more usage information to README.
- Implement learning for generative models.
- Extend StochProcess to allow for ARCH models.
- Separate StochProcess and Sample modules.
- See if building on top of mwc-random is better than
carrying around StdGens.
- Reduce composed probability distributions that have closed-form
solutions before sampling.
