# Regex Components Tutorial

For this challenge, I will be walking you through how to use regex and its different components. 

## Summary
In this tutorial, we will go over the different components of regex and how to use them to create different words, phrases, a sequence of numbers and or characters.

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
Anchors are unique in that they match a position within a string, not a character. Anchors include, but aren't limited to: beginning (^), end ($), word boundary (\b), and not word boundary (\B)

### Quantifiers
Quantifiers indicate that the preceding token must be matched a certain number of times. By default, quantifiers are greedy, and will match as many characters as possible. Quantifiers include but aren't limited to: plus (+), star (*), quantifier {1,3}, optional (?), lazy (?), and alternation (|)


### OR Operator
The OR Operator is used to match one of multiple patterns. For example, "this OR that" would be separated with "|" making it "this|that."
### Character Classes
Character classes match a character from a specific set. There are a number of predefined character classes and you can also define your own sets. Character classes include, but are not limited to: chracter sets [ABC], negated sets [^ABC], range [A-Z], dot (.), match any [\s\S], word (\w), not word (\W), digit (\d), not digit (\D), whitespace (\s), not whitespace (\S), unicode category (\p{L}), not unicode category (\P{L}), unicode script (\p{Han}), and not unicode script (\P{Han}).

### Flags
Expression flags change how the expression is interpreted. Flags follow the closing forward slash of the expression (ex. /.+/igm ). Flags include, but are not limited to: ignore case (i), global search (g), multiline (m), unicode (u), sticky (y), and dotall (s).

### Grouping and Capturing
Groups multiple tokens together and creates a capture group for extracting a substring or using a backreference.
### Bracket Expressions
 A bracket expression is an expression closed in square brackets, "[]." Bracket expressions match a specific set of single characters as well as multi-character collating elements, based on non-empty list expressions in brackets.
### Greedy and Lazy Match
Greedy matches mean to match the longest possible string, eg. "h.+1" equals the "hell" in "hello," while lazy matches, on the other hand means to match the shortest possible string, eg. "h.+?1" equals "hel."
### Boundaries
 \b is an anchor like the "^" and "$". It matches at a position that is called a “word boundary”. This match is zero-length.
### Back-references
Backreferences match the same text as previously matched by a capturing group, allowing you to reuse the name of the tag for the closing tag. For example, ([a-c])x\1x\1 equals "axaxa."
### Look-ahead and Look-behind
Lookaround lets you match a group before (lookbehind) or after (lookahead) your main pattern without including it in the result. Lookarounds include, but are not limited to: positive lookahead (?=ABC), negative lookahead(?!ABC), positive lookbehind (?<=ABC), or negative lookbehind (?<!ABC).
## Author
Shanisse Wilson
Github: https://github.com/shanissewilson
