# String Matching

## Horspool Algorithm

**Efficiency** is `O(nm)`
* If pattern character `a` mismatches with text character `b`, if `b` does not appear anywhere in the pattern then shift the patter completely past `b`.  Otherwise, shift the pattern to align `b` with the last occurence of `b` in the pattern. 

[Horspool Algorithm - Example](https://www.youtube.com/watch?v=ZMQWjslBlbU)

[Boyer-Moore Algorithm - Part 1](https://www.youtube.com/watch?v=4Xyhb72LCX4)
[Boyer-Moore Algorithm - Part 2](https://www.youtube.com/watch?v=Wj606N0IAsw)
