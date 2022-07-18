# -Monte-Carlo-Simulation-Discrete-Event-Simulation-of-Queuing-Model-in-AnyLogic-Modeling-Covid-19
Implementation of Monte Carlo Simulation, Discrete Event Simulation of Queuing Model in AnyLogic and Modeling Covid-19


CS421 - Computer Modeling and Simulation
Assignment 3
Due Date: 24th June, 2022
Task 1: Monte Carlo Simulation
For each of the given questions from 1 to 3, do parts a-d.
a. In the case of 2D problems, plot the function, f.
b. Using the Monte Carlo technique, define a function with a parameter for the number of darts
that returns an estimate of the indicated value.
c. Define a function that calls the function from Part b 1000 times and returns the mean and
standard deviation of the results.
d. Using any computational tool or programming language, calculate the answer with
integration.
1. The area between the curve for f (x) = √(cos
2
(x)+ 1) and the x-axis from x = 0 to x = 2
2. The area between the curve for f(x) = x
2 and the x-axis from x = 2 to x = 3
3. An estimate of ∫2
3sin(x
2
)dx. Note that the function is not entirely above or entirely below the
x-axis, so we must adjust the algorithm studied in the class to estimate the integral. Recall that
where a function is negative (below the x-axis), its integral is the negative of the area between
the curve and the x-axis.
Task 2: Discrete Event Simulation of Queuing Model in AnyLogic
Make a simulation of a production line. The production line is pretty straight forward, 5 machines
in line and all the products go through every machine. Three products are made and each
product takes different time in different stages. Machines can take any amount of products so
they can be easily represented with a delay.
The following table portrays the amount of time (in seconds) that each product takes to be
processed in each machine.
Products enter the system in order. Every 5 seconds exactly 1 product will be generated. The
first product to enter the system is product 1, followed by product 2, and followed by product 3.
After product 3, product 1 enters again and so on (1-2-3-1-2-3-1-2-3… etc).
Consider the following assumptions:
- Machines do not need any setting time between different products.
- Delays are fixed.
- No queues at any point.
Generate an event that will occur only once after 1 hour with this action: finishSimulation();
This will stop the simulation.
Generate a bar chart to discover the results. Each bar will show the amount of products in each
machine. You can find the amount of products in a delay using delay.size();
You will get the following result if you did it correctly:
Note: Make the model using Discrete events only. You are not allowed to use any agent
populations, only agent types.
Task 3: Modeling Covid-19 in AnyLogic
Implement the Lipsitch Model for Covid-19 in AnyLogic tool. The values of parameters should
be set based on some search on the Internet.

[CMS_Assignment 3.pdf](https://github.com/ali-haidir/-Monte-Carlo-Simulation-Discrete-Event-Simulation-of-Queuing-Model-in-AnyLogic-Modeling-Covid-19/files/9131422/CMS_Assignment.3.pdf)

