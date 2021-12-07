# 1 - Alphabet Filter

Given a string consisting of only lowercase characters, create two methods that remove all the consonants or vowels from the given word. They must retain the original order of the characters in the returned strings. 

Example:

s = `"onomatopoeia"`

- The filter_vowels method removes all vowels from s and returns the string `"nmtp"`.
- The filter_consonants method removes all consonants from s and returns the string `"ooaooeia"`.


## Function Description

For a given definition of a class LetterFilter, complete its methods filter_vowels and filter_consonants. The class takes a string in the constructor and stores it to its s attribute. The method filter_vowels must return a new string with all vowels removed from it. Similarly, the method filter_consonants must return a new string with all consonants removed from it.

```python
class LetterFilter:
    def init(self, s):
        self.s = s

    def filter_vowels(self):
        # Enter your code here
        # Return a string
        return ""

    def filter_consonants(self):
        # Enter your code here
        # Return a string
        
        return ""
    
```

## Constraints
The string contains only lowercase letters in the range `ascii[a-z]` The string contains at least one vowel and at least one consonant.


