from math import factorial as fac
totalsum = 0
for x in range(3,1000000):
  digits = [int(d) for d in str(x)]
  factorialsum = 0
  for i in range(0, len(digits)):
    factorialsum += fac(digits[i])
  if (factorialsum == x):
    totalsum += x
print(totalsum)
