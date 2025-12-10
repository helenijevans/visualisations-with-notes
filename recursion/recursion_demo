"""
TASK:
Write a recursive function to calculate a to the power of b
(e.g. if a = 2, and b=3, the result = 8 (2^3))

STEPS:
- Find the base cases + pattern
- Create the function
- Base cases first (using if statements)
- Recursive case (the code version of the pattern)
"""

# FIND BASE CASES
# Anything to the power of 0 is 1 (therefore if b = 0, result is 1)
# Anything to the power of 1 is itself (therefore if b = 1, return a)
# Zero multiplied by anything is zero (therefore if a = 0, return 0)

# FIND THE PATTERN
# 2^3 = 2^2 * 2
# 2^2 = 2^1 * 2
# ==> a^b = a^(b-1) * a

def power(a, b):
    # base case
    if b == 0:
        return 1
    elif b == 1:
        return a
    elif a == 0:
        return 0
    # recursive case
    return a * power(a, b - 1)

print(power(2,3))
