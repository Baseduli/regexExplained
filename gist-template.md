# regexExplained

Briefing on what the regex does and how it works.

## Summary

Going to review the core components of regex, explaining how each of them work with code snippets. The regex ^(ABC|DEF){2,3}[0-9]{1,4}$ will be used as a reference to explain the various components.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

Anchors are special characters used in regex to specify the position of the match. The ^ anchor specifies the start of a string, while the $ anchor specifies the end of a string. In our reference regex ^(ABC|DEF){2,3}[0-9]{1,4}$, the ^ and $ ensure that the pattern matches the entire string.

### Quantifiers

Quantifiers specify the number of occurrences of a character or a group of characters. {n,m} is a quantifier that matches at least n and at most m occurrences. In our reference regex, {2,3} and {1,4} are quantifiers.

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
