# matlab-kg

Matlab KG library from two early papers on the knowledge gradient method:
- Frazier, Powell & Dayanik. "A knowledge-gradient policy for sequential information collection", SIAM Journal on Control and Optimization, 2008 (link)[https://doi.org/10.1137/070693424]
- Frazier, Powell & Dayanik. "The knowledge gradient policy for correlated normal beliefs", INFORMS Journal on Computing, 2009 (link)[https://doi.org/10.1287/ijoc.1080.0314]

The latter paper recently (2025) won the Test of Time Award from the INFORMS Journal on Computing.

The code is written in Matlab. There is a more modern implementation of the knowledge gradient method for Bayesian optimization available in [BoTorch](botorch.org) but the code may be of value for historical reasons and could be useful for future research. For example, [Ament et al. NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/419f72cbd568ad62183f8132a3605a2a-Paper-Conference.pdf) "Unexpected improvements to expected improvement for bayesian optimization" noticed that Bayesian optimization can be accelerated if carefully compute the logarithm of the acquisition function instead of its raw value. This same observation is found in the implementation of the correlated knowledge-gradient here.

The code was hosted on my web page for a long time (link)[https://people.orie.cornell.edu/pfrazier/src.html] but putting it on github feels like it will make the code more accessible.
