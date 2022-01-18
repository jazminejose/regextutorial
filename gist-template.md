# Regex Tutorial

What is regular expressions? Regular expressions is a string of characters that specifies a search pattern. It is used to create patterns that help with matching, locating and managing text. 

## Summary

A tutorial explaining regular expressions.

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

Anchors do match any character but match a position before or after characters. 

`^` - caret anchor matches the beginning of the text <br>
`$` - dollar anchor matches the end of the text

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

`*` - match zero or more times
`+` - match one or more times
`?` match zero or one time
`{ n }` - match exactly n times
`{ n, }` - match at least n times
`{ n, m }` - match from n to m times

### Grouping Constructs

Grouping constructs create a sub-expression by placing an expression inside matching open and close parentheses. Each set of parentheses create a capture numeber that is used to identify capturing groups.

`()` - capturing group. captures the information that matches the expression in parentheses
`(?:)` - non-capturing group.
`(?=)` - captures information that is followed by the expression if the expression is true and the input matches the pattern that follows this expression
`(?<>)` - named capture group

### Bracket Expressions

Bracket expressions are a list of characters and/or character classes enclosed in brackets. 

`[abc]` - a, b, or c
`[a-z]` - a through z
`[^abc]` - any character except a, b, or c
`[[:alpha:]]` - any alphabetic character 

### Character Classes

Character classes distinguish kind of characters, for example, distinguishes between letters and digits.

`\d` - matches a digit 
`\s` - matches a whitespace sumbol such a space
`\w` - matches a word character
`.` - matches any character

`\D \S \W` - inverse classes
### The OR Operator

The Alternation Operation (OR) is used to match a single regular expression out of several possible regular expressions.

`(|)` - matches a string and uses either/or of the vertical bar

### Flags

`i` - makes the search case-sensitive
`g` - search looks for all matches, without -- only the first match is returned
`m` - multiline mode
 
### Character Escapes

`\` - used to escape a special character
`^` - beginning of a string
`$` - end of a string
`.` - matches any single character
`|` - matches previous OR next character/group
`?` - match zero or one of the previous
`*` - match zero, one or more of the previous
`+` - match one or more of the previous
`( )` - group characters
`[ ]` - matches a range of characters
`{ }` - matches a specified number of occurrences of the previous

## Author

<a href="https://www.github.com/jazminejose">GitHub Profile</a>

