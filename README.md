# CEADOP
A dataset of CEADOP and CEADTOP instances

## CEADOP Format:
The instances are formatted as follows:

n integer
tmax float
x y score theta1 phi1 ... thetaN phiN (repeating for each point in the dataset)

We use the convention of Chao that the first and final point are the source and sink positions respectively.

## CEADTOP Format
Same as CEADOP, except a line containing the number of agents "m" is inserted on the second line.
