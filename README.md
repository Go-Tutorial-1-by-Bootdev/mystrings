# mystrings

A simple Go package for string manipulation functions.

This repository is part of an educational tutorial from [boot.dev](https://www.boot.dev).

## Functions

- `Reverse(s string) string` - Reverses a string left to right

## Usage

```go
package main

import (
    "fmt"
    "github.com/gooneraki/mystrings"
)

func main() {
    reversed := mystrings.Reverse("hello")
    fmt.Println(reversed) // Output: olleh
}
```