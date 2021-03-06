# Stochastic Processes: Data Analysis and Computer Simulation
This project includes the code I wrote to understand the Brownian motion and stochastic model in business world.

In the first three Python codes labeled as "Jupyter", I simulated the Brownian motion in both 2D and 3D. I then further examined the Brownian motion when an external force is added.

In the next five Pythons codes labeled as "Descriptions", I employed what I have learned in stochastic processes to solve the real business world problem. 

In the first section of these codes, in order to understand the return of stock price, I first calculate the normalized logarithmic return of Apple's stock for a time duration of 30,90,180 days, using the historical data from January 1st, 1989 to December 31st, 2016. Then I calculated the probability distribution function for the absolute normalized price returns and plotted the functions on a log-log scale together with a Gaussian distribution for comparison in order to understand the return distribution of Apple's stock price. 

In the next section of these codes, a stochastic dealer model with two agents(1 and 2 are trading stock with each other) is set in to understand the return of stock price. I calculated the logarithmic return together with the probability distribution function for the absolute normalized price returns to see how this changes under stochastic dealer model. 

In the last section of codes, a more realistic stochastic dealer model is set in which a memory term is added. The memory term is used to simulate both contrarians and trend-followers. I then calculated the logarithmic return together with the probability distribution function for the absolute normalized price returns to better understand the stochastic dealer model when memory term changes.
