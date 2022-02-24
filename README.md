> ---
> # This is currently a Work In Progress
> ### Please feel free to send me corrections and things to add if you want.
> ---

# A Javascript Mastery Pocket Book

A source of definitions and examples to get solid foundations knowledge and become a Senior Software Engineer.

### Disclaimer

This is not intended to be a course or a full list of methods or so.
Take this as a guide to test yourself about concepts you should have at least a surface understanding.

You will face yourself to be the most honest version of you:

- Understand where you are.
- Take note on what you need to know.
- Make a plan to get better by building solid foundations.
- As a rule of thumb: Consistency with low intensity is the key to avoid burnout.
- Practice and teach whatever you want to internalize, normally there's no other way.

## Index

### BRIEF INTRO

###### [AKA: Things you must know]

- Javascript and ECMAScript
- What's ECMA
- About ECMA-262 specification
- A scripting language?
- About ECMAScript
- About Javascript
- Understand the key differences
- Javascript engine
- Javascript runtime

- TODO: Versions highlights through time

---

### BASICS

###### [AKA: Strong foundations | Part One]

- Data Types
- Primitives
- Non Primitives

---

#### EVALUATE COMPLEXITY:

- Execution Context
- Call Stack
- Lexical Environment
- Hoisting
- Closures

---

#### USEFUL AND COMMON METHODS

[Strong foundations | Part One]

#### On Strings

- .toString (ES5)

#### On Arrays

- .map()
- .includes()

#### On Objects

### Categorize...

- toLowerCase()
- toUpperCase()
- Number()
- isNaN()
- Object.fromEntries()
- Object.fromValues()
- typeof - type of
- Object.keys(obj)
- Object.getOwnPropertyNames(obj)
- Object.getOwnPropertySymbols(obj)
- Object.hasOwnProperty()
- Object.size()
- Statements VS Expressions
- for
- for...in
- for...of
- Template strings
- .forEach()
- String and Array .length
- If statements
- functions
- arrow functions
- class
- prototype

### Javascript and ECMAScript

###### What's ECMA

**ECMA International** is a nonprofit standards organization for information and communication systems.
**ECMA** stands for _European Computer Manufacturers Association_ and was founded in 1961 to standarize computer systems in Europe. It changed it's name to **ECMA International** in 1994.

###### About ECMA-262 specification

This is a standard published by **ECMA International** and contains the specification for a general purpose scripting language. We could think of **ECMA-262** as _ECMAScript's reference number_.

ECMAScript is a programming language that falls into the category of Scripting Language by **_what it does_**.

###### A scripting language?

Is intended to only manipulate an external entity.
Basically, it needs an actor. An example could be a dog receiving a _sit_ order. You can tell it what to do, you don't perform the actual action.
You make the order, the part that you don't control is the brain of the dog, who interprets the order and takes the corresponding associated action in the dog's body.

###### About ECMAScript

ECMAScript is an object-oriented programming language originally designed to be used as a scripting language. This means that you can use it to manipulate, customize and automate the facilities of an **existing entity or system**.
ECMAScript is now a fully featured general-purpose programming language. Meaning that is now used both in frontend and backend. [Link to the specification details](https://tc39.es/ecma262/#sec-overview).

Note that since Javascript is a general purpose scripting language that conforms to the ECMAScript specification, is a good idea to understand a bit about this spec.

###### About Javascript

We could say that Javascript is technically a dialect of the ECMAScript language. A dialect derives most of it's lexicon and syntax from it's parent language, but deviates enough to deserver distinction.
Javascript mostly implements the ECMAScript specification as described in ECMA-262, but there are some differences.

###### Understand the key differences

By reading the **ECMAScript Specification** you will learn _how to create a scripting language_.
On the other half, reading the **Javascript Documentation** you learn _how to use a scripting language_

###### Javascript engine

A program or interpreter that understands and executes JavaScript code. These engines are commonly found in web browsers.
Google Chrome has it's V8 JavaScript Engine. SpiderMonkey in Mozilla Firefox and Chakra in Microsoft Edge. Each engine is like a language module for each browser, allowing them to support a certain subset of the JavaScript language.
A word on browser performance: some JavaScript engines are implemented in a most efficient way than others, this translates in fastest execution of the JavaScript code.

Be aware that browser engines actually implements a particular ECMAScript version. It's each companies engine developers that has to update their engines to the latests specifications of EMCAScript. This updates generally goes incrementally.

###### Javascript runtime
