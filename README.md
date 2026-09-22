1. Problem Statement
Write a Java program that handles `ArithmeticException` when computing the daily rental rate with zero rental days.

The program calculates the daily rental rate using the total rental amount and the number of rental days. When the rental days are zero, an `ArithmeticException` occurs because division by zero is not valid.

 2. Objective

To understand exception handling in Java by handling an `ArithmeticException` that occurs when the number of rental days is zero while calculating the daily rental rate.

 3. OOP Concepts and Java Concepts Used

- Class Declaration
- Main Method
- Arithmetic Operation
- Exception Handling
- `try` block
- `catch` block
- `ArithmeticException`
- `System.out.println()`

Arithmetic Operation

```java
dailyRate = totalAmount / rentalDays;

Exception Handling

try {
    // calculation
} catch (ArithmeticException e) {
    // handle exception
}


4. Class Diagram

+-------------------------+
|       RentalDemo        |
+-------------------------+
| + main(String[] args)   |
+-------------------------+
| Calculate Daily Rate    |
| Handle ArithmeticException |
+-------------------------+


5. Algorithm

1.Define a class called RentalDemo.
2.In the main() method, declare the total rental amount and number of rental days.
3.Use a try block to calculate the daily rental rate.
4.Divide the total rental amount by the number of rental days.
5.If rental days is zero, an ArithmeticException occurs.
6.Use the catch block to handle the exception.
7.Display a meaningful error message instead of terminating the program.


6. Program Execution Instructions

1.Open the Java program in IntelliJ IDEA or any Java-supported IDE.
2.Compile the Java program.
3.Run the program.
4.Test the program with valid rental days.
5.Test the program with zero rental days.
6.Observe the normal output and the exception-handling output.

 7. Sample Output
 Error Condition
Error: Rental days cannot be zero.
Please enter a valid number of rental days.

Normal Condition
When rental days is changed to 5:
Daily Rental Rate: 1000

8. Screenshots
Exception Case

Add the screenshot showing the error message when rental days is zero.

Normal Case

Add the screenshot showing the daily rental rate when rental days is 5.

9. Test Cases

| Test Case | Total Amount | Rental Days | Expected Result |

| 1 | 5000 | 5 | Daily Rental Rate: 1000 |
| 2 | 5000 | 0 | ArithmeticException handled and error message displayed |

10. Challenges Faced and Solutions

Challenge
An ArithmeticException occurs when rental days are zero because division by zero is not allowed.

Solution
The try-catch mechanism is used to handle the ArithmeticException and display a meaningful error message.

11. Conclusion

The program successfully calculates the daily rental rate and handles the ArithmeticException when rental days are zero.

12. References

- Oracle Java – Exceptions
- Javatpoint – Exception Handling in Java
