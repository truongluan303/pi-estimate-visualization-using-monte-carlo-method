# Estimate Pi using Monte Carlos method

This is a simple program that estimate the value of Pi using the Monte Carlo Method that is written totally in Python

![estimating-pi-monte-carlo-method](https://user-images.githubusercontent.com/83048295/116643492-0c96e880-a926-11eb-89eb-1fbbc41aca95.png)

From the image above, we can easily calculate the Area of the circle and the square

![equation](https://user-images.githubusercontent.com/83048295/161923210-8cbd2110-cfca-48c3-91b8-6f5366901c73.svg)

Therefore, we can simulate this situation by creating a big number of points that are randomly distributed on the image.
ALL of the points generated (BOTH blue & red) will represent A_square. 
The total number of points that are inside the circle (ONLY red) will represent A_circle
From there, we can do the calculation and estimate the number pi

I am using pygame for the graphical interface
The longer we run the program, the more accurate the output will be

This is how the output looks like:

https://user-images.githubusercontent.com/83048295/123563021-16429e00-d767-11eb-9e8e-6fa285c003be.mp4
