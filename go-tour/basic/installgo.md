# Go 环境安装

## Go安装

### Go源码下载

[https://studygolang.com/dl/golang/go1.9.1.src.tar.gz](https://studygolang.com/dl/golang/go1.9.1.src.tar.gz)

### Windows
下载地址
[https://studygolang.com/dl/golang/go1.9.1.windows-amd64.msi](https://studygolang.com/dl/golang/go1.9.1.windows-amd64.msi)

### *nix
```
wget https://studygolang.com/dl/golang/go1.9.1.linux-amd64.tar.gz
```

### Mac
```
brew install go
```

------------
## 环境变量设置
`GOPATH`是工作目录

`GOROOT`是go语言源码

### Windows
设置环境变量`GOPATH`以及`GOROOT`

### *nix
```
export GOROOT=<go 源码目录>
export GOPATH=<go 工作目录>
export PATH=$PATH:$GOROOT/bin
```

### Mac
```
export GOROOT=/usr/local/Cellar/go/1.9/libexec
export GOPATH=<go workspace>
export PATH=$PATH:$GOROOT/bin
```

-------------
## git安装
下载[https://git-scm.com/download/win](https://git-scm.com/download/win)

## VScode安装
下载[https://code.visualstudio.com/Download](https://code.visualstudio.com/Download)
