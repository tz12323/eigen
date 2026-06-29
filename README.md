**Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.**

For more information go to http://eigen.tuxfamily.org/ or https://libeigen.gitlab.io/docs/.

For ***pull request***, ***bug reports***, and ***feature requests***, go to https://gitlab.com/libeigen/eigen.

如果需要链接blas，需要手动在[build].cxxflag中添加["-DEIGEN_USE_BLAS","-lopenblas"]