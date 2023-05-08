## prompt 1- A function called "multiplication" that returns the product of the two input numbers
## unit test-prompt1-
Expect multiplication(1, 2) to be a number
Expect multiplication(1, 2) to be 2
Expect multiplication(1, -2) to be -1
Expect multiplication(a, 2) to be an error
## prompt 2- A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays
## unit test-prompt2-
Expect concatOdds([3, 2, 1], [9, 1, 1]) to be [1, 3, 9]
expect concatOdds([2, 2, 4], [6, 8, 10]) to be undefined
Expect concatOdds([], []) to be undefined
Expect concatOdds([1, 1, 1], [1, 1, 1]) to be [1]
Expect concatOdds([a], [b]) to be an error
## prompt 3- A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest
## functional test-prompt1-
When a user checks out with an empty cart, they should not be allowed to check out
When a user goes to check out, they should be asked if they want to create an account, or to log in, or check out as guest
When a user chooses to create an account, be asked information to create an account
When a user chooses to loggin, be asked to fill out account details
When a user chooses to check out as guest, they should be asked billing details