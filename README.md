# maxwells-demon
A simulation of Maxwell's Refrigerator which takes a binary string as input, and makes transitions between a hot reservoir and a cold reservoir as follows:
Rules:
1. The bits 0 and 1 are two energy states with equal energies.
2. The demon interacts with one bit at a time.
3. The demon can be either in contact with the upper(hot, energy Eh) reservoir(state u) or the lower(cold, Energy Ec, Eh > Ec) reservoir(state d).
4. The four possible states of the demon, hence, can be listed as 0u, 0d, 1u, 1d.
5. The demon can make intrinsic transitions between 0u and 0d or 1u and 1d, mediated by the hot reservoir.
6. The demon can make the transition 0d <-> 1u, while interacting with the cold reservoir. The demon changes the bit in this transition.
The last rule suggests that more the number of 0s in the input binary string, more the probability of transition from 0d to 1u, which is facilitated by the cold reservoir.
Hence the final thermodynamic entropy of the system decreases, depending on the input string.

However, the information entropy of the string increases with any such transition made, and the total entropy of the system is seen to abide by the second law of thermodynamics.

In this simulation, the transition rates are thought to be of the order which brings the probabilities of the demon being in hot and cold reservoirs close to equillibrium.
            
