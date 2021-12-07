# 2 - Common Prefix Length

Given a string, split the string into two substrings at every possible point. The rightmost substring is a suffix. The beginning of the string is the prefix. Determine the lengths of the common prefix between each suffix and the original string. Sum and return the lengths of the common prefixes. Return an array where each element i is the sum for string `i`.

Example

Consider the only string in the array inputs = `['abcabcd']`. Each suffix is compared to the original string

| Remove to leave Suffix | Suffix    | Common Prefix | Length |
|------------------------|-----------|---------------|--------|
| ''                     | 'abcabcd' | 'abcabcd'     | 7      |
| 'a'                    | 'bcabcd'  | ''            | 0      |
| 'ab'                   | 'cabdc'   | ''            | 0      |
| 'abc'                  | 'abcd'    | 'abc'         | 3      |
| 'abca'                 | 'bcd'     | ''            | 0      |
| 'abcab'                | 'cd'      | ''            | 0      |
| 'abcabc'               | 'd'       | ''            | 0      |


```
The sum is 7 + 0 + 0 + 3 + 0 + 0 + 0 = 10.
```

## Function Description
Complete the function commonPrefix as presented below:

```python
# Complete the 'commonPrefix' function below.
# The function is expected to return an INTEGER_ARRAY.
# The function accepts STRING_ARRAY inputs as parameter.

def commonPrefix(inputs):
    # Write your code here
    return inputs

```

