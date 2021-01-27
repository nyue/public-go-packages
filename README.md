# public-go-packages
For initial import test

## Usage
```go
package main

import (
	"fmt"

	foo "github.com/nyue/public-go-packages"
	sum "github.com/nyue/public-go-packages/compute"
)

func main() {
	fmt.Println("Hello World")
	fmt.Println(foo.Bar())
	fmt.Println(sum.Add())
	fmt.Println(sum.Subtract())
}
```
