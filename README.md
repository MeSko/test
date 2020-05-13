# r-conda

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MeSko/test/master?urlpath=rstudio)

> R and RStudio in repo2docker without waiting for packages to compile!

Jupyter+R: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/MeSko/test/master?filepath=test.ipynb)

RStudio: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/MeSko/test/master?urlpath=rstudio)

Binder supports using R and RStudio, with libraries pinned to a specific versions.

Install R itself and your required R packages via conda packages. Installing conda packages is faster than
installing CRAN packages. This is because CRAN packages need compiling during the install process and conda
packages do not.


Both [RStudio](https://www.rstudio.com/) and [IRKernel](https://irkernel.github.io/)
are installed by default, so you can use either the Jupyter notebook interface or
the RStudio interface.
