# for_if_break
basic_practice
import sympy

for i in range(2, 24):
    if sympy.ntheory.primetest.isprime(i):   # call isprime directly
        print(i)
