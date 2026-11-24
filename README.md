# Decorator Pattern

## Description of the following methods

1. showAccountType() - Either returns "Savings Account", "GSave" or "UpSave"
2. getInterestRate() - Either returns 1% for Savings Account; 2.5% for GSave; 4.0%
UpSave
3. getBalance() - Returns the balance of the account set.
4. showBenefits() - Either returns "Standard Savings Account" for Savings Account;
benefits offered by savings account + "GSave Transfer";
benefits offered by savings account + "With Insurance";
5. computeBalanceWithInterest() - returns new balance by computing the balance plus
the interest depending on the interest rate.
6. showInfo() - Returns details of account number, account name, and balance.

BankAcountDecorator must be an interface.
Follow instructions. You are not allowed to insert other methods except what is stated in
the diagram (setters and getters are allowed).

## UML
<img width="1294" height="735" alt="image" src="https://github.com/user-attachments/assets/fe5f64cc-69bc-496d-9e1d-24a8393c57c9" />

