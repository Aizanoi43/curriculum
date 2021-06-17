---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    // 👋 Welcome to the JavaScript coding playground.
    // These are the arrays:
    
    name = ["Stefan", "Michael", "Rebekah", "Natasha"]
    lastName = ["Stojanovic", "Stevens", "Mikaelson", "Romanoff"]

---

# Iterate Over two Arrays

---

## Content

Given two arrays:

```javascript
let names = ['Stefan', 'Michael', 'Rebekah', "Natasha"];
let lastNames = ['Stojanovic', 'Stevens', 'Mikaelson', "Romanoff"];
```

Can you write a program that will iterate over both arrays simultaneously and output the corresponding values?

Example output:
```plain-text
Stefan Stojanovic
Michael Stevens
....
```

To achieve this, you can use the following concepts:
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

Create the arrays and use a loop to cycle through them. 

> Use the same index to track the second array as well.