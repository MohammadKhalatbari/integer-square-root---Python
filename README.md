Algorithm development: calculating βinteger square rootβ.
Let us say that for an integer π, the integer square root of π is the integer π such that the difference
πππ (π β π2)
is the smallest possible. The solution can be found by the following two steps:
1. Ask the user for a number.
2. Make a loop that searches for the integer that, when raised to the power of 2, is closest to the number given by the user.
For example, the integer square root of 7 is 3.
β’ 2 ** 2 = 4 β the distance is |7-4| = 3
β’ 3 ** 2 = 9 β the distance is |7-9| = 2.
Note that integer square root is always unique, that is, for an π, there cannot be two π:s which are equally far from π2.