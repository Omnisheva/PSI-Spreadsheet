# At Your Own Risk

There are some hidden sheets where all the calculations are made and there are a couple of visible settings that are changeable but I don't recommend you do so unless you are super comfortable with Google Sheets and are pretty confident with how this spreadsheet actually functions

### Visible Settings

On the <mark style="background-color:yellow;">Budget Setup</mark> sheet there are two options called the Viewing Options on the right hand column. These refer to:

* The date following the last date on all budget graphs. If you change this the relevant graphs will stop at the month preceding the one you entered. The year doesn't matter for this.
* The other viewing option determines over how many years your budget repeats for the purposes of the graph displays. You can overwrite this however I strongly recommend you leave the formula as it is

```excel-formula
// Formula for viewing option year
=MAX($H$6:$H$999)
```

### Hidden Sheets

There are four hidden sheets and they are:

* <mark style="background-color:yellow;">Background - Plans</mark> this is the sheet that turns what you put in the <mark style="background-color:yellow;">Budget Setup</mark> sheet into actual numbers. You'll see the formula for the dates is pretty complex
* <mark style="background-color:yellow;">Background - Savings</mark> is essentially the same as <mark style="background-color:yellow;">Background - Plans</mark> but <mark style="background-color:yellow;"></mark> for your savings plan rather than your budget
* <mark style="background-color:yellow;">Background - Lists</mark> this is an assortment of helper calculations for all the sheets in the workbook. Each column header references what this list or parameter refers to.
* <mark style="background-color:yellow;">Background - Spending</mark> this has some helper calculations for the spending sheet that would have been awkward to put on the <mark style="background-color:yellow;">Background - Lists</mark> sheet
