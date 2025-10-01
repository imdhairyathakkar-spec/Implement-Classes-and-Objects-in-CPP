# Implement-Classes-and-Objects-in-CPP
Aim:
To study and implementation of pointer operation with call by value and call by address in C++

Software used:
Mingw compiler, visual studio code, online C++ compiler

Program 1 Calculation outside the Class
Explanation and Theory of the code: This program demonstrates basic Object-Oriented Programming (OOP) in C++ using a class named cube. The class contains three public data members: height, width, and length. In main(), an object c1 is created, and its attributes are accessed to compute the volume using the formula: volume = height × width × length. Since the values are initialized within the class, the calculation is straightforward. This approach encapsulates related data, promoting modular and reusable code design.

Algorithm:

Start
Define class cube with height, width, length
In main(), create object c1
Access c1 attributes
Calculate volume = height × width × length
Print volume
End
Program 2 Calculation inside the Class
Explanation and Theory of the code: This program uses Object-Oriented Programming (OOP) with a class cube that encapsulates dimensions and includes a member function volume() to compute the cube’s volume. The function accesses the class’s own data members (height, width, length) and returns the calculated volume. In main(), an object cube1 is created, and its volume() method is called. This approach promotes encapsulation, keeping both data and behavior within the class, making the code more modular and maintainable.

Algorithm:

Start
Define class cube with data members
Define member function volume()
Inside volume(), compute height × width × length
Return volume
In main(), create object cube1
Call cube1.volume() and store result
Print volume
End
Program 3 Access specifier
Explanation and theory of code: This program uses encapsulation, a core concept of Object-Oriented Programming (OOP). The class cube defines height, width, and length as private members, restricting direct access from outside the class. The public member function volume() accesses these private members to compute and return the volume. In main(), an object cube1 calls volume(), demonstrating how encapsulated data can be safely accessed through public interfaces. This design improves security, modularity, and maintainability of code.

Algorithm:

Start
Define class cube
Private: height, width, length
Public: volume() function
Inside volume(), compute height × width × length
Return volume
In main(), create object cube1
Call cube1.volume() and store result
Print volume
End
Program 4 User Defined class
Explanation and theory of code: This program showcases Object-Oriented Programming (OOP) with user input. The class cube contains public data members and three member functions: inp() for input, volume() for calculation, and display() for output. The inp() function takes dimensions from the user via cin, and volume() computes the result using the formula: volume = height × width × length. Encapsulation is maintained by grouping related data and behavior, while modular design improves readability and reusability. This structure is ideal for real-world object modeling.

Algorithm:

Start
Define class cube
Data members: height, width, length
Member functions: inp(), volume(), display()
In inp(), take input for dimensions
In volume(), compute height × width × length
In display(), call volume() and print result
In main(), create object cube1
Call cube1.inp()
Call cube1.display()
End
Conclusion
Through these programs, we've mastered key concepts of C++ programming—from basic function calls to advanced object-oriented design. we began with call by value, where changes don’t affect original variables, then progressed to call by reference using pointers and reference variables, enabling direct modification. Transitioning into classes, you explored encapsulation, member functions, and user interaction. By integrating input methods and display logic, you built a dynamic and modular structure. Altogether, these examples reflect the growing command over C++ fundamentals, logical thinking, and clean code design—laying a solid foundation for more complex applications ahead.
