# JavaScript (JS) Intro
JavaScript (JS) is a lightweight programming language with first class functions

## Interacting
- functions to interact with a user: **alert, prompt and confirm.**
### Alert
- Alert shows a message and waits for the user to press “OK”.
### Prompts
- Prompts accept two arguments: **title (The text to show the visitor) & default (the initial value for the input field)**
With prompts, it'll shows a modal window with a text message, an input field for the visitor, and the buttons OK or Cancel.
> The visitor can type something in the prompt input field and press OK. Then we get another text in the result. Or they can cancel the input by pressing Cancel or hitting the Esc key, then we get null as the result. The call to prompt returns the text from the input field or null if the input was canceled.
### Confirm
- Confirm shows a modal window with a question and two buttons: OK and Cancel. The result is _true_ if OK is pressed and _false_ if otherwise.

## Summary
- Alert shows a message.
- Prompt shows a message asking the user to input text. It returns the text or, if Cancel button or Esc is clicked, null.
- Confirm shows a message and waits for the user to press “OK” or “Cancel”. It returns true for OK and false for Cancel or Esc.
- All these methods are modal: they pause script execution and don’t allow the visitor to interact with the rest of the page until the window has been dismissed.

# Variables

## JavaScript variables:
- var
- let
- const

**Variables are containers for storing data (values)**

### All JavaScript variables must be identified with unique names.

These unique names are called _identifiers_
- Identifiers can be names (like x and y) or (age, sum, totalVolume).

### The general rules for constructing names for variables (unique identifiers) are:
- Names can contain letters, digits, underscores, and dollar signs.
- Names must begin with a letter
- Names can also begin with $ and _ (but we will not use it in this tutorial)
- Names are case sensitive (y and Y are different variables)
- Reserved words (like JavaScript keywords) cannot be used as names

-In JS, the queal sign is an "assignment" operator, not an "equal to" operator.
_The queal to operator is written as "==" in JS_

## JS Data
JavaScript variables can hold numbers like 100 and text values like "John Doe".
In programming, text values are called text strings.
Strings are written inside double or single quotes. Numbers are written without quotes.
If you put a number in quotes, it will be treated as a text string.
> Examples:
> var pi = 3.14;
> var person = "John Doe";
> var answer = 'Yes I am!';

- Creating a variable in JavaScript is called "declaring" a variable.
- You declare a JavaScript variable with the var keyword: var userName
- To assign value to the variable, use the equal sign
- var userName = "Brittani";


Creating a variable in JavaScript is called "declaring" a variable.
You declare a JavaScript variable with the var keyword:
var person = "John Doe", carName = "Volvo", price = 200;