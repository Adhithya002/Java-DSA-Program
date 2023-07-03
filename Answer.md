# Java Quiz
- DAY-01 TASK

## Questions

1. JDK stands for ____.
   - a) Java development kit

2. What makes the Java platform independent?
   - b) It uses bytecode for execution

3. Can we keep a different name for the Java class name and Java file name?
   - a) Yes

4. What is the entry point of a program in Java?
   - a) main() method

5. Which of the following is the correct syntax to create a variable in Java?
   - b) int name;

6. Can the Java program accept input from the command line?
   - a) Yes, using command-line arguments

7. String args[] in the main method is used for?
   - b) Passing arguments at run time

8. What is the use of the access modifier "public" in the Java language?
   - b) To call the main method outside of Class or Package by JVM

9. What is the need to mention "static" before the main method?
   - a) To call the main method without creating an object of the class

10. What does a Data Type in Java refer to?
    - c) The type or variety of data being handled for reading and writing

11. Which among the following is not a Data Type in Java?
    - c) long double

12. Which is the data type that is not recommended for numeric applications in Java?
    - b) float

13. What is the size of a FLOAT floating-point number in Java?
    - b) 4 bytes

14. What is the abbreviation of ASCII?
    - c) American Standard Code for Information Interchange

15. Java is a case-sensitive language.
    - a) True

16. What is the error in this code?

    ```java
    byte b = 50;
    b = b * 50;
    ```

    - b) * operator has converted b * 50 into int, which cannot be converted to byte without casting.

17. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        double a = 6 / 4;
        int b = 6 / 4;
        double c = a + b;
        System.out.println(c);
    }
    ```

    - b) 2.0

18. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        double a = 55.5;
        int b = 55;
        a = a % 10;
        b = b % 10;
        System.out.println(a + " " + b);
    }
    ```

    - a) 5.5 5

19. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        int var1 = 5;
        int var2 = 6;
        System.out.print(var1 > var2);
    }
    ```

    - b) false

20. What is the output of the following code?

    ```java
    public static void main(String[] args) {
        int a = 10, b = 15;
        if (a > b) {
            System.out.print("a ");
        } else {
            System.out.print("b ");
        }
        System.out.print("is greater");
    }
    ```

    - b) b is greater

21. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        int x = 5;
        if (x < 6)
            System.out.print("Hello  ");
        if (x == 5) {
            System.out.print("Hi  ");
        } else {
            System.out.print("Hey ");
        }
    }
    ```

    - Output: Hello  Hi

22. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        int var1 = 5;
        int var2 = 6;
        if ((var2 = 1) == var1)
            System.out.print(var2);
        else
            System.out.print(var2 + 1);
    }
    ```

    - Output: 2

23. Which option can be used to check that one of the numbers is positive and the other is negative?

    - c) a < 0 || b < 0

24. What is the output of the following code?

    ```java
    public static void main(String[] args) {
        int i = 0;
        while (i < 10) {
            i = i + 1;
            System.out.print(i);
            i = i + 1;
        }
    }
    ```

    - Output: 13579

25. What is the output of the following code?

    ```java
    public static void main(String[] args) {
        int a = 50, b = 20;
        if (a > b) {
            if (a > 100)
                System.out.print("Ace");
            if (b < 100)
                b = 50;
        } else if (a == b) {
            System.out.print("King");
        } else {
            System.out.print("Queen");
        }
    }
    ```

    - Output: Queen.

