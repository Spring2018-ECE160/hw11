## Question 1

(Eckel, 15.1-3) Create a simple “shape” hierarchy: a base class called Shape and derived classes called Circle, Square, and Triangle. In the base class, make a virtual function called
draw( ), and override this in the derived classes. Make an array of pointers to Shape objects that you create on the heap (and thus perform upcasting of the pointers), and call draw( ) through the base-class pointers, to verify the behavior of the virtual function. If your debugger supports it, single-step through the code.

Modify the code so draw( ) is a pure virtual function. Try creating an object of type Shape. Try  to call the pure virtual function inside the constructor and see what happens. Leaving it as a pure virtual, give draw( ) a definition.

Expanding on on the previous part, create a function that takes a Shape object by value and try to upcast a derived object in as an argument. See what happens. Fix the function by taking a reference to the Shape object. 

Compile Steps: 

Command(s) to run the program:

Output:
