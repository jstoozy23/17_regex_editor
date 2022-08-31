# * Matching an Email: 

This is a Readme file describing the elements of an Email matching the following: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Regular expressions are a series of special characters, numbers and letters that define the entry pattern for required field. 

## Summary

Matching an Email is one of the most common uses of regular expression. It sets up the pattern of special characters, numbers and letters that are both allowed and required in certain places of the email. This ensures that what is being entered, is at least following the required format for an email. 

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

To validate that the input was formatted correctly we use regular expression. the forward slash "/" is the beginning of the expression
The caret anchor "^" matches the beginning of the text.
The dollar "$" anchor matches the end of the text.

### Quantifiers

The "+" is used in this email expression to define the times you match the elements listed before it. If referencing the email expression given, the "([a-z0-9_\._])" are elements that are allowed and can be used more that once. 

### OR Operator

Allows the validation of two character types. Example a "B" can be validated as b|B as "B"

### Character Classes

This is designating the type of character that is permitted for this input. An example of this would be "digit" which would refer to the numbers 0-9

### Flags

A flag is a way search and replace text. This will replace the data in the string and validate it.

### Grouping and Capturing

Groupins are formed for the username, domain and top level domain. The parentheses on each end of a string indicates that is a grouping and includes the acceptible validation parameters.

### Bracket Expressions

"([a-z0-9_\._])" in this expression, a-z, 0-9,_\.- are all listed inside the expression as acceptable input

### Greedy and Lazy Match

Quantifiers are lazy by default

## Author

Jeff Stutzman