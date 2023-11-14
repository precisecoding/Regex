# Title (replace with your title)

Matching an Email:`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Summary
 
This tutorial will cover the basics of regular expressions, also known as regex. Regex is a sequence of characters that define a search pattern. It is used to find and replace text in a string or document. Regex is used in many programming languages, including JavaScript, Python, and Ruby. It is also used in text editors such as Sublime Text and VS Code.

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
This section will cover the different components of a regular expression. Each component has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.
### Anchors
The `^` and `$` are anchors. They match the position before the first character and after the last character in a string, respectively. In this case, the `^` anchor matches the beginning of the string, and the `$` anchor matches the end of the string. This ensures that the entire string is matched, and not just a portion of it. 

### Quantifiers
The `+` and `?` are quantifiers. They match the preceding token one or more times, and zero or one time, respectively. In this case, the `+` quantifier matches the preceding token one or more times, and the `?` quantifier matches the preceding token zero or one time. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### Grouping Constructs
The `()` are grouping constructs. They group multiple tokens together and create a capture group for extracting a substring or using a backreference. In this case, the `()` grouping constructs group the tokens that precede and follow the `@` symbol. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### Bracket Expressions
The `[]` are bracket expressions. They match a single character that is contained within the brackets. In this case, the `[]` bracket expressions match a single character that is contained within the brackets. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### Character Classes
The `a-z`, `0-9`, and `.` are character classes. They match any one of a set of characters. In this case, the `a-z` character class matches any lowercase letter, the `0-9` character class matches any digit, and the `.` character class matches any character. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### The OR Operator
The `|` is the OR operator. It matches either the expression before or after the operator. In this case, the `|` OR operator matches either the expression before or after the operator. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### Flags
The `/` is the flag. It is used to indicate the beginning and end of an expression. In this case, the `/` flag is used to indicate the beginning and end of the expression. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

### Character Escapes
The `\` is the character escape. It is used to escape a special character. In this case, the `\` character escape is used to escape the `.` character. This ensures that the string contains at least one character before the `@` symbol, and that the string contains zero or one `#` symbol.

## Author

- [GitHub Profile](https://github.com/precisecoding)
- Author: Jeff Rojas

