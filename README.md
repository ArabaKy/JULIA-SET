# JULIA-SET
# Visualization of Julia Sets
Julia Set is a fractal that is defined by the behavior of a function that operates on input complex numbers. A fractal, for that matter, is a mathematically defined object that has similarity and symmetry on different scales. To create a Julia set, a function, for instance,  $f(z)=z^2+c$,
is applied iteratively to a set of points in the complex plane. The $'c'$ in this function is constant while the $'z'$ changes with each iteration. The Julia set represents the set of inputs whose outputs turn towards infinity.

# Procedure
Use %pylab inline to import numpy and matplotlib for use

and then create our complex region using linspace.
Use the meshgrid function to help with the visualization. The meshgrid is used as a canvas on which the visualization is done.

And then declare variable z as z to be equal to $x+yi$, where x is the real part and y, the imaginary part, obtained from the meshgrid.

Declare the golden ratio as gld and equate it to the golden ratio value, thus $\frac{1+\sqrt{5}}{2}$
​
 
Declare  variable c as c being equal to 1− gld for the first case, and different values for the other cases.

Create a variable n to define the number of iterations to take.

Declare a variable l to be an array of zeros taking the shape of z.

Perform the iterative function of $z=z^2+c$ for n iterations, in the first four cases, showing the points of convergence after each iteration.

Use the imshow function to show where the convergence occurred after each and every iteration, thus visualizing the Julia Set.

