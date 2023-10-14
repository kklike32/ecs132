# Keenan Kalra
## October 9, 2023


## Problem 1

A to C is a 2 by 2 grid. Before doing calculations, we are first going 
to put a graph with the origin set on A so that point A is (0,0) and point
C is (2, 2). With the assumption that you can not go backwards, we can 
start doing calculations. First, we are going to assign each point a number
which corresponds to how many options there are to move forward from that
point. Afterwards, we can multiply the numbers together to get the total.
So point A has 2 options, the points right above and to the right has 2
each also. Following the straight horizontal and vertical lines, we can
see that the points (0,2) and (2,0) have 1 option each. Similarly, the points
(1,2) and (2,1) have 1 option each. The last point is (1,1) which has 2 options.
Multiplying all these numbers together will give you 8 total paths.    


## Problem 2

First, let us calculate the combinations of occupied and available blocks.
Since there are 5 blocks, the number of combinations is $$2^5 = 32$$, since 
each block can be either occupied or available.

A. Since the question asks us to calculate the probability of 1 to 4 blocks,
we can calculate the probability of 0 blocks and 5 blocks and subtract that
from 1. The probability of 0 blocks is $$1/32$$, since there is only one way to 
have 0 blocks occupied. The probability of 5 blocks is also $$1/32$$, since there
is only one way to have 5 blocks occupied. Therefore, the probability of 1 to
4 blocks is $$1 - 1/32 - 1/32 = 30/32 = 15/16$$.

B. Since the question asks us to calculate the probability of at least 1 block,
we can calculate the probability of 0 blocks and subtract that from 1. The 
probability of 0 blocks is $$1/32$$, since there is only one way to have 0 blocks
occupied. Therefore, the probability of at least 1 block is $$1 - 1/32 = 31/32$$.


## Problem 3

A. The probability of not choosing an 8 of red suit for the first three cards
are $$50/52 * 49/51 * 48/50$$. The probability of choosing a red 8 on the fourth
card is $2/49$. Multiplying all of these together is $$8/221$$ or 0.0362. which is 
probability you win the game on the fourth card drawn. 


## Problem 4

Let's assume that the total population is 100. That means 60 people watched
Barbie, 50 people watch Oppenheimer, and 30 people saw both. Given this 
information, we can calculate the amount of people that saw just one movie.
First, 30 people only watched Barbie and 20 people only watched Oppenheimer.
Given this information, 20 people did not watch any movie since 100 - 30 - 20 30.
Thus, 20 percent of people did not watch any movie.


## Problem 5

Both scenarios have the scenario where Mary is a professional musician.
This means, the only thing we have to compare is the animal welfare portion.
Even if the animal welfare portion is 99% likely, there is still a chance
that it does not happen. Thus, scenario A is more likely because it does not
have an added scenario.


I used the following website to help me: https://en.wikipedia.org/wiki/Conjunction_fallacy
