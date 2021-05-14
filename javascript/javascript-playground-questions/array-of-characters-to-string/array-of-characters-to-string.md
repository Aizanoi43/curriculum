---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: "// 👋 Welcome to the JavaScript coding playground. \n. // The array of characters: \n let c = ['h', 'e', 'l', 'l', 'o', ' ', 'w', 'o', 'r', 'l', 'd'] \n"

---

# Array of Character to a String

---

## Content

Given an array of characters:
```javascript
let c = [
  'h', 
  'e', 
  'l', 
  'l', 
  'o', 
  ' ', 
  'w', 
  'o', 
  'r', 
  'l', 
  'd'
]
```

Can you write a program that will take the array as input, transform it into a string, and output the result?

To achieve this, you can use the following concepts:
- function declaration (`function something(x) { ... }`)
- flow control (`for...of`)

Learning is best when we give it an honest try. Even if we make a mistake, we'll remember it and do better next time.

That being said, if you're not sure how to get started, check out this footnote[1]. 

When you're finished, feel free to share your solution with the community, join in on discussions and upvote solutions from your fellow learners!

Remember, learning is more effective when we do it with others.

> 💡 Take a look at [how you can format text using markdown](https://www.enki.com/glossary/general/markdown-formatting).

> 💡 The guidelines above are just suggestions. Feel free to include other concepts in your solution as you see fit. The implementation is up to you.

> 🤓 Happy learning! Open the playground and start coding!


---

## Footnotes

[1: Hints]

Create an empty string and use a `for...of` loop to go through every character of the array, concatenating each character to the empty string.