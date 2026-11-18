# Exercise 2: ATM Withdrawal Algorithm

## 1. Understanding the Problem

The problem is to withdraw money from a bank account using an ATM. The ATM must check the card, verify the PIN, confirm that enough money is available, and dispense the requested amount.

## 2. Step-by-Step Algorithm

1. Insert the ATM card into the ATM.
2. The ATM reads the card.
3. Check whether the card is valid.
4. If the card is invalid or cannot be read, display an error message and stop the transaction.
5. If the card is valid, ask the user to enter their PIN.
6. Verify the PIN.
7. If the PIN is incorrect, display an error message and allow another attempt, subject to the bank's security limits.
8. If the PIN is correct, display the available transaction options.
9. Select the withdrawal option.
10. Enter the amount of money to withdraw.
11. Check whether the account has enough money.
12. If the account balance is insufficient, display an insufficient balance message and cancel the withdrawal.
13. Check whether the ATM has enough cash.
14. If the ATM does not have enough cash, display an appropriate message and cancel the withdrawal.
15. If all checks are successful, process the withdrawal and update the account balance.
16. Dispense the requested cash.
17. Offer a receipt if the user wants one.
18. Return the ATM card if it has not already been returned.
19. Display a successful transaction message.

## 3. Error Handling

| Problem | ATM Response |
|---|---|
| Card cannot be read or is invalid | Display an error message and stop the transaction. |
| Incorrect PIN | Display an error and allow another attempt within the security limit. |
| Insufficient account balance | Display an insufficient balance message and do not dispense cash. |
| Insufficient ATM cash | Inform the user and cancel the withdrawal. |
| Transaction failure | Display a failure message and ensure the account is not incorrectly debited. |

## 4. Difference Between Problem, Algorithm and Program

**Problem:** The task that needs to be solved. In this case, withdrawing money from a bank account using an ATM.

**Algorithm:** A clear, ordered set of instructions for solving the problem.

**Program:** The actual computer code written to make the ATM follow the algorithm.

## 5. Expected Result

The user receives the requested cash only when the card is valid, the PIN is correct, the account has enough money, the ATM has enough cash, and the transaction succeeds.

## 6. Lesson Learned

An algorithm gives a computer clear instructions. It must also consider possible errors so that the system can respond safely when something goes wrong.