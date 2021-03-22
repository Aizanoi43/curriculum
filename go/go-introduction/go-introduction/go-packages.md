---
author: Stefan-Stojanovic
type: normal
category: must-know
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: relative
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: relative
---

# Packages


---

## Content

All Go programs are made up of one or more packages.

Every program in Go starts in the `main` package and there can only be one `main` package.

The top of a Go file contains the *package name*

```go
// declare that this code
// belongs to the main package
package main

// ...rest of the code
```

> 💡 A package name is written in lowercase letters

A package can import any other package using the `import` statement:

```go
package main

// We can import packages
// one by one, using the
// Multi-statement import
import "fmt"
import "math"
import "zip"
import "json"

// or we can combine the
// imports as a single
// statement, called
// Factored import
import (
  "fmt"
  "math"
  "zip"
  "json"
)
```

> 💡 We'll show you soon how imports work within a simple Go program

Both ways work the same, however, it is common practice to use the *factored import* as it's quicker to type and easier to change.

> 💡 Factoring means calling a keyword once on multiple instances. Later we'll show other Go keywords that can also be factored.


---

## Practice

Which of these is the common practice way of importing packages in Go?

```go
// Multi-statement import
import "fmt"
import "math"
import "zip"
import "json"

// Factored import
import (
  "fmt"
  "math"
  "zip"
  "json"
)
```

???

- Factored import statement.
- Multi-statement import.


---

## Revision

Using the `import` keyword once to import multiple packages is called ??? import

- factored
- factorial
- factoring
- factual
