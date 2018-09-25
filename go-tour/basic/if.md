# 条件控制语句

条件控制语句，包括：`if` `if else`

## 代码

if.go

```go
package main

import (
	"fmt"
)

func main() {
	if 1 == 1 {
		fmt.Println("1==1 is %s", 1==1)
	}
	if 1 == 2 {
		fmt.Println("1==2 is %s", 1==2)
	} else {
		fmt.Println("1==2 is %s", 1==2)
	}

}

```
---------------
## 编译

```
go build if.go
```

## 输出

```
true
```
