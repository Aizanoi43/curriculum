---
author: tommarshall
type: normal
category: must-know
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
    - type-in-the-gap
  context: standalone
---

# Calling functions


---

## Content

To call a function in Python, you write the function's name followed by some parentheses `()`.

For example:

```python
# To define
def new_func():
    print ('Function time!')

# To call
new_func()

```

Gives the following output:

```plain-text
Function time!
```

A parameter in Python is a variable which can be passed into functions so that methods can be performed onto it.

In this example, variable `x` is passed into the function as a parameter:

```python
def func(x):
    ans = x * x
    print(ans)
```

So to call this function, you must pass a parameter into your function call as follows:

```python
num = 5
func(num)
```

In the example, variable `x` will take the value of `num`, therefore the output will be:

```plain-text
25
```


---

## Practice

Complete the code to define and call the `mean` function to get the arithmetic mean of `x` and `y`:

```python
x = 4
y = 2
??? mean(a, b):
    print((a + b) / 2)

???(???)
```

- def
- mean
- x, y
- (x, y)


---

## Revision

Complete the code snippet to define and call the function with the correct parameter:

```python
??? cube(x):
    res = x * x * x
    print (res)

num = 5
???(???)
```

- `def`
- `cube`
- `num`
- `x`
- `new`
- `obj`
- `var`
- `function`
 
