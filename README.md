# Python

The command palette.

Some of my favorites:

- Esc will take you into command mode where you can navigate around your notebook with arrow keys.
While in command mode:
- A to insert a new cell above the current cell, B to insert a new cell below.
M to change the current cell to Markdown, Y to change it back to code
- D + D (press the key twice) to delete the current cell
- Enter will take you from command mode back into edit mode for the given cell.
- Shift + Tab will show you the Docstring (documentation) for the the object you have just typed in a code cell - you can keep pressing this short cut to cycle through a few modes of documentation.
- Ctrl + Shift + - will split the current cell into two from where your cursor is.
- Esc + F Find and replace on your code but not the outputs.
Esc + O Toggle cell output.
Select Multiple Cells:
Shift + J or Shift + Down selects the next sell in a downwards direction. You can also select sells in an upwards direction by using Shift + K or Shift + Up.
Once cells are selected, you can then delete / copy / cut / paste / run them as a batch. This is helpful when you need to move parts of a notebook.
You can also use Shift + M to merge multiple cells.


- The triple quotes are used to span the string across multiple lines. For example, all the following are legal-```
word = 'word'sentence = "This is a sentence."paragraph = """This is a paragraph. It ismade up of multiple lines and sentences."""

```

> >  ss
> > 
> > 
> > 



- Python does not have multiple-line commenting feature. You have to comment each line individually as follows-

*s*
`
dsds **

1. 1. ![]()



1. ss
2. dssds
`


`	# This is a comment.	# This is a comment, too.	# This is a comment, too.	# I said that already.	`
	
[]()


`sdsd`


 a=b=c=1
 
 Python Arithmetic OperatorsAssume variable a holds the value 10 and variable b holds the value 21, then-  OperatorDescription Example+ AdditionAdds values on either side of the operator.a + b = 31- SubtractionSubtracts right hand operand from left hand operand.a – b = -11* MultiplicationMultiplies values on either side of the operatora * b = 210/ DivisionDivides left hand operand by right hand operandb / a = 2.1% ModulusDivides left hand operand by right hand operand and returns remainderb%a=1** ExponentPerforms exponential (power) calculation on operatorsa**b =10 to the power 20



//Floor Division - The division of operands where the result is the quotient in which the digits after the decimal point are removed.


a = 21b = 10c=0c=a+bprint ("Line 1 - Value of c is ", c)


```{r}
a = 10b = 20list = [1, 2, 3, 4, 5 ]if ( a in list ):print ("Line 1 - a is available in the given list")else:   print ("Line 1 - a is not available in the given list")
   
   
```

```
**Exponentiation (raise to the power)~ +-Ccomplement, unary plus and minus (method names for the last two are +@ and -@)* / % //Multiply, divide, modulo and floor division+-Addition and subtraction>> <<Right and left bitwise shift&Bitwise 'AND'^|Bitwise exclusive `OR' and regular `OR'<= < > >=Comparison operators<> == !=Equality operators40 
Operator precedence affects the evaluation of an an expression.For example, x = 7 + 3 * 2; here, x is assigned 13, not 20 because the operator * has higher precedence than +, so it first multiplies 3*2 and then is added to 7.Here, the operators with the highest precedence appear at the top of the table, those with the lowest appear at the bottom.ExamplePython 3= %= /= //= -= += *= **=Assignment operatorsis is notIdentity operatorsin not inMembership operatorsnot or andLogical operators
```

```
if expression1:
   statement(s)
elif expression2:
   statement(s)
elif expression3:
   statement(s)
else:
   statement(s)
   
   
   
 
 if expression1:   statement(s)   if expression2:      statement(s)   elif expression3:      statement(s)   else      statement(s)elif expression4:   statement(s)else:   statement(s)

```


```

loops


The for statement in Python has the ability to iterate over the items of any sequence, such as a list or a string.

for iterating_var in sequence: statements(s)


```

```
SyntaxThe syntax for a nested while loop statement in Python programming language is as follows-A final note on loop nesting is that you can put any type of loop inside any other type of loop. For example a for loop can be inside a while loop or vice versa.ExampleThe following program uses a nested-for loop to display multiplication tables from 1-10.59Python 3#!/usr/bin/python3 numbers=[11,33,55,39,55,75,37,21,23,41,13] for num in numbers:if num%2==0:print ('the list contains an even number') breakelse:    print ('the list doesnot contain even number')      the list does not contain even number    for iterating_var in sequence: for iterating_var in sequence:      statements(s)   statements(s)while expression:   while expression:      statement(s)   statement(s)

```
	
```	
	import sys
for i in range(1,11):
  for j in range(1,11):
    k = i * j 
    print(k, end= 'ss')
    
print()

 Last print() will be executed at the end of inner for loop.
 When the above code is executed, it produces the following result −
 
 ```
 
```
  
The pass statement is a null operation; nothing happens when it executes. The pass statement is also useful in places where your code will eventually go, but has not been written yet i.e. in stubs).
 
 
 
 
 
 
 
 - Number data types store numeric values. They are immutable data types. This means, changing the value of a number data type results in a newly allocated object.Number objects are created when you assign a value to them. For example-




```
FunctionReturns ( Description )abs(x)The absolute value of x: the (positive) distance between x and zero.ceil(x)The ceiling of x: the smallest integer not less than x.cmp(x, y)-1 if x < y, 0 if x == y, or 1 if x > y. Deprecated in Python 3; Instead use return (x>y)-(x<y).exp(x)The exponential of x: exfabs(x)The absolute value of x.floor(x)The floor of x: the largest integer not greater than x.log(x)The natural logarithm of x, for x> 0.log10(x)The base-10 logarithm of x for x> 0.max(x1, x2,...)The largest of its arguments: the value closest to positive infinity.min(x1, x2,...)The smallest of its arguments: the value closest to negative infinity.modf(x)The fractional and integer parts of x in a two-item tuple. Both parts have the same sign as x. The integer part is returned as a float.pow(x, y)The value of x**y.round(x [,n])x rounded to n digits from the decimal point. Python rounds away from zero as a tie-breaker: round(0.5) is 1.0 and round(-0.5) is - 1.0.sqrt(x)



```


FunctionDescriptionchoice(seq)A random item from a list, tuple, or string.randrange ([start,] stop [,step])A randomly selected element from range(start, stop, step).random()A random float r, such that 0 is less than or equal to r and r is less than 1.seed([x])Sets the integer starting value used in generating random numbers. Call this function before calling any other random module function. Returns None.shuffle(lst)Randomizes the items of a list in place. Returns None.uniform(x, y) A random float r, such that x is less than or equal to r and r is less than y.




 