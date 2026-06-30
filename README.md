# Initial Conditions

This repository has two folders. One folder contains initial conditions for CR3BP trajectories, while the other contains initial conditions for double pendulum trajectories.

For CR3BP trajectories, the nondimensional constant that describes the system is precisely $\mu=0.01215058560962404$. For the double pendulum trajectories, nondimensional ratios are $M=1$ and $L=1$.

Initial conditions were computed using 64 bit floating point arithmatic, and the possibility exists that representation as a string may yield floating point errors.

Family names are somewhat arbitrary. The suffix `-P#` denotes a period-n bifurcated family, while the suffix `B#` denotes a tangent (or hopf) bifurcation from the source family. Unnamed families are temporarily named `unnamed` followed by a number and possibly a note denoting what it is reminiscent of. Families with few members computed are marked with the suffix `few`. If a field is not present in a CSV file, that value is all zero.
