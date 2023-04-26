# Array

What is Array in C?

An array in C is a fixed-size collection of similar data items stored in contiguous memory locations. It can be used to store the collection of primitive data types such as int, char, float, etc., and also derived and user-defined data types such as pointers, structures, etc.

![image](https://user-images.githubusercontent.com/125825670/234075921-b8577131-e376-4698-bac9-d728f7ad0ec4.png)

C Array Declaration

In C, we have to declare the array like any other variable before using it. We can declare an array by specifying its name, the type of its elements, and the size of its dimensions. When we declare an array in C, the compiler allocates the memory block of the specified size to the array name.
Syntax of Array Declaration

data_type array_name [size];

         or
         
data_type array_name [size1] [size2]...[sizeN];

where N is the number of dimensions.

![image](https://user-images.githubusercontent.com/125825670/234076138-58dac9c1-23c6-4ae3-9cbf-0b78f0ea3ee0.png)

Advantages of Array in C:

The following are the main advantages of an array:

1. Random and fast access of elements using the array index.

2. Use of fewer lines of code as it creates a single array of multiple elements.

3. Traversal through the array becomes easy using a single loop.

4. Sorting becomes easy as it can be accomplished by writing fewer lines of code.

Disadvantages of Array in C:

1. Allows a fixed number of elements to be entered which is decided at the time of declaration. Unlike a linked list, an array in C is not dynamic.

2. Insertion and deletion of elements can be costly since the elements are needed to be rearranged after insertion and deletion.
