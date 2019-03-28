# Intro To Conditional Statements

Print out weird or not based on a couple of conditional factors.

# Notice
I would try to solve this first before looking at this if I were you.

# Code

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

# Acknowledgements
* [HackerRank](https://www.hackerrank.com/)
