## BankAccount class exercise!

In this exercise, you will be implementing inheritance and expanding the functionality of the `BankAccount` class by creating a subclass called `SavingAccount`. Follow the instructions below to complete the exercise:

1. Add the `deposit` method: Inside the `BankAccount` class, implement a method called `deposit` that takes a `double` parameter named `amount`. This method should increase the `_accountBalance` by the `amount` and print the updated balance. The message to print should follow this format: `"$amount deposited. New balance: $_accountBalance"`. Don't forget to update the access modifier of `_accountBalance` to private.

2. Add the `withdraw` method with a conditional statement: Still inside the `BankAccount` class, add a method named `withdraw` that takes a `double` parameter named `amount`. This method should check if the account balance (`_accountBalance`) is greater than or equal to the `amount`. If it is, subtract the `amount` from the `_accountBalance` and print the updated balance. The message to print should follow this format: `"$amount withdrawn. New balance: $_accountBalance"`. However, if the account balance is less than the `amount`, print "Insufficient balance." instead.

3. Add the `displayInfo` method: Lastly, add a method named `displayInfo` to the `BankAccount` class. This method should print the account holder's name, account number, and account balance. Use the following format for the printed information:
   - "User account name is: [accountHolder]"
   - "User account number is: [accountNumber]"
   - "User balance is: [_accountBalance]"

4. Implement inheritance with `SavingAccount`: Create a new class called `SavingAccount` that inherits from the `BankAccount` class. The `SavingAccount` class should have an additional instance variable called `interestRate` of type `double`, which represents the interest rate for the savings account.

5. Override the `displayInfo` method in `SavingAccount`: Inside the `SavingAccount` class, override the `displayInfo` method inherited from the `BankAccount` class. Extend the functionality of the method by also printing the `interestRate` using the following format:
   - "Interest rate: [interestRate]"

Remember to test your implementation by creating instances of the `BankAccount` and `SavingAccount` classes and calling each of the newly added methods. You can also test the inheritance by creating both types of accounts and observing the differences in behavior. Good luck!

## Starter Project

```dart
class BankAccount {
  static String bankName = 'ABC';

  final String accountNumber;
  final String accountHolder;
  double _accountBalance;
  bool? hasInterest;

  BankAccount({
    required this.accountHolder,
    required this.accountNumber,
    required double accountBalance,
    this.hasInterest,
  }) : _accountBalance = accountBalance;

   // 1. Add `deposit` method here

   // 2. Add `withdraw` method here

   // 3. Add `displayInfo` method here

}

   // 4. Create a `SavingAccount` class here

```
