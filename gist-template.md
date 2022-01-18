# Regex Tutorial

What is regular expressions? Regular expressions is a string of characters that specifies a search pattern. It is used to create patterns that help with matching, locating and managing text. 

## Summary

A tutorial explaining regular expression:<br>
Matching an email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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

`*` - match zero or more times<br>
`+` - match one or more times<br>
`?` match zero or one time<br>
`{ n }` - match exactly n times<br>
`{ n, }` - match at least n times<br>
`{ n, m }` - match from n to m times<br>

### Grouping Constructs

Grouping constructs create a sub-expression by placing an expression inside matching open and close parentheses. Each set of parentheses create a capture numeber that is used to identify capturing groups.

`()` - capturing group. captures the information that matches the expression in parentheses<br>
`(?:)` - non-capturing group.<br>
`(?=)` - captures information that is followed by the expression if the expression is true and the input matches the pattern that follows this expression<br>
`(?<>)` - named capture group<br>

### Bracket Expressions

Bracket expressions are a list of characters and/or character classes enclosed in brackets. 

`[abc]` - a, b, or c<br>
`[a-z]` - a through z<br>
`[0-9]` - 0 through 0<br>
`[^abc]` - any character except a, b, or c<br>
`[[:alpha:]]` - any alphabetic character <br>

### Character Classes

Character classes distinguish kind of characters, for example, distinguishes between letters and digits.

`\d` - matches a digit <br>
`\s` - matches a whitespace sumbol such a space<br>
`\w` - matches a word character<br>
`.` - matches any character<br>

`\D \S \W` - inverse classes<br>
### The OR Operator

The Alternation Operation (OR) is used to match a single regular expression out of several possible regular expressions.

`(|)` - matches a string and uses either/or of the vertical bar

### Flags

`i` - makes the search case-sensitive<br>
`g` - search looks for all matches, without -- only the first match is returned<br>
`m` - multiline mode
 
### Character Escapes

`\` - used to escape a special character<br>
`^` - beginning of a string<br>
`$` - end of a string<br>
`.` - matches any single character<br>
`|` - matches previous OR next character/group<br>
`?` - match zero or one of the previous<br>
`*` - match zero, one or more of the previous<br>
`+` - match one or more of the previous<br>
`( )` - group characters<br>
`[ ]` - matches a range of characters<br>
`{ }` - matches a specified number of occurrences of the previous

## Author

My name is Jazmine Jose and I am an aspiring web developer. Currently attending UCI Coding Bootcamp.

<a href="https://www.github.com/jazminejose">GitHub Profile</a>

