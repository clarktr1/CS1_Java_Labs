# Lab 2 Car Loan

## Instructions:
- OPEN BlueJ,
- CREATE a new BlueJ project titled CarLoanAPP in your Computer Science folder (H:\Computer Science),
- CREATE and open a new class,
- DELETE BlueJ's starter code, and
- TYPE in our code skeleton:
```
//Name:
//Period:

public class CarLoanAPP
{
    public static void main(String[] args)
    {
        //code goes here
    }
}
```
At some point in your life, you will have to buy a car. It's a scary proposition if you're unprepared.  That's why you are taking the time and writing an app to calculate an approximate car payment.

- Create a variable to store the "retail price" of the car.  This amount will include taxes and fees.  (When we are dealing with money, it's best to use data type double variables.)

- Create two more variables, one for the amount of the "trade-in" and your "down payment".  A trade-in is the car you are going to exchange for the one you're buying.  It has a value and the dealership will give you a value for it.  There may be some haggling over this value.  The down payment is how much cash (or a check) you intend to give the dealership in addition to the trade.

- Create a variable that is the "financed amount" of the car.  This is calculated by taking the retail price of the car and subtracting the trade-in value AND down payment.

- Create a variable that contains how much "interest" you are going to have to pay.  Best guess is to use about $800 per $10K borrowed.  We are not ready to do a complex calculation of this nature.  So, we will use our best guess.

- We have to add the interest to the financed amount of the car; create a "total financed" variable to hold this amount.

- Finally, in order to calculate the monthly payment, we need to know how many "months" to divide into the total financed amount.

- Print how many months and what the monthly payment is.

- Experiment with this calculation by altering the variables.  See how the payment fluctuates by increasing or decreasing the months of the loan.  Alter how much the car costs to see if perhaps you can afford the nicer car.  Maybe you can afford a larger down payment to lower the monthly payments?

See below for sample output.

CAR LOAN PAYMENT APP
```
Retail price of car $25000.0
    Trade-in value   (2000.0)
    Down payment     (3000.0)
Amount to finance   $20000.0

Interest paid         1600.0

Total financing     $21600.0

MONTHLY PAYMENT     $  360.0
spread out over 60 months
```
