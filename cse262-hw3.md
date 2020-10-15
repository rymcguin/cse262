
# Homework 3

Question 1
-
```
a. 	String = '"', {all_charachters-'"'-"\"}| "\", '"';

b. 	Comments = "/*", {all_characters}, "*/" | "//", {all_characters}, \n;

	dot = ".com" | ".net" | ".org" | ".edu" | ".gov" ;
c. 	email = {all_characters - symbols}, "@", {all_characters - symbols}, dot ;

	number = 0|1|2|3|4|5|6|7|8|9;
d.	US phone = number-0-1, number, number, "-", number-1, number, number, "-", number, number, number, number;

e.	binary = {0|1};
	octal = 0o, {0|1|2|3|4|5|6|7};
	Decimal = {0|1|2|3|4|5|6|7|8|9|"."};
	Hexadecimal = {Decimal|A|B|C|D|E};

```
Question 2
-
- Lexical error is a sequence of characters that does not match the pattern of any token.
- Sytax error is a mistake in the sequence of characters or tokens that is intended to be written in compile-time.
- A static semantic error is when the tokens dont match the grammar of the language.
- An ownership error is when the owner variable is outof bounds or doesnt exist for a value.
- A lifetime error is made when rust doesnt infer the right lifetimes. 

Question 3
- 
- the maximum size of usize is 248. In the event of an arithmetic overflow, is when the arethmetic aoperation is bigger than the storage of the variable it is being set equal to. 

Question4
-
- It is difficult to debug code, becasue error messages sometimes times do not give an full enough expination, or with OOP the real error could be in a completly different file. Personally I comment out portions of code and test each part individually to find errors faster by searching smaller areas at a time. The bugs revealed by test are exceptions. If the wrong charactes are entered our passed through then the code could fail. Test helps find these errors. Errors that cannot be caught are ones made by that come from people messing with your public variables. 

Question 5 
-
-Image attached

Question Image attached