# regex-tutorial

This is a tutorial showing a brief breakdown of what Regex is, what it does, and it's significance in computer science.

## Summary

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ Regex which is short for regular expression is basically a set of special characters that when broken down, define a search pattern that developers use. This piece of code is read from left to right and it shows which characters can be used in email for instance.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)

### Anchors

^ and $ are the anchors. ^ usually is used at the start, whilst the $ is towards the end.

### Quantifiers

Quantifiers are characters that with hold the strings limits. + and {} would be the limiting quantifiers in the above example. Curly brackets are dependent on the amount of characters inside. for example {5,10} would mean that a requirement of more than 5 but less than 10 is required.

### Grouping Constructs

Parenthesis are used in regex as a subexpression. This allows the characters to be read easier as they are broken into different sections. The above example is broken into three sections which define a section of the email respectively.

### Bracket Expressions

The brackets indicate a character set. The above example has three. Each set designate a character set which in turn reference a specific part of the email.

### Character Classes

Character Escapes - A backslash is used to invalidate the characters within the square brackets.
Character Class - Any Characters that are found in the sequence of the RegEx

## Author

Afif Patel - https://github.com/Affiiiffff

Link - https://github.com/Affiiiffff/regex-tutorial
