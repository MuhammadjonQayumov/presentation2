# Java Script Lecture 2

## Table of Contents

> - SCOPE
>
> - HOISTING
> 
> - RECURSION
>
> - CLOUSER

## Scope (Область видимости)

>Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global: Global variables are those declared outside of a block. Local variables are those declared inside of a block.

>There are 4 types of scope :
> 
> - 1) Global scope : In a programming environment, the global scope is the scope that contains, and is visible in, all other scopes.
>
>![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS1SBA4POkFHsPD7RUgy9lbV6r0eRudX7jdn0Yj2gSyZFloGkpmF8j1v5uDh1O3zYZ9_yo&usqp=CAU)
>
> - 2) Function scope : A function creates a scope, so that (for example) a variable defined exclusively within the function cannot be accessed from outside the function or within other functions.
>
> - 3) Block scope : Block scoped variables: A block scoped variable means that the variable defined within a block will not be accessible from outside the block. A block can reside inside a function, and a block scoped variable will not be available outside the block even if the block is inside a function.
>
> - 4) Module scope : In modules, a variable declared outside any function is hidden and not available to other modules unless it is explicitly exported. Exporting makes a function or object available to other modules. In the next example, I export a function from the sequence.