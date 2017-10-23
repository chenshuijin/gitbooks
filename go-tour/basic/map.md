# map 的使用

map的使用，包括： `map`

## 代码

map.go

```go
package main

import (
	"fmt"
)

func main() {
	ms := map[string]string{"a": "a", "b": "b"}
	mi := map[int]int{1: 1, 2: 2, 3: 3}
	for index, item := range ms {
		fmt.Printf("index:%s, items %s\n", index, item)
	}
	for index, item := range mi {
		fmt.Printf("index:%d, items %d\n", index, item)
	}

	v, isExist := mi[1]
	fmt.Printf("v:%d, isExist:%v \n", v, isExist)
}

```

## 编译

```
go build map.go
```

## 输出

```

```
