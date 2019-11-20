# HW2
# DiscreteMathematics Homework 2

## DNF Converter  
### input 
- A propositional formula string connected with only 'and'/ 'or'/ 'not' and it will be seperated by white space and bracket '('.
- The variable should be a form of 'an' and n is a natural number.
- example 
```
(and a1 a2 a3 (and a3 a5) (or a3 a15))
```
### output
- print out the numbers of variable number (variable number is n of 'an').
- if the variables is connected with 'and' gate, put '\n' between the numbers.
- if the variables is connected with 'or' gate, put white space between the numbers.
- if the variable is in 'not' gate, the number will be printed with negative number like -n (n is natural number).

- print '0' if printing the formula numbers ends.
- print the solution the formula supposing the formula is 'true' and print out 'USAT' if the formula cannot make the solution.

-example
```
input : (or a1 a2 (and a3 (not a5)))
1
2
3 -5
0
1 2 3 -5
```

## How to build?
```
$ make
```

## How to execute?
```
$ ./run
> input : (propositional formula)

```  

