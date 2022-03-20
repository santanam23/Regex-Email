# Title: Regex Email Breakdown

Hi, thank you for checking out my breakdown of a regex email snippet. Through out this breakdown, I will be illustration what code snippet I choose to describe. Enjoy!

## Summary

Regex expressions are commonly used through many progamming languages. It is important to know how to read them and have examples of them in action. I will be defining each section while breaking down examples of the regex email snippet. Below is the code snippet i will be breaking down.
code snippet: ^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The following are regex components used in the code:
Matching Character Sets, Specifying Location, Matching Special Characters
### Anchors
What is an anchor? Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. The first anchor that we see is "^" at the beginning of the code.
Anchors in code:
"^" It shows the beginning of the string
"$" It shows the end of the string


### Quantifiers
What are qualifiers? Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. 
Qualifier in code: "{2,6}"  

### OR Operator or Alternation Operator
OR operator allows you to say one pattern or another one is going to be valid for matching. We do not have a OR Operator in the regex "|".
### Character Classes
Meta Characters: ".[{()\^$+"
Single Characers: "\d" means any digit (0-9), "." means any character except new line
Literal Characters: "@", "\." which is used to create an email address

### Flags
A flag changes the defalt search behavior of a regular expression. For example: "i, g, s, m, y, u" which we do not have in our snippet. 

### Grouping and Capturing
Grouping basically just groups up a sequence of regulatory expression tokens into one unit. For example (a-z) is used three times in the code above.
### Bracket Expressions
Bracket expressions indicate a ret of characters match "[]". We have three sets of bracket expressions in the code snippet.
First: [a-z0-9_\.-] which are any letters and numbers that match a-z, 0-9, or literal character "."
Second: [\da-z\.-] which are any letters and numbers that match a-z, \d (0-9), or literal character "."
Third: [a-z\.] which are any letters that match a-z followed by a literal character "."

### Greedy and Lazy Match
Only greedy qualifier in code: "{2,6}" 

### Boundaries
Boundaries are places between characters. For example: "\b" (a word boundary) or "\B" (non-word boundary). We do not have word boundaries in the snippet

### Back-references
Backreference identifies a repeat character or substring. We do not have this in our code sample.

### Look-ahead and Look-behind
Also known as assertions! Are patterns to be looked beyond or before a match. We do not have this in the code example.

## Author

Miriam Santana is a Web Developer who focuses on making sure the client is always satisfied with the product at hand. Feel free to checkout more samples of her work at https://github.com/santanam23 or email her at miriam.steph.santana@gmail.com