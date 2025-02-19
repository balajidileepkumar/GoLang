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

```

### Run the application

```


go run ./variables.go
```
![414251325-9c46a535-5104-4b41-927c-1b24a764f990-1](https://github.com/user-attachments/assets/a037490a-298f-4d90-a0c0-51858cf75bc7)
![414254268-ec5f6111-2400-4844-b736-8080f080b520-2](https://github.com/user-attachments/assets/cf00ed03-d1ee-4996-9d64-291585f18f27)
![414254687-64b402f2-dd7d-4113-a8c0-e10cd939b3bd-3](https://github.com/user-attachments/assets/f8eaba8a-ce23-4614-8e9a-8b4c022dfa5b)
![414258330-8be5d12f-0b5c-4406-b25f-03e46cfc5bd8-4](https://github.com/user-attachments/assets/6031d678-e3ba-4f7a-ba89-8858988cfd7a)



[414254268-ec5f6111-2400-4844-b736-8080f080b520-2](https://github.com/user-attachments/assets/cf00ed03-d1ee-4996-9d64-291585f18f27)
