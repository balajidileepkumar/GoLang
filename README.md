# GoLang
Basics of Go Programming Language

## Info - Golang Overview
<pre>
- golang is developed by Google in C Programming language
- it is faster than any interpretter based languages like Ruby, Python, etc.,
- it is also faster than most compiler based programming languages
- it is a compiler
- golang syntax resembles like C programming language
- golang remove all confusing features, keeping only useful, non-confusing features
- golang avoid memory management issues we have in C/C++
- golang support about 25 keywords
</pre>

## Lab - Running your first hello world go program
Create a file named hello.go with the below content
```
package main 

import "fmt"

func main() {
  fmt.Println( "Hello Golang !" )
}
```
To run the program
```
go run ./hello.go
```
Expected output
![image](https://github.com/user-attachments/assets/a35a084c-d005-49a2-992a-7a18191383c4)
