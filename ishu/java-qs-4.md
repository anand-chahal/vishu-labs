### References (Variables)

1. Which of the following is a reference type in Java?

   a) int  
   b) double  
   c) String  
   d) char  

2. What is the default value of an uninitialized reference variable in Java?

   a) 0  
   b) undefined  
   c) null  
   d) false  

3. Which keyword is used to create a new object in Java?

   a) create  
   b) new  
   c) make  
   d) construct  

4. What does the following code output? String s1 = "Hello"; String s2 = "Hello"; System.out.println(s1 == s2);

   a) true  
   b) false  
   c) HelloHello  
   d) Compilation error  

5. Which of the following is the correct way to declare a reference variable in Java?

   a) int x = 5;  
   b) String s = "Hello";  
   c) char c = 'A';  
   d) double d = 3.14;  

6. Which of the following will cause a NullPointerException in Java?

   a) int x = 0;  
   b) String s = ""; s.length();  
   c) String s = null; s.length();  
   d) boolean flag = false;  

7. Which of the following statements is true about reference variables?

   a) They store the memory address of the object they refer to.  
   b) They can only refer to primitive data types.  
   c) They must be initialized when declared.  
   d) They cannot be reassigned to another object.  

8. What is the output of the following code? String s1 = new String("Hello"); String s2 = new String("Hello"); System.out.println(s1 == s2);

   a) true  
   b) false  
   c) HelloHello  
   d) Compilation error  

9. Which of the following statements is true about the 'null' value in Java?

   a) It can be assigned to primitive types.  
   b) It can only be assigned to reference types.  
   c) It indicates a default value for primitive types.  
   d) It is the same as 0.  

10. Which method can be used to check if a reference variable is null?

    a) isNull()  
    b) nullCheck()  
    c) == null  
    d) equals(null)  

11. What is the output of the following code? String s1 = "abc"; String s2 = s1; s1 = "xyz"; System.out.println(s2);

    a) abc  
    b) xyz  
    c) abcxyz  
    d) null  

12. Which of the following correctly creates an array of integers in Java?

    a) int[] arr = new int[5];  
    b) int arr = new int[5];  
    c) int arr[] = new int[5];  
    d) Both a and c  

13. What will be the result of the following code? Integer x = null; int y = x;

    a) 0  
    b) null  
    c) Compilation error  
    d) NullPointerException  

14. What does the following code output? String s1 = "Hello"; String s2 = "Hello"; System.out.println(s1.equals(s2));

    a) true  
    b) false  
    c) HelloHello  
    d) Compilation error  

15. Which of the following is true about final reference variables in Java?

    a) They can be reassigned to another object.  
    b) They cannot be reassigned to another object.  
    c) They cannot be initialized when declared.  
    d) They are always null by default.  

16. What is the output of the following code? String s1 = "Hello"; String s2 = s1; s2 = "World"; System.out.println(s1);

    a) Hello  
    b) World  
    c) HelloWorld  
    d) null  

17. Which of the following correctly creates an object of the String class?

    a) String s = String("Hello");  
    b) String s = new String("Hello");  
    c) String s = create String("Hello");  
    d) String s = String.new("Hello");  

18. What will be the output of the following code? Integer x = new Integer(10); Integer y = new Integer(10); System.out.println(x == y);

    a) true  
    b) false  
    c) 10  
    d) Compilation error  

19. Which of the following statements is true about arrays in Java?

    a) They can hold primitive data types only.  
    b) They can hold objects only.  
    c) They can hold both primitive data types and objects.  
    d) They must be initialized to a size when declared.  

20. What does the following code output? String s = null; if (s == null) { System.out.println("null"); } else { System.out.println("not null"); }

    a) null  
    b) not null  
    c) Compilation error  
    d) Runtime error  

21. Which of the following is the correct way to create an object of a class named 'Person'?

    a) Person p = new Person();  
    b) Person p = Person();  
    c) Person p = create Person();  
    d) Person p = Person.new();  

22. What is the output of the following code? String s1 = "abc"; String s2 = "abc"; System.out.println(s1 == s2);

    a) true  
    b) false  
    c) abcabc  
    d) Compilation error  

23. Which of the following will cause a compilation error?

    a) String s1 = null;  
    b) int[] arr = new int[5];  
    c) int x = null;  
    d) boolean flag = false;  

24. What will be the result of the following code? String s1 = "Hello"; s1 = null; System.out.println(s1.length());

    a) 0  
    b) null  
    c) 5  
    d) NullPointerException  

