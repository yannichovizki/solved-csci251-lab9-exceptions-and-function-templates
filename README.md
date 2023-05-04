Download Link: https://assignmentchef.com/product/solved-csci251-lab9-exceptions-and-function-templates
<br>
<strong> </strong>Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs using exceptions and function templates.<strong> </strong></li>

</ul>

<h1>Question 1 (Exception Class)</h1>

Create an exception class called InventoryException that inherits from runtime_error. The class should contain three constructors, a default constructor and two non-default constructors. The default constructor will pass the message “Invalid stock number. Stock number should be between 1111 and 9999” to the what() function in the base class. One non-default constructor should except an integer value that will pass the message “Invalid quantity. Quantity should not be negative” to the what() function. And another non-default constructor that accepts a floating-point value that will pass the message “Invalid price. Price should not be below RM0 and over RM10000.00” to the what() function.

Create an Inventory class with data members for stock number, quantity, and price. Include a default constructor, and overloaded insertion and extraction operator. The extraction operator should throw a suitable InventoryException object if the stock id, quantity, and price entered are invalid.

Create a main() function that instantiate an Inventory object, read its data and display the data of the object if no exception is thrown. Perform exception handling method in main().<strong> </strong>

<h1>Question 2 (Function Template)</h1>

Write a template version of the iterative binary search algorithm that searches an array of arbitrary type for a given key.

Declare and implement a class called Student that keeps the student id, name, and grade. Include a default constructor, the overloaded insertion (&lt;&lt;) operator and also the overloaded extraction operator (&gt;&gt;).

Declare and implement another class called Book that keeps the book’s title, author, and price. Just like the Student class, Include in class Book a default constructor, the overloaded insertion (&lt;&lt;) operator and also the overloaded extraction operator (&gt;&gt;).

Write a main() function that test your function by passing parameters of type int, float, char, Student, and Book. Identify and implement additional suitable operators needed to be overloaded in the Student and Book class that you define above so that it can work well with the template binary search function that you have written. A Student object should be searched using the student id and the Book object should be searched using its title.


