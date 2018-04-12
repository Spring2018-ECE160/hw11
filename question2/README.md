## Question 2

(Eckel, 15.6, 15.8, 15.9, 15.10)

Create an inheritance hierarchy of Rodent: Mouse, Gerbil, Hamster, etc. In the base class, provide methods that are common to all Rodents, and redefine these in the derived classes to perform different behaviors depending on the specific type of Rodent. Create an array of pointers to Rodent, fill it with different specific types of Rodents, and call your base-class methods to see what happens.

Starting with the previous Rodent hierarchy, inherit BlueHamster from Hamster, override the base-class methods, and show that the code that calls the base-class methods doesn’t need to change in order to accommodate the new type.

Starting with the previous Rodent hierarchy, add a non virtual destructor, create an object of class Hamster using new, upcast the pointer to a Rodent*, and delete the pointer to show that it doesn’t call all the destructors in the hierarchy. Change the destructor to be virtual and demonstrate that the behavior is now correct. 

Starting with the previous Rodent hierarchy, modify Rodent so it is a pure abstract base class.

Compile Steps: 

Output:
