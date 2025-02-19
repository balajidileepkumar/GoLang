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
![image](https://github.com/user-attachments/assets/a35a084c-d005-49a2-992a-7a18191383c4){:height="360px" width="480px"}

## Lab - Variables in golang

Create a file named variables.go with the below content
```
package main

import "fmt"

func main() {
	var inventor1 = "Ken Thompson" //Declares a string implicitly

	inventor2 := "Rob Pike"	       //Short form of declaring a variable and initializing it with some value
	var inventor3 string	       //Declares string variable
	inventor3 = "Robert Griesemer" //initialize the string variable with a value

	fmt.Println ("Golang inventors")
	fmt.Println ( inventor1 )
	fmt.Println ( inventor2 )
	fmt.Println ( inventor3 )
}
```

