# TASK-6
Operator Overloading in C++: Circle Class Example
This project showcases how to implement operator overloading in C++ through a simple Circle class example.

Overview
Operator overloading enables us to define the functionality of operators when applied to custom data types like classes. In this example, we demonstrate overloading the + operator to add together the radii of two Circle objects.

Circle Class
The Circle class contains the following components:

A private member variable radius to store the circle's radius.
A default constructor that initializes the radius to 0.0.
A setter method setRadius to modify the radius.
A getter method getRadius to access the radius value.
An overloaded + operator to combine the radii of two Circle objects.
Main Function
In the main function, the program performs the following steps:

Creates three Circle instances: c1, c2, and c3.
Sets the radii of c1 and c2 using the setRadius function.
Adds the radii of c1 and c2, and stores the result in c3 by using the overloaded + operator.
Displays the radius of c3 by calling the getRadius function.
Output
The program outputs the radius of the third circle, which is the combined sum of the radii of the first two circles.

Key Concepts
Operator Overloading
Class Design
Constructors and Destructors
Setter and Getter Methods
Overloading Stream Operators for Complex Class
This C++ program illustrates how to overload the stream insertion (<<) and stream extraction (>>) operators for a Complex class. The Complex class holds two private member variables, real and imaginary, which represent the real and imaginary components of a complex number.

Stream Insertion Operator (<<)
The << operator is overloaded to output a complex number in the format a + bi, where a is the real part and b is the imaginary part.

Stream Extraction Operator (>>)
The >> operator is overloaded to take the real and imaginary parts of a complex number as input from the user.

Main Function
Within the main() function, a Complex object com1 is created. The user is prompted to enter the real and imaginary parts of the complex number, which are read using the overloaded >> operator. The program then displays the complex number using the overloaded << operator.

Output
The program produces the following output when executed:
