# Object-Oriented Programming Principles Showcase

This Java project serves as an illustration of fundamental Object-Oriented Programming (OOP) principles, using an Employee Payroll System as an example.

## Demonstrated OOP Principles

1. **Encapsulation:**
   - The `Employee` class encapsulates essential attributes (name, id) and behavior (calculateSalary) of an employee.
   - Controlled access is provided through accessor methods (`getName()`, `getId()`).

2. **Abstraction:**
   - The `Employee` class, being abstract, introduces an abstract method `calculateSalary()`, acting as a template for concrete subclasses (`FullTimeEmployee` and `PartTimeEmployee`).

3. **Inheritance:**
   - Both `FullTimeEmployee` and `PartTimeEmployee` inherit shared attributes and methods from the abstract `Employee` class.
   - Emphasis on code reusability through extension rather than redundancy.

4. **Polymorphism:**
   - Polymorphism is demonstrated by the overridden `calculateSalary()` method in both `FullTimeEmployee` and `PartTimeEmployee` classes.
   - The `PayrollSystem` class operates with a list of `Employee` objects, showcasing polymorphic behavior.

5. **Composition:**
   - The `PayrollSystem` class utilizes composition to manage a list of `Employee` objects, emphasizing flexibility and modularity in design.

## Usage Instructions

1. Compile the Java code :
   javac Main.java
2. Run the compiled code :
   java Main
3. Output :
   Upon execution, the program creates a PayrollSystem, adds instances of FullTimeEmployee and PartTimeEmployee, displays initial details, removes an employee, and 
   then presents the remaining details.

## Contributions

Contributions are encouraged! Please feel free to open issues or submit pull requests for any enhancements or suggestions.
