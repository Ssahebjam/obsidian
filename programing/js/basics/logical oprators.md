
|| => will return the value to its left if it was true and in otherwise it will return the value to its right

console.log(null || "user")
// → user
console.log("Agnes" || "user")
// → Agnes

we can use this for fallback on a defualt value if you have a value that might be empty

main-val || fallback

if the main-val converted to false it can use right value

-----------------------------------------------------------------------
0 - NaN - ("") => are false

------------------------------------------------------------------------
?? => oprator is like || but it will return the right side only if the value on the left is null or undefined.

console.log(0 || 100);
// → 100
console.log(0 ?? 100);
// → 0
console.log(null ?? 100);
// → 100

------------------------------------------------------------------------
&& => if the value to its left is false it return the value and in otherwise it will return right-value

------------------------------------------------------------------------
short-circuit evaluation => when you put a true value in right side of a || oprator its never going to check the right value 

(true || X) or (false && X) -> no matter what x is its never going to check it