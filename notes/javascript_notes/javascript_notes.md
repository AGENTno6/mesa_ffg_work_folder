# Learning JavaScript

The language of most modern web browsers<br>

## Basics

**syntax**- the set of rules that define the meaning of an arrangement of symbols.<br>
Console- displays important messages, like errors.<br>
`;` - semicolons are placed at the end of a line or statement.<br>

**Comments**- can explain what the code is doing, leave instructions for others and just add useful annotations.<br>
A single line comment will take up one line
`//This is a single line comment taking up one line and one line only.`<br>

A multi-line comment will take up more than one line. You use `/*` to begin your comment and `*/` to end your comment.<br>

## Data Types

Data types - the classifications given to each type of data we use. In JavaScript **there are 7 types**.<br>

- Number- any number, including those with decimals.(Written without quotes)
- String(text)- any grouping of characters (letters, numbers,spaces, symbols) surrounded by single quotes ('...').
- Boolean- this data type has two possible values, `true` and `false`. Its helpful to think of booleans as off and on switches.
- `null`- this data type represents the intentional absence of a value and is represented by the keyword `null`.
- `undefined`- this also represents the absence of a value **BUT** this means the value _doesnt exist_.
- Symbol- unique identifiers, useful in complex coding.
- Object- collections of related data.

## Arithmetic Operators

Operator- a character that performs a task in our code.<br>
Add `+`<br>
Subtract `-`<br>
Multiply `*` <br>
Divide `/` <br>
Remainder `%` aka modulo- returns the number that remains after dividing the right evenly into the left digit.<br>
Concatenation- the process of appending one string to another.<br>

```
console.log('hi'+'ya') //Prints 'hiya'
console.log('middle'+ ' ' + 'space') //Prints 'middle space'
```

## Properties

All data types have properties that the developer can access for information about the data type. These properties are passed down to each instance of a data types.<br>
For example, **length** is a property that stores the # of characters in a _string_.

## Methods

Methods are actions we can perform.<br>
We use methods by appending(attaching) an instance with:

- a period(the dot operator)
- the name of the method
- () parenthesis
  <br>
  When writing `console.log`, we're calling the `.log()` method on the console object.

### Common Methods

`.toUpperCase()` method- returns a string in all capital letters.<br>
`.startsWith()`- accepts an argument and will return a boolean whether or not the string starts with the passed character.<br>

---

## Variables

Variables- hold variables; hold reusable data in a program and associate it with a name.<br>
Camel casing- when you group words into one, the 1st letter of the 1st word is lowercase and the 1st letter of every word after is uppercase. Ie. **camelCasingLooksLikeThis**<br>

### Rules for naming variables

- Variables can't start with numbers.
- Variable names are case sensitive, so `myName` and `myname` would be two different variables. **Try not to assign variable names with the same name but different cases.**
- Variable names can't be the same as keywords.

### Declaring a Variable

The `let` keyword signals that the variable you are declaring can be reassigned to a different value.<br>
**If you declare a variable without assigning a value it will be automatically initialized with a value of `undefined`**<br>
`let total=0;` <br>
To check if something is successfully assigned, log it to the console with the `console.log()` statement.<br>

The `const` keyword signals that the variable you are declaring can not be reassigned because its constant.<br>
**If you try to declare a constant variable without a value, you'll get a Syntax Error**<br>
`const name="Alicia";`
