# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```js
const functionName = (params) => {
  // code to be executed
}
```
•⁠  ⁠**const:** const should be used whenever a function expression is assigned to a variable.
**The function name:** The name you choose for the function.
•⁠  ⁠**Parameters:** Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
•⁠  ⁠**The arrow syntax:** Indicates that this will be a function.
•⁠  ⁠**The body:** The statements that make up the function itself. Surrounded by curly braces.

•⁠  ⁠**Example:**


```js
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

	⁠Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

**Example**:
```js
greet('Alice'); // Outputs: Hello, Alice!

```
## 3. Return values

Functions can process data input and output a value using the return keyword.

**Example**: 
```js
const addNums = (numA, numB) => {
  return numA + numB
}


const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs]


[MDN docs]: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions]

[details](https://www.rotanastar.ae/ar/?utm_campaign=AR%20-%20Rotana%20World&utm_term=تاجير%20سيارة%20فاخرة%20دبي&utm_source=adwords&utm_medium=ppc&hsa_ver=3&hsa_acc=8666845445&hsa_mt=p&hsa_src=g&hsa_cam=15356230739&hsa_grp=129340925919&hsa_tgt=kwd-3500001&hsa_kw=تاجير%20سيارة%20فاخرة%20دبي&hsa_ad=702397993845&hsa_net=adwords&gad_source=1&gad_campaignid=15356230739&gbraid=0AAAAADC3t9O5NOaza7E3a4bjjswqcCEqc&gclid=CjwKCAjwprjDBhBTEiwA1m1d0i67fgCSfriz8rUDcP1SZqYHaY-cyDPWNdGF3SLxx2XnTnu0esNOIRoCeeMQAvD_BwE)

![this is car](https://images-ext-1.discordapp.net/external/rXJurhfKF5ASk8LNyVePQKc8MiUiv_iNxR5tWXrMrNo/%3Fq%3D80%26w%3D1374%26auto%3Dformat%26fit%3Dcrop%26ixlib%3Drb-4.1.0%26ixid%3DM3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%253D%253D/https/images.unsplash.com/photo-1751442188780-c4ba25403392?format=webp&width=1472&height=1104)
