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
<img src="https://github.com/user-attachments/assets/a35a084c-d005-49a2-992a-7a18191383c4" width="800px" height="600px" alt="Output"></img>
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

### Run the application

```
go run ./variables.go
```
Expected Output 1
<img src="https://github.com/user-attachments/assets/75b1bf7c-788e-466b-bd42-e3c50e26473c" widh="800px" height="600px"></img>

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
	
	var firstnumber,secondnumber int = 10,20
	fmt.Println("Value of first number is", firstnumber)
	fmt.Println("Value of second number is", secondnumber)
}
```
Expected Output 2
<img src="https://github.com/user-attachments/assets/2a63d3ae-9f2d-421b-94eb-83d3bd88c2a2" widh="800px" height="600px"></img>


Expected Output 3
<img src="https://github.com/user-attachments/assets/8fc4849b-18c7-42d4-ba45-2a34c8d0388d" widh="800px" height="600px"></img>



