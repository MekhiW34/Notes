Chapter 9 Notes

The Stack and the Heap: where things live. 
There are TWO areas of memory. The Heap is where OBJECT lives. And the Stack is where METHOD INVOCATIONS and LOCAL VARIABLES live.

Instance Vars are declared inside the class but not in the method.

Local Vars are declared inside a method, also including method parameters.

Non-Primitive vars hold reference to an object, NOT the obj itself. Objects live on the HEAP.

Local vars live on the STACK.
Instance vars live on the HEAP but inside the object they belong to.

If you write a constructor that takes arguments and you still want a no-arg constructor u have to build the no-arg constructor yourself.

More than one constructor in a class, constructors MUST have different argument lists.

OVERLOADED constructors means you have more then one constructor in your class.
Public Mushroom (int size){}
Public Mushroom (){}
Public Mushroom (boolean isMagic){}

Things to remember about constructors :
MUST have the same name as class and no return type.
If you don't put it in your class the compiler puts in a default constructor which is a no-arg constructor. 
You can have more than one constructor in your class, as long as the arguments list are different, having more than one constructor means you have overloaded constructors.


A call to super() in your constructor puts the superclass constructor on top of the stack. Then it calls a superclass constructor . And it goes until the object constructor is on the top. Once Object() finishes, it pops off the stack and the next thing down the stack(subclass constructor  that called object() is now on top.




The SCOPE of a variable is the part of the program within which the variable can be used. So, the scope describes the visibility of an identifier within the program. The LIFE of a variable or function is the time duration for which memory is allocated to store it, and when that memory is released.

Variables in Java are classified into primitive and reference variables. From the programmer's perspective, a primitive variable's information is stored as the value of that variable, whereas a reference variable holds a reference to information related to that variable. reference variables are practically always objects in Java.

Null can be assigned to any variable of a reference type (that is a non-primitive type) to indicate that the variable does not refer to any object or array. That means that null cannot be used in place of a reference to a Java object like an instance of java.

