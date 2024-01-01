# Lab 3 Basic Calculator
## Instructions:
- OPEN BlueJ,
- CREATE a new BlueJ project titled CalculatorAPP in your Computer Science folder (H:\Computer Science),
- CREATE and open a new class,
- DELETE BlueJ's starter code, and
TYPE in our code skeleton:
```
//Name:
//Period:

import java.util.*;
public class CalculatorAPP
{
    public static void main(String[] args)
    {
        Scanner console = new Scanner(System.in);
        //code goes here
    }
}
``` 

## Calculator APP
Write a program that will create a text-based calculator app.  First, print a text-based "menu" to the console (screen) that will show users the choices of operations, like the following:
```
1 – addition (+)
2 – subtraction (-)
3 – multiplication (*)
4 – division (/)
5 – modulus (%)
```

`Enter the number of your desired operation from the menu above >>> 1`
- Save the user's choice into an integer variable called operation.  After the user chooses the desired operation, ask them to input the values for the calculation:         

```
Enter first number >>> 2
Enter second number >>> 4
```
- Finally, print out the variables and the result of the calculation (based on which operation was selected):

`2 + 4 = 6`
         
