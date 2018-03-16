# kmer

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/kmer)](https://cran.r-project.org/package=kmer)
[![](http://cranlogs.r-pkg.org/badges/grand-total/kmer)](https://cran.r-project.org/package=kmer)
[![Build Status](https://travis-ci.org/shaunpwilkinson/kmer.svg?branch=master)](https://travis-ci.org/shaunpwilkinson/kmer)
[![codecov](https://codecov.io/github/shaunpwilkinson/kmer/branch/master/graphs/badge.svg)](https://codecov.io/github/shaunpwilkinson/kmer)
[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![ORCiD](https://img.shields.io/badge/ORCiD-0000--0002--7332--7931-brightgreen.svg)](http://orcid.org/0000-0002-7332-7931)

--------------------------------------------------------------------------------
K-mer counting and clustering for biological sequence analysis  

`kmer` is an R package for rapidly computing distance matrices and 
clustering large sequence datasets using fast alignment-free k-mer counting and 
recursive k-means partitioning. 


### Installation
To download `kmer` from CRAN and load the package, run
```R
install.packages("kmer")
library("kmer")
```
To download the development version from 
GitHub, first ensure a C/C++ compliler is available and the 
[devtools](https://github.com/hadley/devtools) R package is installed. 
Linux users will generally have a compiler installed by default; 
however Windows users may need to download 
[Rtools](https://cran.r-project.org/bin/windows/Rtools/) and Mac 
OSX users will need [Xcode](https://developer.apple.com/xcode) 
(note that these are not R packages). 
To download and install devtools, run 
```R
install.packages("devtools")
``` 
The `kmer` package is then installed and loaded by running 
```R
devtools::install_github("shaunpwilkinson/kmer") 
library("kmer")
```

### Help
An overview of the package and it's functions can be found by running
```R
?kmer
```

To view the tutorial, you can either run
```R
vignette("kmer-vignette")
```
or access it directly from [CRAN](https://CRAN.R-project.org/package=kmer).

If you experience a problem using this package please feel free to
raise it as an issue on [GitHub](http://github.com/shaunpwilkinson/kmer/issues).
Any feedback is appreciated.

### Acknowledgements
This software was developed at 
[Victoria University of Wellington](http://www.victoria.ac.nz/) 
with funding from a Rutherford Foundation Postdoctoral Research Fellowship 
award from the Royal Society of New Zealand.
