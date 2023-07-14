# Regex-Tutorial - Matching a Hex Value 

In this tutorial, I will be explaining how to match a Hex Value using Regex. I will be using the following regex: `^#?([a-f0-9]{6}|[a-f0-9]{3})$`. This regex will match a Hex Value with or without a `#` in front of it. It will also match a Hex Value that is either 3 or 6 characters long.

## Summary

This regex will match a Hex Value with or without a `#` in front of it. It will also match a Hex Value that is either 3 or 6 characters long. The regex will not match a Hex Value that is not 3 or 6 characters long. It will also not match a Hex Value that is not a valid Hex Value.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components



### Anchors
The `^` and `$` are anchors. The `^` anchor matches the beginning of the string. The `$` anchor matches the end of the string. In this regex, the `^` anchor matches the beginning of the string and the `$` anchor matches the end of the string. This means that the regex will only match a string that starts and ends with the regex.




### Quantifiers

The Quantifiers in this regex are `{6}` and `{3}`. The `{6}` quantifier matches the preceding token exactly 6 times. The `{3}` quantifier matches the preceding token exactly 3 times. In this regex, the `{6}` quantifier matches the preceding token exactly 6 times and the `{3}` quantifier matches the preceding token exactly 3 times. This means that the regex will only match a string that has 6 or 3 characters in it.

### OR Operator

The `|` is the OR operator. The `|` operator matches either the expression before or after the operator. In this regex, the `|` operator matches either the expression before or after the operator. This means that the regex will match a string that has either 3 or 6 characters in it.

### Character Classes

The character classes in this regex are `[a-f0-9]` and `[a-f0-9]`. The `[a-f0-9]` character class matches a single character in the list. In this regex, the `[a-f0-9]` character class matches a single character in the list. This means that the regex will match a string that has a character in the list in it.

### Flags

The flags in this regex are `i` and `g`. The `i` flag enables case-insensitive matching. The `g` flag enables "global" matching. In this regex, the `i` flag enables case-insensitive matching and the `g` flag enables "global" matching. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.




### Grouping and Capturing

The `()` are used for grouping and capturing. The `()` are used to group tokens together and capture the text matched by the tokens. In this regex, the `()` are used to group tokens together and capture the text matched by the tokens. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

### Bracket Expressions

The `[]` are used for bracket expressions. The `[]` are used to match a single character in the list. In this regex, the `[]` are used to match a single character in the list. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

### Greedy and Lazy Match

The `?` is used for a lazy match. The `?` is used to match the preceding token 0 or 1 times. In this regex, the `?` is used to match the preceding token 0 or 1 times. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

### Boundaries

The `\b` is used for a word boundary. The `\b` is used to match a word boundary. In this regex, the `\b` is used to match a word boundary. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

### Back-references

The `\1` is used for a back-reference. The `\1` is used to match the same text as most recently matched by the 1st capturing group. In this regex, the `\1` is used to match the same text as most recently matched by the 1st capturing group. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

### Look-ahead and Look-behind

The `(?=)` is used for a look-ahead. The `(?=)` is used to match a group after the main expression without including it in the result. In this regex, the `(?=)` is used to match a group after the main expression without including it in the result. This means that the regex will match a string that has a character in the list in it regardless of case. It also means that the regex will match all occurrences of the pattern in the string.

## Author

- Github: [@KevinJessie]  


