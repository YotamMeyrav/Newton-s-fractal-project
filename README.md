# Newton-s-fractal-project
A nuemeric method to estimate fractal dimensions of Newton's fractals

Newton's method is an algorythem to estimate the roots of a polynomial (including complex ones).
Newton's fractal is the result of applying this algorythem on a grid of complex points.

This project is the final project of my 11th grade CS class.
It is a live MATLAB code, that you can play with to learn about Newton's method and Newton's fractal.
I optimized the original Newton's method using standard techniques, that included: introducing an itteration cap and a tolerance for the converging point.

I also included two different versions of Newton's fractal: one that is colored based on coversion time, and one based on which root the point converged to.

Lastly, I used the "Box Counting Method" to estimate the fractal dimension: I divided the binary fractal into ever shrinking squares, calculated how many of them touch the fractal boundery, and used linear regression to calculate the dimension.
(the final answar is not always accurate. This will be fixed in the future)
