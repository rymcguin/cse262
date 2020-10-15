Ryan McGuiness

# Date: September 27,2019
Racket
-
-lexical scope
```
(a.b)
(define a "Ryan")
(let ([a "Hello"][b "World"])
	(list a b))
```
commpiler
```
(string-length q)
//output 4
```
control flow
-
-outline
```
(if(condition)
	(affirm)
	(Negative))
```
```

(define x 3)
(if (> x 5)
	(+ x 9))
```



Map and Fold
-
- (map) - apply function to each variable
- (fold) - aggregate list into a single variable
- recursion 

```
(mapo(lambda(i)(i+1))lambda)
```

# Date September 30, 2019
- Applications/Racket v74/bin/raco
## Origin Story
- Alonzo Church - 1903-1995
- Alan Turing - 1912-1954
- Alonzo was interested in the theory of computation. And he want to figure out 

Alonzo=Lambda Calc  <--->  Alan Turing=Turing Machine(a-machine)

Idempotency
-
- a Funtion is idempotent if it is only a funtion of its inputs.
	- ie. pure and not-pure

pure
-
- sin(x)->y
	- sin(0)-0
- add(x,y)

not-pure
-
- rand()
- time()/now()
- U/I

## Lambda Calculus 
- expression-  defined by a name
```
expression = name | function | application ;
function = "†" , name , ".", expression;
application = expression, expression ;
```


