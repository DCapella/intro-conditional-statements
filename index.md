# Intro to Conditional Statements
#### [HackerRank](www.hackerrank.com)

## Problem

* If n is odd, print Weird
* If n is even and in the inclusive range of 2 to 5, print Not Weird
* If n is even and in the inclusive range of 6 to 20, print Weird
* If n is even and greater than 20, print Not Weird

## Thought Process

```
# (if n is odd) or n is even and in 6:20 inc. than weird
# (if n is even) and in 2:5 inc. or >20 than not weird
```

## Code It Out

#### Template

```
...
# Recieving given number and turning into int
n = int(fileinput.input()[0])

if () or (() and ()):
  print("Weird")
elif () and (() or ()):
  print("Not Weird")

# Comment out their code and pass because it's weird.
if __name__ == '__main__':
  pass
    # N = int(input())
```

#### Fill

```
...
if (n % 2 != 0) or ((n % 2 == 0) and (n in range(6,21)):
  print("Weird")
elif (n % 2 == 0) and ((n in range(2,6) or (n > 20)):
  print("Not Weird")
...
```

#### Final Code W/ Imports

```
#!/bin/python3

import math
import os
import random
import re
import sys
import fileinput

n = int(fileinput.input()[0])

if (n % 2 != 0) or ((n % 2 == 0) and (n in range(6,21))):
  print("Weird")
elif (n % 2 == 0) and ((n in range(2,6)) or (n > 20)):
  print("Not Weird")


if __name__ == '__main__':
  pass
    # N = int(input())
```

## Conclusion

As always, fun to code. Got more practice with fileinput and figuring out what to comment out in their code to make it easier for me.


