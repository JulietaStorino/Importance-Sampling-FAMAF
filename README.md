# Importance sampling
## Models and Simulation - FAMAF - UNC

### author
* Julieta Paola Storino

The report presents the Importance Sampling method to improve the efficiency in the simulation of rare events, optimizing the convergence of estimates compared to the traditional Monte Carlo method.

- In the first problem, the goal is to approximate the probability P(X > 3) where X is a standard normal variable. The traditional Monte Carlo method (direct sampling) is compared to the Importance Sampling method, using different importance distributions (N(4,1), exponential, and gamma) to improve the estimate.

- In the second problem, the probability that the time until the ninth call in a queue process (gamma model) is greater than or equal to 10 is calculated. Monte Carlo and Importance Sampling are implemented again, using a normal importance distribution N(11,1).

- The results are presented graphically, comparing both methods, and it is concluded that Importance Sampling significantly improves the efficiency and accuracy of the estimates. The proper choice of the importance distribution is key to the success of the method.
