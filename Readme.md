# Day-1 Task

# Java Quiz

This is a quiz about Java programming language.

## Questions

1. JDK stands for ____.
   - Java development kit
   - Java deployment kit
   - JavaScript deployment kit
   - None of these

2. What makes the Java platform independent?
   - Advanced programming language
   - It uses bytecode for execution
   - Class compilation
   - All of these

3. Can we keep a different name for the Java class name and Java file name?
   - Yes
   - No

4. What is the entry point of a program in Java?
   - main() method
   - The first line of code
   - Last line of code
   - Main class

5. Which of the following is the correct syntax to create a variable in Java?
   - var name;
   - int name;
   - var name int;
   - All of these

6. Can the Java program accept input from the command line?
   - Yes, using command-line arguments
   - Yes, by accessing command prompt
   - No
   - None of these

7. String args[] in the main method is used for?
   - Passing arguments at compile time
   - Passing arguments at run time
   - Counting the number of words
   - Nothing

8. What is the use of the access modifier "public" in Java language?
   - To hide the main method from misuse
   - To call the main method outside of Class or Package by JVM
   - To protect the main method
   - None of the above

9. What is the need to mention "static" before the main method?
   - To call the main method without creating an object of the class
   - To make the main method a class method common to all instances
   - Both A and B
   - None of the above

10. What does a Data Type in Java refer to?
    - The place where data is stored
    - The technique of how data is retrieved
    - The type or variety of data being handled for reading and writing
    - None of the above

11. Which among the following is not a Data Type in Java?
    - short
    - int
    - long double
    - double

12. Which is the data type that is not recommended for numeric applications in Java?
    - byte
    - float
    - int
    - long

13. What is the size of a FLOAT floating-point number in Java?
    - 2 bytes
    - 4 bytes
    - 6 bytes
    - 8 bytes

14. What is the abbreviation of ASCII?
    - American Standard Characters for Information Interchange
    - Australian Standard Code for Information Interchange
    - American Standard Code for Information Interchange
    - None of the above

15. Java is a case-sensitive language.
    - True
    - False

16. What is the error in this code?

    ```java
    byte b = 50;
    b = b * 50;
    ```

    - a) b can not contain value 2500, limited by its range.
    - b) * operator has converted b * 50 into int, which cannot be converted to byte without casting.
    - c) b can not contain value 50.
    - d) No error in this code.

17. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        double a = 6 / 4;
        int b = 6 / 4;
        double c = a + b;
        System.out.println(c);
    }
    ```

    - a) 3.0
    - b) 2.0
    - c) 2.5
    - d) 1.5

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

    - a) 5 5
    - b) 5.5 5
    - c) 6.5
    - d) none of the above

19. What is the output of the following code?

    ```java
    public static void main(String [] args) {
        int var1 = 5;
        int var2 = 6;
        System.out.print(var1 > var2);
    }
    ```

    - a) true
    - b) false
    - c) 0
    - d) 1
    - e) error

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

    - a) a
    - b) b
    - c) a is greater
    - d) b is greater


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


23. Which option can be used to check that one of the numbers is positive and the other is negative?

    - a) a > 0 && b > 0
    - b) a > 0 && b < 0
    - c) a < 0 || b < 0
    - d) a * b < 0

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
 
25. What is the output of the following code?

    ```java
    public static void main(String[] args) {
        int a = 50, b = 20;
        if (a > b) {
            if (a > 100)
                print("Ace");
            if (b < 100)
                b = 50;
        } else if (a == b) {
            print("King");
        } else {
            print("Queen");
        }
    }
    ```

 

