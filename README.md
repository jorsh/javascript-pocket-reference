# JavaScript

## Basics

- A Statement is a group of words, numbers, and operators that perform a specific task.
- An expression is any reference to a variable or value, or a set of variable(s) and value(s) combined with operators.
- Statements are made up of one or more expressions.
`a = b * 2;` *This statement has four expressions in it*
- It’s typically asserted that JavaScript is interpreted, however, the JavaScript engine actually compiles the program on the fly and then immediately runs the compiled code.



## Comments
Comments should explain `why`, not `what`. They can optionally explain `how` if what’s written is particularly confusing.
```javascript
// Single line comment

/*
* Multiline
* Comment
*/
```


## Declarations
- `var`  Declares a variable, optionally initializing it to a value.

`Weak typing`, otherwise known as `dynamic typing`, allows a variable to hold any type of value at any time.

By convention, JavaScript variables as constants are usually capitalized, with underscores _ between multiple words.

- `let` Declares a block scope local variable, optionally initializing it to a value.
- `const` Declares a read-only named constant.

## Blocks
- A Block is a way to group a series of statements together.
- In JavaScript, a block is defined by wrapping one or more statements inside a curly-brace pair { .. }.

## Operators
Operators are how we perform actions on variables and values.

### Assignment operators

| Name                      | Shorthand operator |  Meaning   |
| :------------------------ | :----------------: | :--------: |
| Assignment                |       x = y        |   x = y    |
| Addition assignment       |       x += y       | x = x + y  |
| Subtraction assignment    |       x -= y       | x = x - y  |
| Multiplication assignment |       x *= y       | x = x * y  |
| Division assignment       |       x /= y       | x = x / y  |
| Remainder assignment      |       x %= y       | x = x % y  |
| Exponentiation assignment |      x **= y       | x = x ** y |


- Comparison operators
- Arithmetic operators
- Bitwise operators
- Logical operators
- String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operator


## Data Types

- A primitive is data that is not an object and has no methods.
- All primitives are immutable.

| Type      | typeof evaluation | Primitive |
| --------- | :---------------: | :-------: |
| Boolean   |      boolean      |    yes    |
| Number    |      number       |    yes    |
| String    |      string       |    yes    |
| Symbol    |      symbol       |    yes    |
| null      |      object       |    yes    |
| undefined |     undefined     |    yes    |
| Object    |      object       |    no     |
| Function  |     function      |    no     |
| Array     |      object       |    no     |


## Type Coercion
Coercion is the ability to convert between types.
Coercion can be Implicit or Explicit



## Falsy Values
- ""
- 0
- null
- undefined
- NaN
- false

## Variables
### Naming Convention
### Reserved Words

## Strings
### String Methods

## Numbers
### Arithmetic Operations
### Number Methods

## Conditionals
if
switch

## Loops
while
do
for

## Functions
- A function is generally a named section of code that can be “called” by name, and the code inside it will be run each time.
- Functions can optionally take arguments (aka parameters)—values you pass in. And they can also optionally return a value back.

## Scope
- Scope consists of a series of "bubbles" that each act as a container or bucket, in which identifiers (variables, functions) are declared. These bubbles nest neatly inside each other, and this nesting is defined at author-time.
- The lexing phase of compilation is essentially able to know where and how all identifiers are declared, and thus predict how they will be looked-up during execution.
- Two mechanisms in JavaScript can "cheat" lexical scope: eval(..) and with. 

- The **Principle of Least Privilege** states that in the design of software, such as the API for a module/object, you should expose only what is minimally necessary, and "hide" everything else.

## Closure
## Hoisting
## Prototype

___
### Notes
- JavaScript was created in 1995 by Netscape
- There’s no need to actually use a semicolon to terminate a statement because JavaScript interpreters use a process called Automatic Semicolon Insertion (ASI).
- Technically, only objects have properties and methods. JavaScript overcomes this by creating wrapper objects for primitive values. This all happens in the back- ground, so for all intents and purposes it appears that primitive values also have properties and methods.
- TODO IDEs
- TODO Debugging
- Console

___
#### Sources
- You Don't Know Javascript by Kyle Simpson
- MDN