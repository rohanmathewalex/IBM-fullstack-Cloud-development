## Task 1 - Open the browser console.
In this task, we are going to run the Javascript code in the browser console. The Chrome browser has a v8, which is Google's open source high-performance JavaScript engine.

1. Open a new blank browser page clicking on Ctrl+T(Windows) or Command+T(Mac) to open a new tab.

2. Right-click anywhere on the new blank browser tab and choose Inspect or Inspect Element depending on the browser you are using. The image below is for Chrome Broswer.
3. Go to the Console tab, as shown below. You will see a command prompt. You can run the rest of the tasks there.
4. If your console has any logs printed, clear it by running the following command. This is not mandatory. It will just help in a fresh start.
```
clear()

```
## Task 2 - Running JS commands
> At any point of time, when you want to clear the console run the **clear()** command.
To run the commands we will use the command prompt on the browser control. Type or paste the command and press **enter** to run the command.
1. Let's start with a simple code to print Hello World! to the console. Run the following command.
```
console.log("Hello World!")
```
The undefined means console.log doesn't return anything.
2. Let's create some variable and print them. Run the following command.
```
let num = 23
var mystr = "Rohan"
console.log(num)
console.log(mystr)
```
>Both let and var can be used to create variables. var is used when you want the variable to have global scope and let is used when you want the variable to have scope within the block where it is created.
3. Let's create a constant and print it. Run the following command.
```
const pi_val = 3.147
console.log(pi_val)
```
>Const is used to declare variable whose values can never change
4. Let's create function which prints any value that is input to it.
```
function printMyInput(user_input) {
    console.log("The parameter passed is "+user_input)
}
```
5. Call the function you created in the previous step once with a number and once with a string.
```
printMyInput(9)
printMyInput("John")
```
6 .Let's rewrite the function printMyInput according to the ES6 standard. This syntax is also called **arrow functions** and provide a shorthand to write functions.
```
let printMyInputES6 = (user_input)=>{
    console.log(user_input)
}
```
7. Call the function you created in the previous step once with a number and once with a string.
```
printMyInputES6(9)
printMyInputES6("Rohan")
```
>Since the function is passed a single value and the body of the function is a single line, the brackets can be omitted. The code can also be written as below.
Now when we call it, the output should remain the same.
```
printMyInputES6(9)
printMyInputES6("John")
```

## Task3 - Operators, Conditions, Loops