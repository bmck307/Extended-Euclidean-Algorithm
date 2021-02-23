# Extended-Euclidean-Algorithm
This exists because I am too lazy to do it every time for class

This is some example of how the output is supposed to look:

343 = 128 * 2 + 87|||[ 1 , 0] +  -2[0 , 1] = [1 , -2]

128 = 87 * 1 + 41|||[ 0 , 1] +  -1[1 , -2] = [-1 , 3]

87 = 41 * 2 + 5|||[ 1 , -2] +  -2[-1 , 3] = [3 , -8]

41 = 5 * 8 + 1|||[ -1 , 3] +  -8[3 , -8] = [-25 , 67]

5 = 1 * 5 + 0

HCF(343,128) = 343 * -25 + 128 * 67 = 1

This represents the GCD of 343 and 128.
