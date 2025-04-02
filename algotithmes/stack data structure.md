our computer use a stack internaly called call stack.
when you call a function first your computer allocates memory for that function call.
every time you call a function your computer saves values for all of the variables of that call

when we use recursive functions first computer saves the values of the parent function and when it goes for the child function computer saves the values of the second function in top of the parent function like stacking papers on each other and then when the child function is return the block of the variables that was for it will pop(remove) from the stack . we can see the values of the parent function again and if the parent function return too it will be poped out

when we call a function in side of a function the parent func is paused and it will go in a compeleted state and all of the variables of it will saved.