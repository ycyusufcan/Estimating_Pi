# Estimating_Pi
Estimating Pi with Monte Carlo Method
One method to estimate the value of π (3.141592…) is by using a Monte Carlo method. This methods consists of drawing on a canvas a square with an inner circle.
We then generate a large number of random points within the square and count how many fall in the enclosed circle.

The area of the circle is πr^2,
The area of the square is width^2 = (2r)^2 = 4r^2.

If we divide the area of the circle, by the area of the square we get π/4.

The same ratio can be used between the number of points within the square and the number of points within the circle.

Hence we can use the following formula to estimate Pi:

π ≈ 4 x (number of points in the circle / total number of points)
