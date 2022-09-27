# CplusplusJourney
All code and assignments that I have created for myself as I learn c++



#Chapter 2 Assignment:
-Create 3 classes.

Class 1, Container:
An abstract class with the following proporties:
double *d, a pointer to a double
int size, the total size
toString(), a function returning all of the elements of the container in a string
size(), a function returning the size
a destructor
operator+, a function overriding the '+=' operator

Class 2, Vector:
A class that inherits from Container and does nothing special besides implementing the virtual functions

Class 3, Set:
A class that inherits from Container that does not allow repeat values to be put in.

Class 4, main class:
The main class that uses user input to initialize and play around with Vector and Set objects
