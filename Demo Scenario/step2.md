---
title: How to import a library?

---

Now we import the library that is utilized to give us the desired output. In this case, the library we need is `fmt`. This will enable us to perform string formatting. There are many other Go libraries and you can view the standard ones on [pkg.go.dev](https://pkg.go.dev/std).

Import the library by adding this code

{{copy filename='code.go'}}
```go
package main
{{ highlight }}
import (
		"fmt"
)
{{ /highlight }}
```
{{ /copy }}

Next, we will create the main function.