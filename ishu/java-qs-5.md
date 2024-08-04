### Scanner Class and its Methods

1. Which of the following is the correct way to create a Scanner object to read input from the console?

   a) Scanner sc = new Scanner();  
   b) Scanner sc = new Scanner(System.console());  
   c) Scanner sc = new Scanner(System.in);  
   d) Scanner sc = new Scanner(System.out);  

2. Which method of the Scanner class is used to read a string input from the user?

   a) nextLine()  
   b) nextString()  
   c) nextInput()  
   d) readLine()  

3. How do you read an integer input using the Scanner class?

   a) int num = sc.readInt();  
   b) int num = sc.getInt();  
   c) int num = sc.nextInt();  
   d) int num = sc.scanInt();  

4. Which method of the Scanner class is used to check if there is another token in the input?

   a) hasNext()  
   b) nextToken()  
   c) checkNext()  
   d) isNext()  

5. How do you close a Scanner object?

   a) sc.stop();  
   b) sc.terminate();  
   c) sc.end();  
   d) sc.close();  

6. What does the nextLine() method of the Scanner class return?

   a) The next token  
   b) The next line of input  
   c) The next integer  
   d) The next character  

7. Which method of the Scanner class is used to read a double input from the user?

   a) getDouble()  
   b) readDouble()  
   c) nextDouble()  
   d) scanDouble()  

8. Which of the following statements is true about the Scanner class?

   a) It can only read input from the console.  
   b) It can read input from files, strings, and the console.  
   c) It can only read input from files.  
   d) It can only read input from strings.  

9. How do you read a boolean input using the Scanner class?

   a) boolean b = sc.readBoolean();  
   b) boolean b = sc.getBoolean();  
   c) boolean b = sc.nextBoolean();  
   d) boolean b = sc.scanBoolean();  

10. What is the return type of the nextInt() method of the Scanner class?

    a) float  
    b) double  
    c) int  
    d) String  

11. Which method of the Scanner class is used to read a single character input from the user?

    a) nextChar()  
    b) next()  
    c) nextByte()  
    d) nextCharacter()  

12. What does the useDelimiter() method of the Scanner class do?

    a) Sets the delimiter pattern  
    b) Reads the next token  
    c) Checks if there is another token  
    d) Closes the Scanner  

13. How do you read a long input using the Scanner class?

    a) long l = sc.readLong();  
    b) long l = sc.getLong();  
    c) long l = sc.nextLong();  
    d) long l = sc.scanLong();  

14. Which of the following methods is used to read a float input from the user?

    a) nextFloat()  
    b) nextReal()  
    c) getFloat()  
    d) scanFloat()  

15. What happens if the input is not an integer and you call nextInt() method?

    a) It throws an InputMismatchException.  
    b) It returns 0.  
    c) It returns -1.  
    d) It reads the input as a string.  

16. How do you check if the input has another integer value using the Scanner class?

    a) sc.hasInt()  
    b) sc.checkInt()  
    c) sc.hasNextInt()  
    d) sc.isNextInt()  

17. Which of the following is the correct way to import the Scanner class in Java?

    a) import java.util.Scanner;  
    b) import java.util.ScannerClass;  
    c) import java.util.scanner;  
    d) import java.Scanner;  

18. Which method of the Scanner class is used to read a byte input from the user?

    a) nextByte()  
    b) nextChar()  
    c) nextInteger()  
    d) nextShort()  

19. What is the return type of the nextLine() method of the Scanner class?

    a) String  
    b) char  
    c) int  
    d) boolean  

20. How do you read a short input using the Scanner class?

    a) short s = sc.readShort();  
    b) short s = sc.getShort();  
    c) short s = sc.nextShort();  
    d) short s = sc.scanShort();  

21. Which of the following methods checks if the input has another double value?

    a) sc.hasDouble()  
    b) sc.hasNextDouble()  
    c) sc.checkDouble()  
    d) sc.isNextDouble()  

22. What is the purpose of the reset() method in the Scanner class?

    a) Resets the input stream  
    b) Resets the scanner to its initial state  
    c) Resets the delimiter pattern  
    d) Resets the token pattern  

23. How do you read a string input using the Scanner class?

    a) String str = sc.readString();  
    b) String str = sc.getString();  
    c) String str = sc.nextString();  
    d) String str = sc.nextLine();  

24. Which method is used to check if the input has another line of input?

    a) sc.hasLine()  
    b) sc.hasNextLine()  
    c) sc.isNextLine()  
    d) sc.checkLine()  

25. How do you set the delimiter pattern to a comma in the Scanner class?

    a) sc.useDelimiter(",");  
    b) sc.setDelimiter(",");  
    c) sc.defineDelimiter(",");  
    d) sc.setPattern(",");  

