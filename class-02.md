# HTML & CSS
## Chapter2: _Text_
### Heading & Paragraph Tags
```
<h1-6>          Headings
<p>             Paragraph
```
### Bold, Italic, & Emphasis Tags
```
<b>             Bold
<i>             Italic
<sup>           Superscript
<sub>           Subscript
<br />          Line Break
<hr />          Horizontal Rule
```
### Structural & Semantic Markup Tags
```
<strong>        Strong
<em>            Emphasis
<blockquote>    Long Quotation
<q>             Short Quotation
<abbr>          Abbreviation
<cite>          Citation
<dfn>           Definition
<address>       Address
<ins>           Insert
<del>           Delete
<s>             Strikethrough
```

## Chapter10: _Introducing CSS_
### Selector Examples & Meanings
```
*               Universal Selector
    Applies to all elements in the document

h1, h2, h3      Type Selector
    Matches element names

.note, p.note   Class Selector
    Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol

#introdutions   ID Selector
    Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol

li>a            Child Selector
    Matches an element that is a direct child of another

p a             Descendant Selector
    Matches an element that is a descendent of another specified element (not just a direct child of that element)

h1+p            Adjacent Sibling Selector
    Matches an element that is the next sibling of another

h1~p            General Sibling Selector
    Matches an element that is a sibling of another, although it does not have to be the directly preceding element
```
# Javascript & jQuery
## Chapter2: _Basic JavaScript Functions_
### Arithmetic Operators
```
+       Addition
    Adds one value to another

-       Subtraction
    Subtracts one value from another

/       Division
    Divides two values

*       Multiplication
    Multiplies two values using an asterisk (Note that this is not the letter x)

++      Increment
    Adds one to the current number

--      Decrement
    Subtracts one from the current number

%       Modulus
    Divides two values and returns the remainder
```
## Chapter4: _Decisions & Loops_
### Comparison Operators
```
==      Is Equal To
    Compares two values (numbers, strings, or Booleans) to see if they are the same

!=     Is Not Equal To
    Compares two values (numbers, strings, or Booleans) to see if they are *not* the same

===     Strict Equal To
    Compares two values to check that both the data type and value are the same

!==     Strict Not Equal To
    Compares two values to check tht both the data type and value are *not* the same

>       Greater Than
    Checks if the number ojn the left is *greater than* the number on the right

<       Less Than
    Checks if the number on the left is *less than* the number on the right

>=      Greater Than Or Equal To
    Checks if the number on the left is *greater than or equal to* the number on the right

<=      Less Than Or Equal To
    Checks if the number on the left is *less than or equal to* the number on the right
```
### Logical Operators
```
&&          Logical And
    Test more than one condition
        true && true returns true
        true && false returns false
        false && true returns false
        false && false returns false

||          Logical Or
    Tests at least one condition
        true || true returns true
        true || false returns true
        false || true returns true
        false || false returns false

!           Logical Not
    Takes a single Boolean value and inverts it
        !true returns false
        !false returns true