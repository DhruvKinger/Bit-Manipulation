# Bit-Manipulation
Operations on Programs using Bitwise Logic

+ x ^ ( x & (x-1)) : Returns the rightmost 1 in binary representation of x.
+ x & (-x) : Returns the rightmost 1 in binary representation of x.
+ x & (x-1) will clear the lowest set bit of x.
+ x & ~(x-1) extracts the lowest set bit of x (all others are clear). Pretty patterns when applied to a linear sequence.
