# Regex_Guide

In this guide to Regex or (regular expressions) , we will be taking a brief look into what these expressions are and how they work. While regular expressions may seem to be overwhelming at first glance, just like with any language in programming, they can be broken down into much easier to understand parts and pieces.

## Summary

Regex (short for regular expression) is a string of text that allows you to create search patterns that match, manage, and locate text. An example code snippet of regex shows as following:
```
/[\w._%+-]+@[\w.-]+\.[a-zA-z]{2,4}/
```
* A regular expression used to match an e-mail address

Regular expressions can also be used from the command line and within text-editors to find text within a file. 

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

* Matching Fixed Strings
* Matching Special Characters
* Matching Character Sets
* Specifying Groups and Fields
* Evaluating Occurrences
* Specifying Location
* Specifying Alternatives
* Matching Information from a Table
* Capturing Multiple Lines
* Managing the Scope of Analysis

### Anchors

Anchors are characters within the regular expression that allow the user to match strings that either begin with, end with or sometimes begin and end with certain characters. 

Examples of some Anchors are as follows:

* `^` - matches any string that start with the anterior word
* `$` - matches a string that end with preceeding word before the character
* Examples:
```
^Hello          matches any string starting with `Hello`
World$          matches any string ending with `World`
^Hello World$   matches exact string
goodbye         matches any string that has the exact text `goodbye` in it
```

### Quantifiers

Qunatifiers are characters within the regular expression that specify how many instances a character, group, or character class must be represented in the input to be matched.

Examples of Quanitifers are as follows:

* `*` - matches a string that has the anterior followed by zero or more of the last character
* `+` - matches a string that has the anterior followed by one or more of the last character
* `?` - matches a string that has the atnerior follwoed by zero or one of the last character
* `{}` -  matches a string that has the anterior followed by how ever many the number in the brackets of the last character in the string
* `()*` - matches a string that has any anterior characters followed by zero or more copies of the string within the brackets
* Examples:
```
xyz*        matches a string that has xy followed by zero or more z
xyz+        matches a string that has xy followed by one or more z
xyz?        matches a string that has xy followed by zero or one z
xyz{2}      matches a string that has xy followed by 2 z
xyz{2,}     matches a string that has xy followed by 2 or more z
xyz{2,5}    matches a string that has xy followed by 2 up to 5 z
x(yz)*      matches a string that has x followed by zero or more copies of the sequence yz
x(yz){2,5}  matches a string that has x followed by 2 up to 5 copies of the sequence yz
```

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

I am a Colorado native and current student at the University of Denver enrolled in their full-stack coding boot-camp. In my free time I enjoy learning new skills such as American Sign Language and the development of video games, working on personal goals and helping my community. I enjoy hiking, camping and paddle-boarding. I enjoy spending time with family and friends playing board games like chess, and card games like cribbage and poker.

After graduating from culinary school with a Bachelor's of Science in Food Service Management I decided on broadening my horizons and seeing the world. I am a travel enthusiast with skills in business, marketing, and computer programming. I spent the last 10 years traveling both internationally and around the United States. This enabled me to get a vast amount experience in different jobs as well as seeing different cultures and communities. It has given my a wealth of knowledge in both business and customer service as well as hospitality. I am eager to get started with my career in this field and am looking to using my skills to start a successful career in the Computer Programming and Technology Industry.

🖥️Full Stack Developer certificate from University of Denver
🤔 I’m currently learning React and Computer Science
📧 How to reach me: katlynboches@gmail.com
🧘‍♀️ Hobbies: I enjoy hiking, slack-lining and yoga

Want to see my resume? [Resume] (https://docs.google.com/document/d/13ygbQcv5SL4h9NxDM9orSG58AbcoeopaelRb3ivmf88/edit)

GitHub Repository: [GitHub] (https://github.com/Katlyn627/Regex_Guide)

