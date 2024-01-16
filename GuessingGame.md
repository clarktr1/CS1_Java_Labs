# Lab 6 Guessing Game

## Instructions
- OPEN BlueJ,
- CREATE a new BlueJ project titled GuessingGameAPP in your Computer Science folder (H:\Computer Science),
- CREATE and open a new class,
- DELETE BlueJ's starter code, and
- TYPE in our code skeleton:
```
import java.util.*;

public class GuessingGameAPP
{
    public static void main(String[] args)
    {
        Scanner console = new Scanner(System.in);
        //code goes here
    }
}
```

A while loop is very much like an if statement, except that the code inside the code block (between the curly brackets) will continue to run while the test condition is true.  Example syntax:
```
int i = 0;
while (i < 50)   //will execute while i is less than 50
{
     System.out.print(i + " ");
     i = i + 1;   //can also be written as i++
}
```

## Guessing Game APP
This is the most complex program you will write to date.  If you immediately start coding without a solid understanding of how to proceed, you could find yourself wasting significant time on a solution that isn't remotely feasible. 

Before you begin, write out (by hand, in Word, in comments – however you prefer) your plan prior to coding.  This process is known as "pseudocoding", or writing out your algorithm in something code-like.  Example of pseudocode:


if the user guesses the correct number

     print "Congratulations!  You win"

Create a program that will allow the user to play a number guessing game.  First, declare an integer variable called guesses – the number of guesses a player gets before they lose (7 is a good number to start with).  Next, generate a random number* between 1 and 1000, and save it into an integer variable called number.  Prompt the user, asking them to enter a guess (a number from 1 to 1000.

Your program should then tell them if they guessed correctly.  If they didn't, tell them if they were too high or too low.  Allow them to guess again, repeating this process until they either guess the number correctly (and win) or run out of guesses (and lose). 

Check out the following video to get a sample run.
[Guessing Game Video](https://www.youtube.com/watch?v=3xs0DtApO6c)

To create a random number, paste the following code.
```
Random randomGen = new Random(); //you only need to do this once!

int number = randomGen.nextInt(1000) + 1;

/* NOTE – every time you run your program, the piece of code randomGen.nextInt(1000) will
generate a new random number which is then saved into the variable number.  You DON'T want to make a new random
number each time our user guesses – just once per run of the game! */
