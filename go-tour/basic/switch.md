# 选择控制语句

选择控制语句，包括： `switch`

## 代码

switch.go

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

## 编译

```
go build switch.go
```

## 输出

```
true
```
