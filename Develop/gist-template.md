# <center> Regex: A Program's Tool

Regex, short for regular expression, is a sequence of characters that defines a specific search pattern. Many fields within the tech industry utilize this powerful tool for data processing and manipulation. 
<br><br>

## <center> Summary

One of the many ways regex is used in JavaScript is through form validation. This tutorial will examine code containing a regex, break down its parts, and describe its function. 
<br><br><br><br>

## <center>Table of Contents

- [Regix Snippet](#regex-snippet)
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

<br><br>

## <center>Regex Snippet
`
function validateEmail(email) {
  const emailRegex = /^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+)\.([a-zA-Z]{2,6})$/;
  return regex.test(email);
}
`

<br>

## <center>Regex Components
<br>
Regular expressions (regex) are made up of various components that can be combined in different ways to create complex patterns that match specific sets of characters or strings. A component is a single part or element of the overall pattern that is being matched. We will review several components: Anchors, Quantifiers, Grouping Constructs, Bracket Expressions, Character Classes, The OR Operator, Flags, and Character Escapes.
<br><br>

### <center>Anchors
<br>
Anchor components match a specific position in the string being searched or matched at the beginning or end of the string. The caret "^" anchor matches the beginning of the string. In comparison, the dollar "$" anchor matches the end of the string.

This is identified in our snippet below:

`const addressRegex = /^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+)\.([a-zA-Z]{2,6})$/;`

<br>

### <center>Quantifiers
<br>
A quantifier is a component that specifies how many times the preceding character or string should match. It allows one to specify a minimum and/or maximum number of times a pattern should match within a string.

`const addressRegex = /^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+)\.([a-zA-Z]{2,6})$/;`

Quantifier {2,6} sets the minimum character limit to 2, while the maximum is 6 for the preceding string.
<br>

### <center>Grouping Constructs
<br>
Grouping constructs are components that group subpatterns and apply quantifiers and other operators to the entire group as a unit. They are used to create more complex patterns that match specific patterns within strings. The most commonly used grouping constructs are parentheses "( )."

`const addressRegex = /^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+)\.([a-zA-Z]{2,6})$/;`
<br>

### <center>Bracket Expressions
<br>
A bracket expression is a way to match a set of characters. Bracket expressions are enclosed in square brackets "[ ]" and can contain any number of characters or character ranges.

`const addressRegex = /^([a-zA-Z0-9._-]+)/;`
<br>

### <center>Character Classes
<br>
A character class matches any symbol from a specific character set. A character class is also called a character set.

`const addressRegex = /^([a-zA-Z0-9._-]+)/;`

<br>

### <center>The OR Operator
<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<br>

### <center>Flags
<br>
A flag component is used to modify the behavior of the pattern matching in various ways. Flags are specified at the end of a regular expression They are indicated by a single letter.

<br> 
Common used Flags
g (global): This flag tells the regex engine to find all matches within the input string, rather than just the first match.
i (case-insensitive): This flag makes the pattern matching case-insensitive, so that it matches both uppercase and lowercase letters.
m (multiline): This flag changes the behavior of the "^" and "$" anchor characters so that they match the start and end of each line in a multiline string, rather than just the start and end of the whole string.
<br><br>

### <center>Character Escapes
<br>
A character escape is a way to match a special character or a character that has a special meaning in regex. A backslash "\" is used to indicate that the following character should be treated as a literal character, rather than as a special character.

`const addressRegex = /^([a-zA-Z0-9._-]+)@([a-zA-Z0-9.-]+)\.([a-zA-Z]{2,6})$/`
<br><br><br>

# <center>Author
Github<br>
https://github.com/LightintheBulb
<br>

<br>
Twitter
<br>
https://twitter.com/LightintheBulb
<br>

