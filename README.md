# Jennilees Tech Blog - Match an Email Regex

This tutorial is to explain the structure, components and purpose of regular expressions. A regular expression is sequence of characters that defines a pattern similar to a cipher. Like a regular expression and cipher uses numbers or symbols to represent different letters, much like a regular expression that uses the character sequence to define a pattern. 

## Summary

The regex that I chose is in matching an email. The regex syntax for matching an email is – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ . During this tutorial I will break down this regex to help understand what it is used for and what each portion fo the expression does.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors

The anchors for the regex to match and email are. Beginning ^ and the expression is closed with a $ sign. The purpose of the ^ and the $ is to enclose the expression and not allow for partial matches. In this instance , this regex is only looking for an exact match of an email based on the regex sequence that identifies the pattern associated with the email address.

### Quantifiers

Quantifiers indicate how many times a patter is matched. In this specific example: 

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 

There are few quantifiers here,

1. The (+) plus symbol - This is used to indicated that all patterns that preceed this symbol one or more times.
2. The ( {} ) the curly brackets - This sets a limit to the match. This is at the end of the expression with the numbers {2,6} this indicates that the preceeding string matched a min of 2 and a max of 6 times.


### Character Classes

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
The author of this tech blog is Jennilee Messenger. Jennilee currently works as a system administrator for IBM and Microsoft systems.She is new to coding.

https://github.com/JMess87

## Resources

https://learn.microsoft.com/en-us/dotnet/standard/base-types/