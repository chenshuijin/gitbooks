# 条件选择语句

条件选择语句，包括： `switch`

## 代码

switch.go

```go
package main

import (
	"fmt"
)

func main() {
	switch {
	case 1 == 1:
		fmt.Println("1 == 1")
		fallthrough
	case 2 == 2:
		fmt.Println("2 == 2")

	case 3 == 3:
		fmt.Println("3 == 3")

	}
}

```

## 编译

```
go build switch.go
```

## 输出

```
true
```
