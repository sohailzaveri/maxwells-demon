# maxwells-demon
A simulation of Maxwell's Refrigerator(a solvable model of Maxwell's Demon) which takes a binary string as input and makes transitions between a hot and a cold reservoir according to the rules as follows.

Rules:
1. The bits 0 and 1 are two energy states with equal energies.
2. The demon interacts with one bit at a time.
3. The demon can be either in contact with the upper(hot, Temperature Th) reservoir(state u) or the lower(cold, Temperature Tc, Eh > Ec) reservoir(state d).
4. The four possible states of the system, hence, can be listed as 0u, 0d, 1u, 1d.
5. The demon can make intrinsic transitions 0u<->0d or 1u<->1d, mediated by the hot reservoir.
6. The demon can make the transition 0d <-> 1u, while interacting with the cold reservoir. The demon changes the bit in this transition.

More the number of 0s in the input string, higher the probability of demon using energy from cold reservoir and making the transition 0d<->1u. Hence, it is possible that for a sufficient number of 0s in the input string, the net energy transfer is from the cold reservoir to the hot reservoir. This suggests that the net thermodynamic entropy of the system is negative. 

However, after taking infromation entropy of the system into account, we reach the expected results, hence validating the second law of thermodynamics.

In this project, we simulate Maxwell's refrigerator and observe the final and initial information enropies of the system. We further compare it with the thermodynamic entropy and reach at the conclusion that the net negative change in the thermodynamic entropy is compensated by the increase in the information entropy.
            
