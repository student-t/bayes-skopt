=======
History
=======

0.3.3 (2020-03-16)
------------------

* Fix error occuring when an unknown argument was passed to ``Optimizer``.

0.3.0 (2020-03-12)
------------------

* Add predictive variance reduction search criterion. This is the new default
  acquisition function.
* Implement ``BayesSearchCV`` for use with scikit-learn estimators and
  pipelines. This is an easy to use drop-in replacement for GridSearchCV or
  RandomSearchCV. It is implemented as a wrapper around skopt.BayesSearchCV.
* Determine default kernels and priors to use, if the user provides none.
* Add example notebooks on how to use the library.
* Add API documentation of the library.


0.2.0 (2020-03-01)
------------------

* Allow user to pass a vector of noise variances to ``tell``, ``fit`` and ``sample``.
  This can be used to warm start the optimization process.

0.1.2 (2020-02-16)
------------------

* Fix the ``tell`` method of the optimizer not updating ``_n_initial_points`` correctly,
  when using replace.

0.1.0 (2020-02-01)
------------------

* First release on PyPI.
