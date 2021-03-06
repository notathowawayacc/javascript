# INTRODUCTION TO JAVASCRIPT

## PREREQUISITES

- Computer running Linux or PiOS
- Email account
- [GitHub](https://github.com/signup) account
- [CodeAcademy](https://www.codecademy.com/) account
> You can use your Gmail or GitHub account to sign-in to CodeAcademy

## REQUIREMENTS

- Update and Upgrade OS
  ```bash
  sudo apt-get update && sudo apt-get upgrade -y
- Install git
  ```bash
  sudo apt-get install -y git && git --version
  ```
- Install VS Code
  ```bash
  sudo apt install code
  ```
- Install NodeJS
  ```bash
  curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
  ```
  ```bash
  sudo apt-get install -y nodejs && node --version
  ```
- Install Brave Browser
  ```bash
  sudo apt install -y apt-transport-https curl
  ```
  ```bash
  sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg
  ```
  ```bash
  echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list
  ```
  ```bash
  sudo apt update && sudo apt install -y brave-browser
  ```

## TABLE OF CONTENTS

- [1.1 INTRODUCTION](1_1-Introduction.md#intro-to-programming)
  * [COMPUTER SCIENCE](1_1-Introduction.md#computer-science)
  * [COMPUTER BASICS](1_1-Introduction.md#computer-basics)
  * [COMPUTER HARDWARE](1_1-Introduction.md#computer-hardware)
  * [PROGRAMMING TERMINOLOGY — SYNONYMS](1_1-Introduction.md#programming-terminology---synonyms)
  * [MACHINE LANGUAGE VS. PROGRAMMING LANGUAGE](1_1-Introduction.md#machine-language-vs-programming-language)
  * [PROGRAMMING PARADIGMS](1_1-Introduction.md#programming-paradigms)
  * [WRITING AND SAVING YOUR CODE](1_1-Introduction.md#writing-and-saving-your-code)
  * [COMPILING AND RUNNING YOUR CODE](1_1-Introduction.md#compiling-and-running-your-code)
- [2.1 CSS](2_1-CSS.md#css)
  * [WHAT IS CSS](2_1-CSS.md#what-is-css)
  * [HOW DOES CSS ACTUALLY WORK?](2_1-CSS.md#how-does-css-actually-work-)
  * [HOW TO APPLY YOUR CSS TO YOU HTML](2_1-CSS.md#how-to-apply-your-css-to-you-html)
  * [CSS SYNTAX](2_1-CSS.md#css-syntax)
  * [CSS DECLARATIONS](2_1-CSS.md#css-declarations)
    + [ELEMENT SELECTORS](2_1-CSS.md#element-selectors)
    + [CLASS SELECTORS](2_1-CSS.md#class-selectors)
    + [ID SELECTORS](2_1-CSS.md#id-selectors)
  * [THE BOX MODEL](2_1-CSS.md#the-box-model)
    + [BOX PROPERTIES](2_1-CSS.md#box-properties)
    + [WIDTH AND HEIGHT](2_1-CSS.md#width-and-height)
    + [PADDING](2_1-CSS.md#padding)
    + [BORDER](2_1-CSS.md#border)
    + [MARGIN](2_1-CSS.md#margin)
- [3.1 JAVASCRIPT](3_1-JavaScript.md#javascript)
  * [WHAT IS JAVASCRIPT?](3_1-JavaScript.md#what-is-javascript-)
  * [CONSOLE](3_1-JavaScript.md#console)
  * [COMMENTS](3_1-JavaScript.md#comments)
  * [DATA TYPES](3_1-JavaScript.md#data-types)
  * [ARITHMETIC OPERATORS](3_1-JavaScript.md#arithmetic-operators)
  * [STRING CONCATENATION](3_1-JavaScript.md#string-concatenation)
  * [PROPERTIES](3_1-JavaScript.md#properties)
  * [METHODS](3_1-JavaScript.md#methods)
  * [BUILT-IN OBJECTS](3_1-JavaScript.md#built-in-objects)
  * [REVIEW JAVASCRIPT](3_1-JavaScript.md#review)
- [3.2 VARIABLES](3_2-Variables.md#variables)
  * [VARIABLES](3_2-Variables.md#variables-1)
  * [CREATE A VARIABLE: VAR](3_2-Variables.md#create-a-variable--var)
  * [CREATE A VARIABLE: LET](3_2-Variables.md#create-a-variable--let)
  * [CREATE A VARIABLE: CONST](3_2-Variables.md#create-a-variable--const)
  * [MATHEMATICAL ASSIGNMENT OPERATORS](3_2-Variables.md#mathematical-assignment-operators)
  * [THE INCREMENT AND DECREMENT OPERATOR](3_2-Variables.md#the-increment-and-decrement-operator)
  * [STRING CONCATENATION WITH VARIABLES](3_2-Variables.md#string-concatenation-with-variables)
  * [STRING INTERPOLATION](3_2-Variables.md#string-interpolation)
  * [TYPEOF OPERATOR](3_2-Variables.md#typeof-operator)
  * [REVIEW VARIABLES](3_2-Variables.md#review-variables)
- [4.1 FUNCTIONS](4_1-Functions.md#functions)
  * [WHAT ARE FUNCTIONS?](4_1-Functions.md#what-are-functions-)
  * [FUNCTION DECLARATIONS](4_1-Functions.md#function-declarations)
  * [CALLING A FUNCTION](4_1-Functions.md#calling-a-function)
  * [PARAMETERS AND ARGUMENTS](4_1-Functions.md#parameters-and-arguments)
  * [DEFAULT PARAMETERS](4_1-Functions.md#default-parameters)
  * [RETURN](4_1-Functions.md#return)
  * [HELPER FUNCTIONS](4_1-Functions.md#helper-functions)
  * [FUNCTION EXPRESSIONS](4_1-Functions.md#function-expressions)
  * [ARROW FUNCTIONS](4_1-Functions.md#arrow-functions)
  * [CONCISE BODY ARROW FUNCTIONS](4_1-Functions.md#concise-body-arrow-functions)
  * [REVIEW FUNCTIONS](4_1-Functions.md#review-functions)
- [5.1 ARRAYS](5_1-Arrays.md#arrays)
  * [ARRAYS](5_1-Arrays.md#arrays-1)
  * [CREATE AN ARRAY](5_1-Arrays.md#create-an-array)
  * [ACCESSING ELEMENTS](5_1-Arrays.md#accessing-elements)
  * [UPDATE ELEMENTS](5_1-Arrays.md#update-elements)
  * [ARRAYS WITH LET AND CONST](5_1-Arrays.md#arrays-with-let-and-const)
  * [THE .LENGTH PROPERTY](5_1-Arrays.md#the-length-property)
  * [THE .PUSH() METHOD](5_1-Arrays.md#the-push---method)
  * [THE .POP() METHOD](5_1-Arrays.md#the-pop---method)
  * [MORE ARRAY METHODS](5_1-Arrays.md#more-array-methods)
  * [ARRAYS AND FUNCTIONS](5_1-Arrays.md#arrays-and-functions)
  * [NESTED ARRAYS](5_1-Arrays.md#nested-arrays)
  * [REVIEW ARRAYS](5_1-Arrays.md#review-arrays)
- [5.2 SCOPE](5_2-Scope.md#scope)
  * [SCOPE](5_2-Scope.md#scope-1)
  * [BLOCKS AND SCOPE](5_2-Scope.md#blocks-and-scope)
  * [GLOBAL SCOPE](5_2-Scope.md#global-scope)
  * [BLOCK SCOPE](5_2-Scope.md#block-scope)
  * [SCOPE POLLUTION](5_2-Scope.md#scope-pollution)
  * [PRACTICE GOOD SCOPING](5_2-Scope.md#practice-good-scoping)
  * [REVIEW SCOPE](5_2-Scope.md#review--scope)
- [6.1 LOOPS](6_1-Loops.md#loops)
  * [LOOPS](6_1-Loops.md#loops-1)
  * [REPEATING TASKS MANUALLY](6_1-Loops.md#repeating-tasks-manually)
  * [THE FOR LOOP](6_1-Loops.md#the-for-loop)
  * [LOOPING IN REVERSE](6_1-Loops.md#looping-in-reverse)
  * [LOOPING THROUGH ARRAYS](6_1-Loops.md#looping-through-arrays)
  * [NESTED LOOPS](6_1-Loops.md#nested-loops)
  * [THE WHILE LOOP](6_1-Loops.md#the-while-loop)
  * [DO...WHILE STATEMENTS](6_1-Loops.md#dowhile-statements)
  * [THE BREAK KEYWORD](6_1-Loops.md#the-break-keyword)
  * [REVIEW LOOPS](6_1-Loops.md#review)
- [7.1 OBJECTS](7_1-Objects.md#objects)
  * [INTRODUCTION TO OBJECTS](7_1-Objects.md#introduction-to-objects)
  * [CREATING OBJECT LITERALS](7_1-Objects.md#creating-object-literals)
  * [ACCESSING PROPERTIES](7_1-Objects.md#accessing-properties)
  * [BRACKET NOTATION](7_1-Objects.md#bracket-notation)
  * [PROPERTY ASSIGNMENT](7_1-Objects.md#property-assignment)
  * [METHODS](7_1-Objects.md#methods)
  * [NESTED OBJECTS](7_1-Objects.md#nested-objects)
  * [PASS BY REFERENCE](7_1-Objects.md#pass-by-reference)
  * [LOOPING THROUGH OBJECTS](7_1-Objects.md#looping-through-objects)
  * [REVIEW OBJECTS](7_1-Objects.md#review)