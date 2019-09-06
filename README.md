### Challenge

Create a function `makeChangeAsString(fromAmount:withCost:)` that takes two `Doubles` as parameters - `fromAmount`(the amount given to pay for the purchase) and `withCost`(how much the item costs) and returns a `String` that details the total amount of change returned _and_ the quantity and type of each denomination returned (in dollars, quarters, dimes, nickels and pennies).

#####Example:

`makeChangeAsString(fromAmount: 5.00, withCost: 2.15)  // returns "Your change is $2.85. That is 2 dollars, 3 quarters, 1 dime, 0 nickels and 0 pennies."`

`makeChangeAsString(fromAmount: 10.00, withCost: 2.38) // returns "Your change is $7.62. That is 7 dollars, 2 quarters, 1 dime, 0 nickels and 2 pennies."
`

Here are the overall [instructions for code challenges](https://github.com/LambdaSchool/ios-code-challenge-instructions). Before you begin, fork and clone this repo and work through your solution in the included starter playground file. When you're done, **Please make sure to save and push all your work, and submit a Pull Request. Don't forget tag your TL so they can review your submission!**