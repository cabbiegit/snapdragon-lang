# snapdragon-lang
Snapdragon is strongly typed and compiled. It is also a functional language. The main goal of Snapdragon is to be simplistic, structured, and fast. I took inspiration from Ruby when writing this language. "natural to read and easy to write."

This is a long example that showcases everything Snapdragon can do. (As of now.)
#Snapdragon Example:

#This is a comment.

package math; #This is where packages are declared.

var a : int = 5; #This is an integer. Any number that isn't a decimal is an integer.
var b : float = 5.0; #Floats are floating-point numbers. (Decimals)
const c:string = "Hello, World!"; #Strings are kept within quotation marks.
var d : pointer = @c #The @ symbol indicates a pointer. Pointers can't be constants, since the value can change. 
const e : char = e #A char is a single-letter string literal.
const d : bool = true; #Bools occupy one bit - true and false.

#Long and double types exist for expecially large ints and floats, giving extra memory space for those values.

fn main { #fn main must exist in every project file.
  pass
}







