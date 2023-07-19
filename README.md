# Regex-Tutorial

## Intro paragraph 
Regex is useful for extracting information from text by searching patterns and then matches. Also can be used to validate user inputs.  

## Summary

This shows the matching email regex. this is the most common used regex, its matches all possible valid email address. 

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 


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
It doesnt match any charcters instead the match potions 
### Quantifiers
Its shows many instances of a character, class must be present in the input for a match to be found.
### OR Operator
The OR operator will add a logic that will except one or another. it uses this symbol (|). 
### Character Classes
 A set of characters enclosed within square brackets.
### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching. The m flag is used to specify that a multiline input string should be treated as multiple lines. A regular expression consists of a pattern and optional flags: g , i , m , u , s , y . 
### Grouping and Capturing
Capturing groups are a way to treat multiple characters as a single unit () the capturing is inside the ()
### Bracket Expressions
 Bracktet Expressions matchs a specific set of single characters, and may match a specific set of multi-character collating elements
### Greedy and Lazy Match
Greeady trys to find as many possible outcome and Lazy find minmal outcome 
### Boundaries
Forward slash / indicates boundaries of experessions.
### Back-references
Back references are Regex commands which refer to a previous part of the matched regular regex. 
### Look-ahead and Look-behind
Lookahead allows to add a condition for what follows, Lookbehind is similar, but it looks behind.
## Author
Tuji Abdulaya link to github: https://github.com/tujiabdulaya


