**Challenge:** Generating the Fibonacci sequence, with a twist

**Description:** Write a function that will take in 1 argument that's a positive integer > 0, the amount of numbers to output from the sequence. The output will be comma separated numbers in a string (a leading/trailing comma is fine). The sequence will start off with `0,1,1,...`

**How the Sequence Works:** The standard Fibonacci sequence is n = n₋₁ + n₋₂ however the twist is to reverse the digits in the previous numbers to get n. so for example, if the previous 2 numbers are 8 and 13, the next number will be 39, since 8 is 8 in reverse but 13 is 31 in reverse. So 8 + 31 = 39.

**The First 20 Numbers:**
`0,1,1,2,3,5,8,13,39,124,514,836,1053,4139,12815,61135,104937,792517,1454698,9679838`

[OEIS link](http://oeis.org/A001129)
