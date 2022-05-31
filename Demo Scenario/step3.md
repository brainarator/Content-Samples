---
title: Create the main function

---

Create the main function that will implement our stated logic. In the main package, this function is always considered to be the application’s logic entry point. The application logic that we want to implement should return the words “Brainarator’s Hello World”. To do this we use `fmt` library's `fmt.Println()` function which takes a single string as its argument. Add the main function

{{copy filename='code.go'}}
```go
package main
import (
		"fmt"
)
{{ highlight }}
func main() {	
		fmt.Println("Brainarator's Hello World")
}
{{ /highlight }}
```
{{ /copy }}

Our application is now complete. Add the command to compile the application to see the output.

{{ execute }}
```
go run code.go
```
{{ /execute }}