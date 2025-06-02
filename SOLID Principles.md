1. S — Single Responsibility Principle (SRP)
- A class should have only one reason to change—meaning it should only do one thing.
2. O — Open/Closed Principle (OCP)
- Software entities (classes, modules, functions) should be open for extension but closed for modification.
3. L — Liskov Substitution Principle (LSP)
- Subclasses should be substitutable for their base classes without altering the correctness of the program.
4. I — Interface Segregation Principle (ISP)
- Clients should not be forced to depend on interfaces they do not use.
5. D — Dependency Inversion Principle (DIP)
- Depend on abstractions, not concretions. High-level modules should not depend on low-level modules.

### Assignment
- Try to implement the last principle in case of a Database connection class where if we switch Databases, then we should handle it with minimal code change.
- Tip:- Using an interface and implementing Database classes. Using the object of interface. 

