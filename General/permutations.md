**Challenge:** Permutations of a string's characters

**Description:** Write a function that receives a string and output every possible permutation of the characters in the string. The output has to be a string with each permutation being comma separated. Leading/trailing commas are allowed.

**Important Note:** As long as you have all the combinations with no duplicates, the order that they are presented in, in the output string does not matter.

**Warning:** The permutations is the factorial of the length of the string, so test with small strings!

**Examples:**

```text
input -> output

"" -> ""
"l" -> "l"
"lm" -> "lm,ml"
"lma" -> "lma,lam,mla,mal,alm,aml"
"lmao" -> "lmao,lmoa,lamo,laom,loma,loam,mlao,mloa,malo,maol,mola,moal,almo,alom,amlo,amol,aolm,aoml,olma,olam,omla,omal,oalm,oaml"
```
