GO Cross Compiling Help

Use Below command to cross compile GO code to arm/linux

**$ env GOOS=linux GOARCH=arm go build <file>**
  
Here is way to reduce the binay size

**$ go build -ldflags "-s -w" hello.go**
