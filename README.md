## Groebner

**Organization of this Repository**

Each axis of the tensor of coefficients of a multivariate polynomial are ordered from smallest degree to largest degree. For example, the polynomial $x^2y^2 + 2x^2y + 3xy -5 = 0$ is represented by the matrix

x^0, x^

**Solving a System of Polynomial Equations**

Groebner bases can be used to find solutions to a system of polynomial equations.
Unfortunately, computing Groebner bases is known to be unstable due to floating point error propagation.
Polynomials in the power basis can be represented by a summation of Chebyshev polynomials, which are good for stable computation.
Converting the polynomials to Chebyshev polynomials reduces the error significantly.
Here's an example using the code from this repository:

*Example*

Developed at Brigham Young University 2016-2017
