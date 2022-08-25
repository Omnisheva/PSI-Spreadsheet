# Seeing Account Balances

Once you have a budget and are adding in transactions and all the rest you'll want to see what your current account balances are and how close you are to your various goals. Well here is where you can do all that. Head on over to the <mark style="background-color:yellow;">Account Overview</mark> sheet and see what is there

### The Basics

Here you are presented with a big table with all of your accounts listed and mostly self explanatory column names. On the right hand side of the table however, there are 2 columns with a blue halo saying _WHAT IF_. The long and short of this is:

* The left hand part of the table refers to your accounts **as they are now**
* The _WHAT IF_ section refers to your accounts **as they could be in the future**

The right hand grey column contains some overall statistics such as _net worth_ but also contains a couple of settings that control how the _WHAT IF_ section works

### Left Hand Side of the Table

Starting off with the most straight forward aspects of this sheet. The left hand side of  the table consists of:

* The <mark style="color:blue;">Account</mark> column, which is the category name of the account
* The <mark style="color:blue;">Type</mark> column, which says whether it is a savings, investment or credit account
* The <mark style="color:blue;">First Balance</mark> column which means different things for different account types
  * For _savings_ and _investments_ this is the starting balance of it before using this spreadsheet
  * For _credit_ this is the total amount borrowed (even if you borrowed more later)
* The <mark style="color:blue;">Interest Rate</mark> column contains the interest rate for _saving_ and _investment_ accounts but **not  for credit accounts**
* The <mark style="color:blue;">Added To Date</mark> column which means different things for different account types
  * For _savings_ and _investments_ this is the total amount recorded within the <mark style="background-color:yellow;">Transactions</mark> sheet
  * For _credit_ this is the total amount of the credit account paid to date
* The <mark style="color:blue;">Current Balance</mark> column shows the total value of that account as it is today

<details>

<summary>Why don't you want interest rate for credit accounts</summary>

I decided not to do interest calculations for credit accounts because there may be weird and wonderful mechanisms of credit that may be offered and it could possibly miscalculate because of that. It also as a by-product forces you to be more active around recording losses to interest which might be the motivation to get them gone!

</details>

### Right Hand Grey Column

The _Net Worth_ stat is self explanatory so we jump straight to the next section where it asks you for a choice from a list and a date. Here is what that is about

* The _Based On_ What If parameter is a drop down that will affect how the _WHAT IF_ section calculates your possible future balances or possible future dates when you'll achieve your accounts goal. The three options are:
  * _Plans_. Here the _WHAT IF_ section will assume you hit your **budgets savings goal exactly** from today onwards
  * _Last 12 Months_. Here the _WHAT IF_ section will assume you hit the average savings rate for that account that you achieved over the last year from today onwards
  * _All Time_. Here the _WHAT IF_ section will assume you hit the average savings rate for that account that you achieved since you started using this spreadsheet from today onwards
* The _Future Date_ What If parameter is a date you can offer the spreadsheet. The _WHAT IF_ section will take this date and the option you chose in the _Based On_ What If parameter and for each account will calculate what the **account's balance would be** on that date

### What If Section of Table

The infamous _WHAT IF_ section of the table contains two columns whose explanations are pretty straight forward

* The <mark style="color:blue;">Future Balance</mark> column is what the balance of this account would be:
  * If you saved according to the option chosen in the _Based On_ What If parameter
  * On the date you chose in the _Future Date_ What If parameter
* The <mark style="color:blue;">Date Goal Hit</mark> column is the date you can expect to achieve your accounts goal if you saved according to the option chosen in the _Based On_ What If parameter