25. Which of the following statements is true about String objects in Java?

    a) They are mutable.  
    b) They are immutable.  
    c) They can be converted to primitive types.  
    d) They must be created using the 'new' keyword.  

26. What is the output of the following code? String s1 = "Hello"; String s2 = "Hello"; System.out.println(s1.equals(s2));

    a) true  
    b) false  
    c) HelloHello  
    d) Compilation error  

27. Which of the following statements is true about the 'new' keyword in Java?

    a) It is used to declare variables.  
    b) It is used to create new objects.  
    c) It is used to initialize variables.  
    d) It is used to convert types.  

28. What will be the output of the following code? String s = "Hello"; s = s + " World"; System.out.println(s);

    a) Hello  
    b) Hello World  
    c) HelloWorld  
    d) Compilation error  

29. Which of the following correctly declares a reference variable of type String?

    a) String s;  
    b) int s;  
    c) boolean s;  
    d) double s;  

30. What is the output of the following code? String s1 = new String("Hello"); String s2 = s1; System.out.println(s1 == s2);

    a) true  
    b) false  
    c) HelloHello  
    d) Compilation error  

### Answers and Explanations

1. **c) String**  
   **Explanation:** String is a reference type in Java.

2. **c) null**  
   **Explanation:** The default value of an uninitialized reference variable in Java is null.

3. **b) new**  
   **Explanation:** The new keyword is used to create a new object in Java.

4. **a) true**  
   **Explanation:** Both s1 and s2 point to the same string literal "Hello" in the string pool.

5. **b) String s = "Hello";**  
   **Explanation:** This is the correct way to declare a reference variable of type String.

6. **c) String s = null; s.length();**  
   **Explanation:** Calling a method on a null reference variable will cause a NullPointerException.

7. **a) They store the memory address of the object they refer to.**  
   **Explanation:** Reference variables store the memory address of the object they refer to.

8. **b) false**  
   **Explanation:** s1 and s2 are two different objects created using the new keyword, so their references are not equal.

9. **b) It can only be assigned to reference types.**  
   **Explanation:** The null value can only be assigned to reference types.

10. **c) == null**  
    **Explanation:** The == operator can be used to check if a reference variable is null.

11. **a) abc**  
    **Explanation:** s2 is assigned the value of s1 before s1 is reassigned to "xyz".

12. **d) Both a and c**  
    **Explanation:** Both int[] arr = new int[5]; and int arr[] = new int[5]; are correct ways to declare an array of integers in Java.

13. **d) NullPointerException

**  
    **Explanation:** Assigning null to an Integer reference variable and then trying to unbox it to an int will cause a NullPointerException.

14. **a) true**  
    **Explanation:** The equals method compares the contents of the strings, and both s1 and s2 contain "Hello".

15. **b) They cannot be reassigned to another object.**  
    **Explanation:** Final reference variables cannot be reassigned to another object once they are assigned.

16. **a) Hello**  
    **Explanation:** s1 remains unchanged because s2 is assigned a new value.

17. **b) String s = new String("Hello");**  
    **Explanation:** This is the correct way to create an object of the String class using the new keyword.

18. **b) false**  
    **Explanation:** x and y are two different objects, so their references are not equal.

19. **c) They can hold both primitive data types and objects.**  
    **Explanation:** Arrays in Java can hold both primitive data types and objects.

20. **a) null**  
    **Explanation:** The condition s == null is true, so "null" is printed.

21. **a) Person p = new Person();**  
    **Explanation:** This is the correct way to create an object of the class Person.

22. **a) true**  
    **Explanation:** Both s1 and s2 point to the same string literal "abc" in the string pool.

23. **c) int x = null;**  
    **Explanation:** Primitive types cannot be assigned the value null.

24. **d) NullPointerException**  
    **Explanation:** Calling a method on a null reference variable will cause a NullPointerException.

25. **b) They are immutable.**  
    **Explanation:** String objects in Java are immutable, meaning they cannot be changed once created.

26. **a) true**  
    **Explanation:** The equals method compares the contents of the strings, and both s1 and s2 contain "Hello".

27. **b) It is used to create new objects.**  
    **Explanation:** The new keyword is used to create new objects in Java.

28. **b) Hello World**  
    **Explanation:** The + operator concatenates the strings "Hello" and " World".

29. **a) String s;**  
    **Explanation:** This is the correct way to declare a reference variable of type String.

30. **a) true**  
    **Explanation:** s1 and s2 point to the same object, so their references are equal.
