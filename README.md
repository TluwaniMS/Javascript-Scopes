# Javascript Scopes

There are 3 types of scopes in Javascript:
* The Global Scope:

This refers to variables declared outside of a function, these variables can be accessed from anywhere within the file.

```
const name = "Thoka";

function sayMyName() {
  console.log(`The name given to me globally is ${name}`);
}

sayMyName();

will print:
/// The name given to me globally is Thoka
```
* The Function Scope:

This refers to variables that are declared inside/within a function; these variables can only be accessed within the function.

```
function sayMyName() {
  const name = "Thoka";
}

console.log(`The name declared in the function scope is ${name}`);
/// This will return an error because name is not defined globally.
```

* The Block Scope:

This refers to functions that are declared inside curly braces `{}` (a block).
Variables declared in these blocks can not be accessed/used outside of the blocks.
