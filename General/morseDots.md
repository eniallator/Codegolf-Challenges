**Challenge:** Morse Dots

**Description:** You are to write a function that will receive a string input, only consisting of either [a-z] or [A-Z] (your choice), however it cannot have characters in [a-z] and [A-Z]. So `AAA` and `aaa` are both fine (depending on whether you accept lowercase or uppercase), but `aAa` is not. The function is to then output a **truthy** value if the morse code translation of the string input consists of more dots than dashes, and a **falsy** value otherwise.

**Morse Code Reference:**

![Morse code reference](https://i.imgur.com/R9LESFK.png)

**Examples:**

```text
input -> output

S -> truthy
K -> falsy
HELLO -> truthy
CODE -> falsy
```

<sub>**Challenge From:** [codegolf.stackexchange](https://codegolf.stackexchange.com/questions/181318/they-call-me-inspector-morse#181318)</sub>
