# RegEx

Regex stands for regular expression!! Regular expressions help us with extracting information from any text. We do this by searching for specific patterns with special characters known as unicodes.

## Summary

The Regex I will be talking about is hex value. Hex value is used to check the colors to make us it is the correct one and what we are looking for. Hexadecimal color code should start with '#', then followed by numbers and/or letters. The length of the colour code must naturally lie between three and six characters.

### Examples

^#([a-fA-F0-9]{3,6})$

This searches from upper and lower case letters, and numbers.

/^#?([a-f0-9]{6} | [a-f0-9]{3})$/

This searches two different expressions. Below we are going to explain what some of these RegEx components mean.

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

- An Anchor is two characters to help you search strings. You can do it a few different ways, the first symbol is the " ^ " which is placed in the front and then the word which will search the strings that start with the word you want. The second symbol is the " $ " which is placed at the end of the searched word to match a string that ends with it. You can also combine them both to search of an exact string that starts and ends with those two words or phrase.

#### Example

- ^The - matches any string that starts with The.

- end$ - matches a string that ends with end.

- ^The end$ - exact string match (starts and ends with The end).

### Quantifiers

- Quantifiers are used to do a few things, one is to repeat a part of a regular expression and another would be to match a string. Some of the symbols used for quantifiers would be ( _, +, ?, {}, { , }). this first symbol the (abc _) is used to match ab and none to as many Cs after that. the + is used to find one or more, and the ? is used to find none to one. the brackets are used to for a specific number or between two numbers like 3 and 9.

#### Example

- abc{3} - searches for three Cs exactly

- abc{3,9} - search between 3 and 9

### OR Operator

- the OR operator is two unicode characters | . This is used to match a string followed by one or the other characters. it is also used we searching for one or more conditions that might match, like searching for a color with 3 characters or 6 characters.

#### Example

- a(b|c) - searches for a followed by b or c

- [a-f0-9]{6} | [a-f0-9]{3} - searches for 2 different values of 3 or 6

### Character Classes

- character classes are what we use to search between a range of letters and numbers. this A-F will search for uppercase letters and 0-9 searchs for numbers. we can combine this together to create a single search with multiple conditions

#### Example

- [a-f] - search for lowercase letters a-f

- [A-Z] - search for Upperrcase letters A-Z 

- [0-9] - search for numbers 0-9

### Bracket Expressions

- Bracket expressions are the "[ ]" which is used to search for specific range of characters and numbers.  inside these brackets we can combine character classes like A-Z and a-z so it searches for all upper and lowercase letters together. 

#### Example

- [a-fA-F0-9] - search for lowercase and uppercase letters a-f, also searches numbers 0-9 together.

### Greedy and Lazy Match

## Author

My name is Andrew Febre and this is my github link https://github.com/afebre1027

and the gisthub link 
