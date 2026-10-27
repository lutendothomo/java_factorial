Factorial

A small Java program that calculates the factorial of a number using a loop.

How it works
Negative numbers print an error message (factorials aren't defined for them).
0 and 1 return 1.
Any other number is multiplied down to 2 in a for loop.

Example output:

5! = 120
Requirements
Java 17 or newer (JDK)
Run it

From the project root:

bash
javac org/example/Factorial.java
java org.example.Factorial

Or run it from your IDE (IntelliJ: click the green arrow next to main).

Change the input

Edit this line in Factorial.java:

java
int number = 5;
Limitations

The result is stored in a long, which overflows above 20!. For larger inputs, switch to BigInteger.