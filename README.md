# BalanceNSettle
BalanceNSettle is a C++ program that helps in minimizing cash flow among a group of people who have borrowed money from each other. This program calculates the minimum number of transactions required to settle all debts, ensuring that the least amount of money changes hands.

Features

-Determines the net amount to be settled by each person.

-Finds the minimum cash flow to settle all debts.

-Outputs the transactions required to achieve the settlement.

Functionality Explanation

-findMinIndex Function: Finds the index of the person with the minimum net amount.

-findMaxIndex Function: Finds the index of the person with the maximum net amount.

-minOfTwo Function: Returns the smaller of two values.

-settleAmounts Function: Recursively settles amounts between people by finding the minimum amount to be transferred and updating the net amounts.

-calculateMinCashFlow Function: Calculates the net amount to be settled by each person and calls settleAmounts to determine and display the required transactions.
