# Example 3: Tricky

This example is a tricky one. Basically we want a monthly spend of £20 but we only want it for the last 2 years in a 4 year period.

### How To Do It

* We enter some information in the <mark style="color:blue;">Category</mark> and <mark style="color:blue;">Description</mark> and column. We shall choose _Spending_ in the <mark style="color:blue;">Type</mark> column.
* In the <mark style="color:blue;">Occurrences</mark> column we enter 24. This is the number of times that this item will happen between the dates we are about to enter
* In the <mark style="color:blue;">Start Date</mark> column we enter _1 January 2020_ (I could have picked any year). This means the first payment of £20 will be expected in January
* In the <mark style="color:blue;">End Date</mark> column we enter _31 December 2020_ (I could have picked any year). This means the last payment of £20 will be expected in December&#x20;
* In the <mark style="color:blue;">Over X Years</mark> column we enter _4_ because we want this pattern to repeat every 4 years
* In the <mark style="color:blue;">Starting Option</mark> column we enter _Start at Year 3_ because we want our monthly payment to not happen in the first 2 years and then only to happen in the last 2 years of a 4 year period
* In the <mark style="color:blue;">Amount</mark> column we enter _£20_ which is the amount for each instance

<details>

<summary>Reveal how to make the £20 monthly spend only happen in the FIRST 2 years</summary>

In the <mark style="color:blue;">Starting Option</mark> column we enter _Stop at Year 2_ instead of _Start at Year 3_. Note how  the stopping option means **at the end of the year**

</details>

### How it Looks in the Spreadsheet

![Monthly spend for the last 2 years of a 4 year period](<../../.gitbook/assets/Monthly 2 Out Of 4.png>)

### **The Schedule**

Year 1 and Year 2:\
_-- No payments at all --_\
\
Year 3 and Year 4:\
_January, February, March, April, May, June, July, August, September, October, November, December_

__
