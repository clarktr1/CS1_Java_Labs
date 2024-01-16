# Lab6 Bottles On The Wall

- OPEN BlueJ,
- CREATE a new BlueJ project titled BottlesOnTheWallAPP
- CREATE and open a new class,
- DELETE BlueJ's starter code, and
- TYPE in our code skeleton:
```

import java.util.*;

public class BottlesOnTheWallAPP
{
    public static void main(String[] args)
    {
        Scanner console = new Scanner(System.in);
        //code goes here
    }
 }

```
## Bottles on the Wall APP
You find yourself in a curious predicament – you can never remember how to sing the classic "99 bottles of <something> on the wall" song, but there's no way you're going to sing it all the way to the end to remember it – that would take way too long.  Luckily, you know how to code, and you could write a program to do it for you in much less time.

First, prompt the user, asking them to enter their age.  Iff (if and only if) they are over 20, ask them if they prefer beer or Coke (enter 1 for beer, or 2 for Coke).  Save their response into an integer called choice.

Next, make a new String variable called drink and, depending on the value of choice, set its value to either "beer" or "Coke".

The song will be sung with "99 bottles of beer on the wall" if they are over 20 and choose beer; if they're under 21 (or choose Coke), the song will be sung with "99 bottles of Coke on the wall".

Use concatenation whenever possible.  Sample program run below(user input shown after >>)

```
Enter your age (whole number only) >>> 52
Do you prefer beer or Coke? (enter 1 for beer, 2 for Coke) >>> 2


99 bottles of Coke on the wall
99 bottles of Coke
Take one down, pass it around, 98 bottles of Coke on the wall!
```
… all the way to the last verse (different than the others!):

```
1 bottle of Coke on the wall
1 bottle of Coke
Take it down, pass it around, zero bottles of Coke on the wall!
```
