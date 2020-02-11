# Kaggle_Santa_Competition
Want to help Santa with some non-convex optimisation problem?

Based on Kaggle competition description: Santa has to allocate 5000 families to one of 100 days when they can visit his workshop. The allocations to different days result in different cost to Santa, based on the family preferences, size and the daily occupancy rates. This results in a non linear optimisation problem - what is the minimal cost to Santa you can achieve?

The algorythm I created is based on Metropolois simmulated annealing algorythm, with 1 way and swap reallocations, presented on Reallocation picture.

The algorythm achieves decent results relativelly quickly. A 2 day simulation results in a circa 72k cost result, which puts it in the upper half of the solutions provided to the competition.

For more details please see the problem description at https://www.kaggle.com/c/santa-workshop-tour-2019/overview

