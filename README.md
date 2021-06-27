# Pi_Estimate Explaination

This is a simple program that estimate the value of Pi using the Monte Carlo Method that is written totally in Python

![estimating-pi-monte-carlo-method](https://user-images.githubusercontent.com/83048295/116643492-0c96e880-a926-11eb-89eb-1fbbc41aca95.png)

From the image above, we can easily calculate the Area of the circle and the square

A_circle = pi * (r^2)

A_square = (2r)^2 = 4 * (r^2)

=> A_circle / A_square = pi / 4

=> pi = 4 * A_circle / A_square

Therefore, we can simulate this situation by creating a big number of points that are randomly distributed on the image.
ALL of the points generated (BOTH blue & red) will represent A_square. 
The total number of points that are inside the circle (ONLY red) will represent A_circle
From there, we can do the calculation and estimate the number pi

I am using pygame for the graphical interface

This is how the output looks like:
Uploading Estimate Pi 2021-06-27 16-35-55.mp4…
