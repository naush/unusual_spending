## Kata Workshop

### Problem

You work at a credit card company and as a value-add they want to start providing alerts to users when their spending in any particular category is higher than usual.

* A Payment is a simple value object with a price, description, and category
* A Category is an enumerable type of a collection of things like "entertainment", "restaurants", and "golf"
* For a given userId, fetch the payments for the current month and the previous month
* Compare the total amount paid for the each month, grouped by category; filter down to the categories for which the user spent at least 50% more this month than last month
* Compose an e-mail message to the user that lists the categories for which spending was unusually high, with a subject like "Unusual spending of $1076 detected!" and this body:

### Examples

```
Hello card user!

We have detected unusually high spending on your card in these categories:

* You spent $148 on groceries
* You spent $928 on travel

Love,

The Credit Card Company
```

### Learning Outcomes

* [The Four-Phase Test](https://thoughtbot.com/blog/four-phase-test)
* [Three Rules of TDD](https://blog.gowtham-sai.com/three-laws-of-tdd-a84dd5204eae)
* Test Doubles
* Inside-Out and Outside-In Development

### Resources

* [Unusual Spending Kata by testdouble](https://github.com/testdouble/contributing-tests/wiki/Unusual-Spending-Kata)
