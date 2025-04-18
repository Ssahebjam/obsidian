functions is a piece of program wrapped in value. this values can called to run the piece of the program using a function is called invoking, calling, applying.

when a function produces a value it is said to return that value

let x = function(param) {
	code
}

-----------------------------------------------------------------------------------------------
this is another way to use functions this is function declaration

hello("soheyl")     // This works

function hello(param) {
	code
  }

important -> this type of function no matter where they are declered when ever you call them they will to the top of the call

-----------------------------------------------------------------------------------------------
Arrow functions

const hello = (param) => {
	code
}

const square = (x) => {return x * x}
const square2 = x => x * x;

if we have only 1 param we can remove the parentheses and if we have 1 line of code instead of a block we can remove the brackets;

-----------------------------------------------------------------------------------------------
if you defeine a function with 1 argument and call it with three arguments the js will not complain and set the extra parameters to undefined

-----------------------------------------------------------------------------------------------
Closure -> local variables of a function is created every time a function is called the local variables of inside of this function are saved in memory even doe the function call is ended we make them with returning another function in side of the function 

function multiplier(factor) {
	return number => number * factor;
}
let twice = multiplier(2)
console.log(twice(2))
// 4

as we can see the 2 number the we  gave the multiplier is saved