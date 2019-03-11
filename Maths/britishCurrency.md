**Challenge:** Converting a number to British currency.

**Description:** To write a function that will take in 1 argument. This argument is the number to convert to British currency. The output will be a string with comma separated numbers corresponding to the index (more on this below) of the coin/note that goes into the original number. You are expected to use the highest valued notes/coins that make up the original number so you can't just dump a series of 1p coins in the output.

**More on the notes/coins indexes:** This is a list of all possible notes/coins in descending order with index `0` being the £50 note all the way down to index `11` being the 1p coin (£0.01). Full list below:

```text
0: £50
1: £20
2: £10
3: £5
4: £2
5: £1
6: £0.5
7: £0.2
8: £0.1
9: £0.05
10: £0.02
11: £0.01
```

**Technical stuff:** You can expect the number given to this function to have at max 2 decimal places and will always be > 0. In your output, you may have a trailing/leading comma.

**Examples:**

```text
Input -> output

27 -> '1,3,4'
5.76 -> '3,6,7,9,11'
12.62 -> '2,4,6,8,10'
88.88 -> '0,1,2,3,4,5,6,7,8,9,10,11'
1005.23 -> '0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,3,7,10,11'
```