26. What does the close() method of the Scanner class do?

    a) Closes the Scanner and releases any associated resources  
    b) Closes the input stream  
    c) Resets the Scanner  
    d) Sets the delimiter pattern  

27. Which of the following is true about the next() method of the Scanner class?

    a) It reads the entire line of input.  
    b) It reads the next token of input.  
    c) It reads the next integer.  
    d) It reads the next float.  

28. How do you read a BigInteger input using the Scanner class?

    a) BigInteger bigInt = sc.readBigInteger();  
    b) BigInteger bigInt = sc.getBigInteger();  
    c) BigInteger bigInt = sc.nextBigInteger();  
    d) BigInteger bigInt = sc.scanBigInteger();  

29. Which of the following methods can be used to skip the current line in the Scanner class?

    a) sc.skipLine()  
    b) sc.skip()  
    c) sc.nextLine()  
    d) sc.next()  

30. What happens if you call nextLine() method after nextInt() method?

    a) It skips the current line and reads the next line.  
    b) It reads the remaining input in the current line.  
    c) It reads the next integer.  
    d) It throws an InputMismatchException.  

### Answers and Explanations

1. **c) Scanner sc = new Scanner(System.in);**  
   **Explanation:** This is the correct way to create a Scanner object to read input from the console.

2. **a) nextLine()**  
   **Explanation:** The nextLine() method reads a string input from the user.

3. **c) int num = sc.nextInt();**  
   **Explanation:** The nextInt() method reads an integer input from the user.

4. **a) hasNext()**  
   **Explanation:** The hasNext() method checks if there is another token in the input.

5. **d) sc.close();**  
   **Explanation:** The close() method is used to close a Scanner object.

6. **b) The next line of input**  
   **Explanation:** The nextLine() method returns the next line of input.

7. **c) nextDouble()**  
   **Explanation:** The nextDouble() method reads a double input from the user.

8. **b) It can read input from files, strings, and the console.**  
   **Explanation:** The Scanner class can read input from various sources including files, strings, and the console.

9. **c) boolean b = sc.nextBoolean();**  
   **Explanation:** The nextBoolean() method reads a boolean input from the user.

10. **c) int**  
    **Explanation:** The nextInt() method returns an int.

11. **b) next()**  
    **Explanation:** The next() method can be used to read a single character input from the user.

12. **a) Sets the delimiter pattern**  
    **Explanation:** The useDelimiter() method sets the delimiter pattern for the Scanner object.

13. **c) long l = sc.nextLong();**  
    **Explanation:** The nextLong() method reads a long input from the user.

14. **a) nextFloat()**  
    **Explanation:** The nextFloat() method reads a float input from the user.

15. **a) It throws an InputMismatchException.**  
    **Explanation:** If the input is

 not an integer, the nextInt() method throws an InputMismatchException.

16. **c) sc.hasNextInt()**  
    **Explanation:** The hasNextInt() method checks if the input has another integer value.

17. **a) import java.util.Scanner;**  
    **Explanation:** This is the correct way to import the Scanner class in Java.

18. **a) nextByte()**  
    **Explanation:** The nextByte() method reads a byte input from the user.

19. **a) String**  
    **Explanation:** The nextLine() method returns a string.

20. **c) short s = sc.nextShort();**  
    **Explanation:** The nextShort() method reads a short input from the user.

21. **b) sc.hasNextDouble()**  
    **Explanation:** The hasNextDouble() method checks if the input has another double value.

22. **b) Resets the scanner to its initial state**  
    **Explanation:** The reset() method resets the scanner to its initial state.

23. **d) String str = sc.nextLine();**  
    **Explanation:** The nextLine() method reads a string input from the user.

24. **b) sc.hasNextLine()**  
    **Explanation:** The hasNextLine() method checks if the input has another line of input.

25. **a) sc.useDelimiter(",");**  
    **Explanation:** The useDelimiter() method sets the delimiter pattern to a comma.

26. **a) Closes the Scanner and releases any associated resources**  
    **Explanation:** The close() method closes the Scanner and releases any associated resources.

27. **b) It reads the next token of input.**  
    **Explanation:** The next() method reads the next token of input.

28. **c) BigInteger bigInt = sc.nextBigInteger();**  
    **Explanation:** The nextBigInteger() method reads a BigInteger input from the user.

29. **b) sc.skip()**  
    **Explanation:** The skip() method can be used to skip the current line.

30. **a) It skips the current line and reads the next line.**  
    **Explanation:** Calling nextLine() after nextInt() skips the rest of the current line and reads the next line of input.
