**Challenge:** Oscillating range

**Description:** You are to write a function that has 2 positive integer inputs, a and b. The output of this function will, for any a < b, in this case just be a. Then when a == b, the output will be b - 1, again (so this would be the output if a is either b - 1, or b). Then for a > b, the output numbers must go back down to 0 (where it started from) and 0 will be repeated twice, like b - 1. then the next section should then go back up to b - 1 and so on. If this is very confusing, I'm not really sure how to better express this in a better way, so please see the examples to clear anything up.

**Technical Details:** you can expect a to be an integer >= 0 and b to also be an integer >= 1.

**Examples:**

```text
These are the outputs of numbers 0 -> 19 (inclusive) as input a concatenated together:
input b -> first 20 numbers as output

1 -> 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0
2 -> 0, 1, 1, 0, 0, 1, 1, 0, 0, 1, 1, 0, 0, 1, 1, 0, 0, 1, 1, 0
3 -> 0, 1, 2, 2, 1, 0, 0, 1, 2, 2, 1, 0, 0, 1, 2, 2, 1, 0, 0, 1
4 -> 0, 1, 2, 3, 3, 2, 1, 0, 0, 1, 2, 3, 3, 2, 1, 0, 0, 1, 2, 3
5 -> 0, 1, 2, 3, 4, 4, 3, 2, 1, 0, 0, 1, 2, 3, 4, 4, 3, 2, 1, 0
6 -> 0, 1, 2, 3, 4, 5, 5, 4, 3, 2, 1, 0, 0, 1, 2, 3, 4, 5, 5, 4
7 -> 0, 1, 2, 3, 4, 5, 6, 6, 5, 4, 3, 2, 1, 0, 0, 1, 2, 3, 4, 5
8 -> 0, 1, 2, 3, 4, 5, 6, 7, 7, 6, 5, 4, 3, 2, 1, 0, 0, 1, 2, 3
9 -> 0, 1, 2, 3, 4, 5, 6, 7, 8, 8, 7, 6, 5, 4, 3, 2, 1, 0, 0, 1
10 -> 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 9, 8, 7, 6, 5, 4, 3, 2, 1, 0
```
