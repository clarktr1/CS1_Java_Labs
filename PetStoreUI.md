# Lab 7 Pet Store UI

## Starter Code

```
import java.util.*;
public class PetStoreUI
{
   public static void main(String[] args)
   {
      Scanner console = new Scanner(System.in);
      //code goes here
   }
}
```
This exercise will create an interactive application that will talk to a cat owner and attempt to sell some cat food.  Your program should emulate the process shown below.  This is ONE example using a specific set of data.  Review the instructions to see where variances occur based on needed decisions.
![fluffy's food](https://i.ibb.co/c3yqKYX/fluffy-food-1.png)

1) Please note:  If not specifically mentioned, all text shown above including flavor text, should be used.  Some of the text is used as a "prompt."  If you see data that has been previously entered and saved in a variable, that means you should use that variable in your message as well.  Don't "hard-code" my sample data.

2) Unless specifically stated, ALL String comparisons should be case-insensitive.

3) Declare a variable that can hold text called petName and get its value from the keyboard.

4) Display a greeting to the petName’s person. (See sample above.)

5) Declare a variable that can hold text called petGender and get its value from the keyboard. (See sample above.)

6) Display a prompt asking about the pet’s preference of food specific to the pet’s gender entered. (See sample above.)

7) Then display two prompts asking what kind of food does petName like.

* NOTE: Both prompts ask for numbers as responses. You must translate these responses to Boolean variables.

* Two responses means two Boolean variables.

* “can” equals TRUE, “regular” equals TRUE

8) Display a summary of the data entered. You must use the Boolean variables declared in Step 7.  You should also use logical operators.

9) Display a prompt asking how many containers of food are needed. (See sample above.)

10) Using the chart below, calculate and display the total cost of cat food.

|          |          | Cost per container |
|----------|----------|---------------------|
| Can      | Regular  |         1.0         |
| Can      | Premium  |        2.25         |
| Dry      | Regular  |        16.25        |
| Dry      | Premium  |        28.95        |


11) Display a prompt asking if the customer (cat owner) still wants to buy. You can use the words “yes” or “no” or their single letter abbreviations as valid responses.

12) Display a message based on the response. You can use the sample for a negative response.  If “yes”, use petName plus “thanks you and I thank you for your purchase.”
