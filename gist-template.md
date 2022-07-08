# EMAIL MATCHING REGEX

## Summary

I will review the following regex: 

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The purpose of this regex to pick out any email address.


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

In this example the ANCHORS are ^ and $


### Quantifiers

In this exaple the QUANTIFIER is /d


### OR Operator

### Character Classes

This example uses 3 differnt groups to process the username, domain name, and domain extension. Please see below.

1. [a-z0-9_\.-]
2. [\da-z\.-]
3. [a-z\.]


### Greedy and Lazy Match

This example uses the Greedy matches + and {}

For {}, we re looking for 2-6 characters


## Author
Hey  👋🏽

I'm Joel, and I'm a novice Developer. I love leanring more about this worl and growng everyday.