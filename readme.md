# 当前版本的 thrift go 无法编译的问题
thrift 的 golang 库，现在官方Golang thrift 库与生成的代码不匹配，导致无法编译，可以使用这个版本的代码，下载后将 git.apache.org 放到 gopath 的 src 目录下即可，最好是现在使用 go get git.apache.org/thrift.git/lib/go/thrift 获取后，再进行替换，不然不会报一些其他的依赖库找不到。