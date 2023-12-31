# Complex Numbers for FreePascal

**Author**: Paul Lipkowski

## About
I decided to write my own complex numbers mechanism, as FreePascal's built-in mechanism isn't sufficient enough for me.  

## Features

### As of now
- basic routines, type casting
- powers, square and cubic roots
- exponential and logarithmic functions
- trigonometric functions and their inverses
- hyperbolic and area functions
- MinusOneTo, ImagTo, MinusImagTo
- isZero, isNatural, isInteger, isReal, isNotReal, isImaginary, isComplex boolean functions
- ComplexNumPolar (initializing a complex number with polar coords)
- gamma, gammaln functions
- lower and upper incomplete gamma functions
- erf, erfc, erfi functions
- beta, incomplete beta, regularized incomplete beta functions
- E_n function (exponential integral) with branches
- Ei function
- li (logarithm integral)
- sinc function
- Si, Ci functions (sine integral, cosine integral)
- Newton symbol `(z,n)`
- Dirichlet eta function
- Riemann's zeta function

### Todo list
- round
- Lambert's W function with branches
- inifinities
- Fresnel integrals



## References

1. [W.H. Press, S.A. Teukolsky, W.T. Vetterling, B.P. Flannery; 'Numerical Recipes. The Art of Scientific Computing. Third Edition'; Cambridge University Press (2007)](http://numerical.recipes/book.html)
2. [L. Lorentzen, H. Waadeland; 'Continued fractions with applications'; North-Holland Publishing Co. (1992)](https://link.springer.com/content/pdf/bbm:978-94-91216-37-4/1)
3. [D. Harvey; 'A multimodular algorithm for computing Bernoulli numbers'; Math. Comput., 79 (272): 2361–2370 (2010)](https://www.ams.org/journals/mcom/2010-79-272/S0025-5718-2010-02367-1/)