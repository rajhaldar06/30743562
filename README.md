Documentation
How to Run the Application
1.	Compile the Java Files:
Ensure you have JDK installed on your machine. Open a terminal or command prompt and navigate to the directory where your .java files are located.
Compile the Java files using the javac command:
2.	Run the Application:
o	After compilation, you will have class files for each of your Java classes. Run the application using the java command:

Some of the features:-

1.	Add Account:
o	Select option 1 from the menu.
o	Enter the account ID, customer ID, balance, and account type when prompted.
2.	Remove Account:
o	Select option 2 from the menu.
o	Enter the account ID of the account you wish to remove.
o	The specified account will be removed from the system if it exists.
3.	Update Account:
o	Select option 3 from the menu.
o	Enter the account ID you want to update.
o	Enter the new balance and account type.
o	The account details will be updated accordingly.
4.	Deposit Funds:
o	Select option 4 from the menu.
o	Enter the account ID to deposit funds into.
o	Enter the amount to deposit.
o	The specified amount will be added to the account balance.
5.	Withdraw Funds:
o	Select option 5 from the menu.
o	Enter the account ID from which you want to withdraw funds.
o	Enter the amount to withdraw.
o	The specified amount will be subtracted from the account balance if sufficient funds are available.
6.	Transfer Funds:
o	Select option 6 from the menu.
o	Enter the account ID from which funds will be transferred.
o	Enter the destination account ID.
o	Enter the amount to transfer.
o	The funds will be transferred between the specified accounts if sufficient balance is available in the source account.
7.	Print Account Details:
o	Select option 7 from the menu.
o	The application will print details of all accounts currently in the system.
8.	Print Transactions:
o	Select option 8 from the menu.
o	The application will print all transactions recorded in the system.
9.	Exit:
o	Select option 9 from the menu to exit the application.

•	Account Class: Represents individual customer accounts with attributes like ID, customer ID, balance, and account type. This class encapsulates all data related to an account and provides methods for accessing and modifying account details.
•	Transaction Class: Records transactions associated with accounts. It includes attributes like transaction ID, account ID, transaction type, amount, and date. This class helps in tracking changes in accounts.
•	BankingSystem Class: Manages the core functionalities of the banking system, including adding, removing, updating accounts, performing deposits, withdrawals, and transfers, and managing transactions. It uses a HashMap for account storage and an ArrayList for transactions.
•	BankingSystemApp Class: Provides the console interface for interacting with the banking system. It allows users to select operations from a menu and input necessary data.
Object-Oriented Principles Applied
1.	Encapsulation:
o	Definition: Encapsulation involves bundling the data (attributes) and methods (functions) that operate on the data into a single unit or class.
o	Application: Each class (Account, Transaction, BankingSystem) encapsulates its data and provides public methods to interact with that data. This helps in protecting the internal state of objects and exposing only necessary functionalities.
2.	Abstraction:
o	Definition: Abstraction focuses on hiding the complex implementation details and showing only the essential features of an object.
o	Application: The BankingSystem class abstracts the complexity of managing accounts and transactions. Users interact with high-level methods without needing to understand the internal workings.
3.	Inheritance:
o	Definition: Inheritance allows a class to inherit attributes and methods from another class, promoting code reuse.
o	Application: In this implementation, inheritance is not used directly, as the design focuses on individual classes representing distinct entities. However, in a more complex system, you could extend this design to include base classes and derived classes for various types of accounts or transactions.
4.	Polymorphism:
o	Definition: Polymorphism allows objects to be treated as instances of their parent class rather than their actual class. It also refers to the ability of different objects to respond to the same method call in different ways.
o	Application: The current design does not explicitly demonstrate polymorphism, but in future extensions, methods could be overridden in subclasses to provide different implementations, demonstrating polymorphic behavior.
Overall, the application is designed to be modular and scalable, with clear separation of concerns and adherence to Object-Oriented principles, ensuring maintainability and extensibility.



