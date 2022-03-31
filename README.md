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
```
* The Function Scope:

This refers to variables that are declared inside/within a function; these variables can only be accessed within the function.
* The Block Scope:

This refers to functions that are declared inside curly braces `{}` (a block).
Variables declared in these blocks can not be accessed/used outside of the blocks.
