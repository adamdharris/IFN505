# String Matching

## Horspool Algorithm

`No. Shifts = (n - m + 1)`  

Where:  
* m = pattern  
* n = text

**Efficiency** is `O(nm)`
* If pattern character `a` mismatches with text character `b`, if `b` does not appear anywhere in the pattern then shift the patter completely past `b`.  Otherwise, shift the pattern to align `b` with the last occurence of `b` in the pattern. 

[Horspool Algorithm - Example](https://www.youtube.com/watch?v=ZMQWjslBlbU)
