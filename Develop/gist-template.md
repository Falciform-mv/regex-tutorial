# REGEX Tutorial

Dive into the world of Regex and learn how they work. In this tutorial we will break down the individual parts to better understand Regex.

## Summary

Password Validation
/^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[a-zA-Z]).{8,}$/gm

ensures:
- at least 8 characters
- must contain at least 1 uppercase letter, 1 lowercase letter, and 1 number
- Can contain special characters



## Table of Contents


- [Quantifiers](#quantifiers)

- [Character Classes](#character-classes)

- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components


### Quantifiers
* {8,}


### Character Classes
a-z range, matches a character in the range a to z. case sensitive


### Look-ahead and Look-behind
Matches a group after the main expression
(?=.*\d) (?=.*[a-z]) (?=.*[A-Z]) (?=.*[a-zA-Z])
## Author


