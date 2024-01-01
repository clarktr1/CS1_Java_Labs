# Lab 4 NutsAndBolts

## Instructions:
- OPEN BlueJ,
- CREATE a new BlueJ project titled NutsAndBoltsAPP in your Computer Science folder (H:\Computer Science),
- CREATE and open a new class,
- DELETE BlueJ's starter code, and
TYPE in our code skeleton:
```
//Name:
//Period:
import java.util.*;

public class NutsAndBoltsAPP
{
    public static void main(String[] args)
    {
        Scanner console = new Scanner(System.in);
        //code goes here
    }
}
```

## Nuts and Bolts APP
You run an online hardware store specializing in nuts, bolts and washers.  Your store has the following items at the following prices:

- Bolts – 5 cents each
- Nuts – 3 cents each
- Washers – 1 cent each
Write a program that asks the user for the number of bolts, nuts, and washers they wish to purchase and then calculates and prints out the total (save each into its own variable).

As an added feature, your program checks the user's order. A correct order must have:

- at least as many nuts as bolts
- at least twice as many washers as bolts
…otherwise, the order has an error.  Use boolean variables to store whether a user's order has an error.  Boolean variables can store values true and false, but can also be initialized using the value of a boolean expression.  Example:
```
int apples = 12;
boolean isAboveZero = (apples > 0);
//round brackets not required but may be more readable
```
Iff (if and only if) the order has an error, the program prints "Check order: too few nuts" or "Check order: too few washers" (as appropriate).  Iff there are no errors, the program should print "Order OK!".

In all cases, the total price in cents is printed (you can warn the buyer about possible errors, but you still want to make the sale!).  Below are sample runs of the program, use them to test your code:
```
Number of bolts >>> 12
Number of nuts >>> 8
Number of washers >>> 21

Warning! Check order: too few nuts
Warning! Check order: too few washers

Total cost (in cents) >>> 105
```
and another...
```
Number of bolts >>> 32
Number of nuts >>> 32
Number of washers >>> 356

Order OK!

Total cost (in cents) >>> 612
```
