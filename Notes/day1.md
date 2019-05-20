## ES6

- Prior to ES6, JS didn't support collecting variables

- Now we can right for loops

        for (let i = 0; i < arr.length; i++)
        
- Features

1) New methods for strings and arrays

2) Promises (for Async programming)

3) Maps and sets 

4) Generators, Proxies, WeakMaps (completely new)

## JavasScript ES6

- JS is just like a coffee barista. You give the computer an expression, and it returns a value just as you wish


### Values and Expression

        11
        
This is an expression and a value. **All values are expressions.**

        "Hamin" + " " + "Lee" + "Happy"
        
All the string elements are value, strings with operators(+ operator in this case)
 are not values, they are expressions.
       
### Values and Identity

**===** => test if two values are identical

**!==** => not

### Value Types

**String, Numbers, booleans** are example of JS **value** for **primitive**, used interchangeably.

### Reference Types

For **Arrays**, it generates its own **unique** array thus

        [2-1, 2, 2+1] === [1,2,3]
        [1,2,3] === [1, 2, 3]
        [1, 2, 3] === [1, 2, 3]
        
All following examples return **False**

### Floating

Numbers are represented internally as floating point.

Floating number => Binary(in Assembly)

Professional programmars almost never use Floating number for monetary amounts.

It has some deviation which is sensitive in monetary terms.

Say $11.11 => this will be represented as two numbers dollars and cents.\


## Basic Functions

- In JS functions are values.