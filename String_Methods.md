# 23 String Methods Every Python Developer Should Know
October 19, 2023 — written by Josafá Marengo, translated by Santliam

### Summary

|Method|Usage|
|------|-----|
|len|Counts the total number of characters in a string|
|capitalize|	Converts the first character to uppercase and the rest to lowercase|
|upper|	Returns a new string with all characters in uppercase|
|lower|	Returns a new string with all characters in lowercase|
|count|	Counts how many times a specific string appears within the string|
|find|	Returns the position of the first occurrence of a substring|
|rfind|	Returns the position of the last occurrence of a substring|
|startswith|	Checks if the string starts with a specific prefix|
|endswith|	Checks if the string ends with a specific suffix|
|index|	Works like find(), but raises a ValueError if not found|
|split|	Splits the string based on a specific separator or delimiter|
|rsplit|	Splits the string based on a specific separator or delimiter, from the end|
|join|	Creates a new string by joining other strings with a separator|
|strip|	Removes whitespace from both ends of the string|
|lstrip|	Removes whitespace from the left side of the string|
|rstrip|	Removes whitespace from the right side of the string|
|removeprefix|	Removes a specific prefix from a string|
|removesuffix|	Removes a specific suffix from a string|
|replace|	Replaces a specific part of a string with another if a match is found|
|format|	Generates formatted output based on string-type data indexes|
|center|	Returns a string centered within a specified width|
|ljust|	Returns the string left-justified within a specified width|
|rjust|	Returns the string right-justified within a specified width|
|partition|	Splits the string into a tuple of three elements based on a substring|

## Introduction

It's essential to have a clear understanding of what exactly a string is.

In simple terms, a string is a data type used to represent textual content rather than numbers in various programming languages. It primarily consists of a predefined collection of characters, including whitespace and numeric digits, and is usually enclosed in single or double quotes to highlight it during program execution.

String literals in Python have no maximum length limit and only depend on your computer’s memory resources.

The string data type in Python comes with a large set of built-in methods. These functions make it easy to modify and work with string literals in Python.

For example, if you want to convert every character in your string to lowercase, there’s a better way to do it than looping through each character manually.

This can be easily achieved in a single line using Python’s lower() method, which performs exactly that task. That’s how useful these methods are in real life.

This article will focus on the most important built-in string methods in Python, which have surprisingly useful applications in string manipulation within data structures and algorithms.

## 1 len

Used to count the total number of characters in a string.
Syntax:

```
len(<string>)

```
```
text = "How many characters are there here?"
print(len(text))

# 35
```
## 2 capitalize

