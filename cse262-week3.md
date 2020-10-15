# Extended Backus-Naurr Form(EBNF)
- specification language for defining grammars
- 


# Date September 11, 2019
## EBNF
- Specifies **production rules** that define a grammar

 ## Production Rules
- defines each statement of grammar
```
"let _ x = 3 + 24;"
```
```
Program = {statement};
Statement = VariableDef "=", Expression, ";" ;
VariableDef = "let _", {Alphas};
Expression = Number, Operator, Number;
Number = {Digit};

```
The way it works:
1. start at let & program.
1. Passes IF:  all characters consumed & productions satisfied 
1. Fails IF: cant match any production || matches, but has left-overs
1. 

_ expresion, ";" ;  - if expression has ";" then it works

1

	