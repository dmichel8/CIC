# CIC
A model calculating the force of many particles in a field using a wide variety of numerical methods

I will get around to fleshing out the math more about it, but this is a simulation of 32768 particles in a box, and I calculate all of their forces using the Cloud-In-Cell method.

I do this using the Kick-Deift-Kick Method for calculating the acceleration of particles for each timestep, and I solve the Poisson Equation using Fast Fourier Transforms by calcualting the force in Fourier Space. Like I said, this is all confusing, I'll flesh it out later, but this presentation is a good model: https://astro.uchicago.edu/~andrey/talks/PM/pm.pdf
