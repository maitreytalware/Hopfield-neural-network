# Hopfield neural network
 
 A Hopfield network is a form of recurrent artificial neural network popularized by John Hopfield in 1982, but described earlier by Little in 1974.Hopfield nets serve as content-addressable ("associative") memory systems with binary threshold nodes. They are guaranteed to converge to a local minimum and, therefore, may converge to a false pattern (wrong local minimum) rather than the stored pattern (expected local minimum). Hopfield networks also provide a model for understanding human memory 
 
 -Wiki
 

# 1. Aim: 
**To build a discrete Hopfield neural network to store the following two patterns: (1, 0, 1, 1) and (1, 1, 1, 0).**



# 2. Transfer Function used:
<img src="transfer function.png">

# 3. Questions to be Answered
1. What is the weight matrix according to Hebbian learning? Make sure you zero out the self connections.

2. What is the total number of states (vectors) in the configuration space? 

3. For each vector in the configuration space, feed it into the neural network, and find the vector that it converges to. Always cycle through the neurons in the following order: X1, X4, X2, and X3, until convergence. 

4. For each of the two stored vectors, find the size of the basin of attraction ( the number of states that converge to the stored pattern). 

5. How many spurious patterns are there? For each such pattern, give the size of the basin of attraction. 