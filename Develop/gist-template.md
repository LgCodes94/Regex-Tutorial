
  # Regex-Insight  
  
  ## Description
  Step into the world of regular expressions with us at Regex Insights. Whether you're new to coding or a seasoned developer, our blog is here to demystify regex.

Get ready for simple tips, real-world examples, and a journey through the basics and beyond. Let's explore the art of coding together! Welcome to Regex Insights, where every expression is an opportunity. Happy coding! 🚀💻🎨
  
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

 * Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`


### Anchors

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ utilizes anchors (^ and $) to precisely match the entire email structure from start to end within a given string.

### Quantifiers

In the email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/, the + quantifier indicates one or more occurrences for the username and domain, allowing flexibility in character combinations. The {2,6} quantifier specifies that the top-level domain must consist of 2 to 6 lowercase letters or dots, providing a range for the TLD length.

### OR Operator

The provided email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ does not explicitly use OR operators (represented by |). Instead, it employs character classes, quantifiers, and literal characters to define a pattern for matching email addresses with specific criteria for the username, domain, and top-level domain.

### Character Classes

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ uses character classes to define valid characters for the username, domain, and top-level domain. This ensures adherence to a specific matching pattern for email addresses.

### Flags

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ has no flags, implying case-sensitive matching and single-match behavior for the entire input string.

### Grouping and Capturing

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ employs grouping with parentheses to capture and separate the username, domain, and top-level domain components for efficient extraction and processing.

### Bracket Expressions

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ uses square brackets [ ] to establish character classes, ensuring valid characters for the username, domain, and top-level domain, thereby enforcing specific pattern criteria.

### Greedy and Lazy Match

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ uses default greedy matching (+) to capture the longest valid sequences for the username, domain, and top-level domain without explicit employment of lazy matching.

### Boundaries

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ uses the ^ anchor to start matching at the beginning of the line and the $ anchor to conclude the pattern at the end of the line, ensuring the entire string adheres to the specified email pattern.

### Back-references

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ doesn't use back-references, which allow the reuse of previously captured groups within the pattern.

### Look-ahead and Look-behind

The email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ does not involve look-ahead or look-behind assertions.

## Author

Blog created by Luis Garcia
https://github.com/LgCodes94/Regex-Tutorial

Regex Insight: https://gist.github.com/LgCodes94/51aa723ecd7b0081ee5057ff3c80137d

URL- https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial

Date Published: [November 14, 2023]
