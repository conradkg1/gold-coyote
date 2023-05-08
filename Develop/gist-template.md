# REGEX EXPLANATION

Introductory paragraph (replace this with your text)

## Summary

Regex, short for Regular Expression, is a tool used to define a specific pattern for searching within a text. It consists of a sequence of characters that are used to match and identify certain sets of strings while rejecting others that do not fit the pattern. I will explain all the components below.

Below is an example of Regex that matches an email
/^([a-z0-9_.-]+)@([\da-z.-]+)\.([a-z.]{2,6})$/



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

In regular expressions, anchors are special characters that match a specific position within the text, rather than matching a character. They are used to anchor a regular expression to a specific location in the text, such as the beginning or end of a line, or the start or end of a word. The two most common anchors are the caret (^), which matches the start of a line, and the dollar sign ($), which matches the end of a line.

### Quantifiers

Regex quantifiers are symbols that allow you to specify how many times a particular pattern should appear in the text you are searching or matching. They are used to match a certain number of repetitions of a character or group in a regular expression. Examples of quantifiers include the asterisk (*), which matches zero or more occurrences, the plus sign (+), which matches one or more occurrences, and the question mark (?), which matches zero or one occurrence.

### OR Operator

The OR operator in regular expressions allows you to create a regular expression that matches multiple patterns rather than just a single pattern. It is represented by the pipe character (|) and allows you to specify multiple patterns separated by the pipe character. For example, the regular expression "cat|dog" matches either the string "cat" or the string "dog".

### Character Classes

Regex character classes, also known as character sets, allow you to define a set of characters that you want to match in a regular expression. They are enclosed in square brackets [] and can include a range of characters or a list of individual characters. For example, the character class [abc] matches any occurrence of the letters 'a', 'b', or 'c'. Additionally, certain shorthand character classes such as \d (digits), \w (word characters), and \s (whitespace characters) can be used to match predefined sets of characters.

### Flags

Regex flags are used to modify the behavior of a regular expression pattern. They are specified as a single letter after the closing delimiter of the regular expression. The most commonly used flags are 'i' for case-insensitive matching,

### Grouping and Capturing

In regular expressions, grouping and capturing are used to extract specific parts of a matched string. Grouping is the process of enclosing a portion of the regular expression pattern in parentheses (()), which creates a group. Capturing is the process of storing the matched substring of a group in a separate memory location, which can be accessed later.

### Bracket Expressions

Regex bracket expressions are used to match a single character from a set or range of characters. They are defined by enclosing the characters to be matched within square brackets [ ]. For example, the bracket expression [abc] matches any one character that is either 'a', 'b', or 'c'.

### Greedy and Lazy Match

In regular expressions, greedy and lazy matching refer to how the regex engine tries to match patterns. A greedy match means the regex engine will try to match as much of the input string as possible while still satisfying the pattern. In contrast, a lazy match means the regex engine will try to match as little of the input string as possible while still satisfying the pattern. Greedy and lazy matching can be controlled by using quantifiers, such as '+' or '*'.

### Boundaries

In regular expressions, boundaries are used to match positions within the input string instead of matching characters. Boundaries can be used to match the beginning or end of a word, the beginning or end of a line, or the boundary between a word character and a non-word character.

### Back-references

Back-references in regular expressions refer to previously matched patterns and allow you to match repeated instances of that pattern later in the text. This can be useful for matching things like repeated words, numbers, or characters. Back-references are created by using parentheses to capture a group of characters and then referencing that group later in the expression using the \n notation, where n is the number of the captured group.

### Look-ahead and Look-behind

Look-ahead and look-behind are features in regular expressions that allow you to check for a pattern ahead of or behind the current matching position, without actually including it in the match. Look-ahead is denoted by (?=pattern) and look-behind is denoted by (?<=pattern) for positive look-behind, and by (?<!pattern) for negative look-behind. 

## Author

https://github.com/conradkg1
