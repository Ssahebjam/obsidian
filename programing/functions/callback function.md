when you pass a function to another function as an argrument the function will execute it self first and the will execute the function that we gave it before.

function greet(name) {
  console.log("Hello, " + name);
}

function processUserInput(callback) {
  const name = "Soheyl";
  callback(name); // calling the callback
}

processUserInput(greet);