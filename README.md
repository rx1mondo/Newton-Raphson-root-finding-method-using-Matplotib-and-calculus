# Newton-Raphson Root Finding Visualizer

A Python tool I built to visualize how the Newton-Raphson method approximates roots of non-linear equations step-by-step using numerical calculus.

## Why I Built This
In A-Level Pure Maths, we learn the Newton-Raphson formula to find where $f(x) = 0$:

$$x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}$$

Doing these iterations by hand on a calculator takes time and doesn't give a clear picture of why the method works. I wrote this script to automate the calculation loop and plot the tangent lines visually so you can watch the guesses "zoom in" on the actual root.

## Features
- **Iterative Solver:** Runs the Newton-Raphson loop until the difference between steps is under target tolerance ($\Delta x < 10^{-6}$).
- **Step-by-Step Visualization:** Plots the main function curve alongside each tangent line segment and vertical drop line using `Matplotlib`.
- **Dynamic Color Gradient:** Uses a color map so each iteration step is visually distinct.

## Built With
- Python 3
- NumPy
- Matplotlib
