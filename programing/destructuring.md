getting the values of a object or array and instead of saving it one by one in variables we can write them with just 1line of code like this =>

// not goood!
let arr = [1,2,3]
let one = arr[0]
let one = arr[2]
let one = arr[3]

nice!!!!
let [a,b,c] = arr

we can do this with objects to => 

bad!!
let name = obj.name
let lastName = obj.lastName

goooood!!!
let {name,lastName} = obj
