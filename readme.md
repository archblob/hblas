# About

hOpenBLAS is a self contained full BLAS and LAPACK binding that provides the 
full BLAS and LAPACKE APIs in a simple, unopinionated, Haskell wrapper. 

This library is *NOT* meant to be used by end users, it is designed to be 
an unopinionated, simple, portable, easy to install BLAS/LAPACK substrate for higher level numerical
computing libraries to build upon. Morever, this library is strictly a wrapper,
and simply makes using the functionality of OpenBLAS more accessible.

hOpenBLAS requires having gfortran or another fortran compiler installed in 
order to build.

patches and other contributions welcome.