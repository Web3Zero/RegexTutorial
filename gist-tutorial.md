# Regex Tutorial

Regular expressions (regex) are powerful tools for working with text data. They allow us to define patterns and search for specific strings within a larger body of text. In this tutorial, we will dive into the fascinating world of regular expressions by exploring a specific regex that is commonly used for validating email addresses.

Email addresses are an essential form of communication today, and being able to validate and extract them accurately can be incredibly valuable. By using a well-crafted regex, we can ensure that the email addresses we work with meet the necessary formatting requirements.

In this tutorial, we will dissect a regex that matches email addresses and break down each component to understand its function. We will explore anchors, quantifiers, character classes, grouping, and other essential elements of regex syntax. By the end of this tutorial, you will have a solid understanding of how the regex works and how to utilize it effectively.

## Summary

In this tutorial, we will explore a regular expression (regex) that matches email addresses. Email addresses have a specific format, and using a regex can help validate and extract them from text. The regex we will be examining is:

/^[\w.-]+@[\w.-]+\.[\w.-]+$/

We will break down each component of this regex and explain its function in order to understand how it works.

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
Anchors are symbols that represent the position of the regex match within the text. The ^ symbol at the beginning of our regex represents the start of the line, and the $ symbol at the end represents the end of the line. Together, they ensure that the entire string is matched from start to finish.

### Quantifiers
Quantifiers specify how many times a certain element should occur. In our regex, the + symbol is a quantifier that matches one or more occurrences of the preceding element. For example, [\w.-]+ matches one or more word characters, dots, or hyphens.

### OR Operator
The OR operator, represented by the | symbol, allows us to provide alternative matches for a specific position. However, in our email regex, we do not use the OR operator.

### Character Classes
Character classes allow us to specify a set of characters that can match at a particular position. The \w represents a word character (letter, digit, or underscore). The dot . is used to match any character except a newline. The hyphen - has no special meaning within a character class and can be used as a literal.

### Flags
Flags are used to modify the behavior of the regex matching. In our regex, we do not use any flags.

### Grouping and Capturing
Grouping is denoted by parentheses ( ) and allows us to group multiple elements together. However, our email regex does not use grouping.

### Bracket Expressions
Bracket expressions define a set of characters enclosed in square brackets [ ]. In our regex, we use bracket expressions to match specific characters, such as [\w.-] matching word characters, dots, and hyphens.

### Greedy and Lazy Match
The quantifiers in regex are greedy by default, meaning they match as much as possible. In our regex, the + quantifier is greedy, ensuring that as many word characters, dots, and hyphens as possible are matched.

### Boundaries
Boundaries define positions where certain conditions are met. In our email regex, we do not use any boundaries.

### Back-references
Back-references allow us to refer to previously captured groups. In our email regex, we do not use back-references.

### Look-ahead and Look-behind
Look-ahead and look-behind assertions are used to define conditions that must be satisfied without consuming the characters in the match. In our email regex, we do not use look-ahead or look-behind assertions.

## Author

Ash Shilkin, a very junior developer in training. Link to GitHub: https://github.com/Web3Zero
