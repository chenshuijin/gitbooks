# 循环控制语句

循环控制语句，包括：`for` `while`

## 代码

loop.go

```go
package main

import (
	"fmt"
)

func main() {
	i := 0
	for i:=0; i<3; i++{
		fmt.Println("for: ", i);
	}
	i = 0
	while i<3 {
		fmt.Println("while: ", i);
		i += 1
	}
	s := "abcdefghij"
	for index, item := range s {
		fmt.Println("index %d, item %s", index, item)
	}
}
```

## 编译

```
go build loop.go
```

## 输出

```

```
