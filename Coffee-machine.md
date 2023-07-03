## Exercise Description: Building a Coffee Machine Program with Dart.

In this exercise, you will create a coffee machine program using the Dart programming language. This program will allow users to interact with a coffee machine, order different types of coffee, and manage the coffee machine's inventory. As you work on this exercise, you will also learn and implement important Object-Oriented Programming (OOP) principles, including classes, objects, and encapsulation.

Here are the steps to follow for this exercise:

### Step 1: Class Creation

- Start by creating a class called `CoffeeMachine`. This class will represent the coffee machine itself and will contain properties and methods related to its functionality.
- Think about the properties that a coffee machine should have. For example, you can include properties like `coffeeBeans`, `water`, and `milk` to track the inventory levels.
- Define appropriate data types for these properties and initialize them with default values.

### Step 2: Object Instantiation

- Once you have created the `CoffeeMachine` class, instantiate an object of this class in the main function. This object will represent the actual coffee machine that users will interact with.

### Step 3: Encapsulation

- Apply encapsulation by making the properties of the `CoffeeMachine` class private. Use Dart's naming convention of prefixing private properties with an underscore (_) to indicate that they should not be accessed directly from outside the class.
- Implement getter and setter methods for the private properties to allow controlled access and modification of the coffee machine's inventory.

###  Step 4: Coffee Ordering

- Add a method in the `CoffeeMachine` class called `orderCoffee`. This method should take parameters like `coffeeType` and `sugarAmount` to represent the user's coffee preferences.
- Inside the `orderCoffee` method, use conditional statements to determine the coffee recipe based on the user's preferences. For example, if the user orders a cappuccino, the method should adjust the inventory levels accordingly (e.g., decrease the coffee beans and milk).
- Display a message indicating the successful preparation of the coffee.

By completing this exercise, you will gain a better understanding of how to implement OOP principles in Dart while building a practical coffee machine program. This exercise will reinforce your knowledge of classes, objects, and encapsulation, allowing you to create well-structured and modular code. Happy coding!
