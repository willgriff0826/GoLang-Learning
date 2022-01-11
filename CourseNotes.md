### Notes: 

_Packages_

- "package main is special - defines a package that can be compiled and then executed. Must have a function called "main" 
- A reusable package can be used a dependency within the project. E.g. __package calculator__ will not create an executable 

_Import Statements_
- fmt is a standard library of Go. 
- List of all of the packages in the standard library golang.org/pkg 
- Gain access to another package inside of the one we're working in

_Functions_
- Functions work the same as other languages

_File Organization_
- Package declaration first 
- Then import packages we need 
- Declare functions and do things

Types
- Go is a statically typed language
- Basic Go Types: bool, string, int, float64
 ```
	var card string = "Ace of Spades"

	The line above can be written as: 
	card := newCard()
```
- Go compiler will infer the type from the right side
- := is only used on first initialization 

Data Structures
- Array: fixed length list of things 
- Slice: An array that can grow or shrink
- Every element in a slice must be of the same type

Loops
- "Range" is a keyword when we want to iterate over every element in a slice
