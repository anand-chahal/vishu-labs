### String Class and its Methods

1. How do you create a new string object in Java?

   a) String s = 'Hello';  
   b) String s = new String("Hello");  
   c) String s = Hello;  
   d) String s = String.new("Hello");  

2. Which method is used to find the length of a string in Java?

   a) size()  
   b) length()  
   c) getLength()  
   d) measure()  

3. What is the output of the following code? String s = "Hello"; System.out.println(s.charAt(1));

   a) H  
   b) e  
   c) l  
   d) o  

4. Which method is used to convert a string to uppercase in Java?

   a) toUpperCase()  
   b) toUpper()  
   c) convertToUpperCase()  
   d) upperCase()  

5. How do you concatenate two strings in Java?

   a) Using the + operator  
   b) Using the concat() method  
   c) Both a and b  
   d) Using the append() method  

6. What does the equals() method do in the String class?

   a) Compares two strings for reference equality  
   b) Compares two strings for content equality  
   c) Converts the string to uppercase  
   d) Converts the string to lowercase  

7. What is the output of the following code? String s = "Hello"; System.out.println(s.substring(1, 4));

   a) Hel  
   b) ell  
   c) llo  
   d) ello  

8. Which method is used to check if a string starts with a specified prefix?

   a) beginsWith()  
   b) starts()  
   c) startsWith()  
   d) prefixWith()  

9. What is the result of the following code? String s = "Hello"; System.out.println(s.indexOf('l'));

   a) 1  
   b) 2  
   c) 3  
   d) 4  

10. How do you replace all occurrences of a character in a string?

    a) replaceAll()  
    b) replace()  
    c) substitute()  
    d) change()  

11. Which method is used to split a string into an array of substrings?

    a) divide()  
    b) partition()  
    c) split()  
    d) slice()  

12. What is the output of the following code? String s = "Hello World"; System.out.println(s.toLowerCase());

    a) hello world  
    b) HELLO WORLD  
    c) Hello World  
    d) hello World  

13. How do you trim whitespace from both ends of a string in Java?

    a) strip()  
    b) trim()  
    c) clean()  
    d) removeWhitespace()  

14. What does the compareTo() method do in the String class?

    a) Compares two strings lexicographically  
    b) Compares two strings for reference equality  
    c) Converts the string to uppercase  
    d) Converts the string to lowercase  

15. Which method is used to convert a string to a char array?

    a) toChars()  
    b) getChars()  
    c) toArray()  
    d) toCharArray()  

16. What is the result of the following code? String s = "abc"; System.out.println(s.isEmpty());

    a) true  
    b) false  
    c) abc  
    d) Compilation error  

17. How do you compare two strings, ignoring case differences?

    a) compare()  
    b) compareToIgnoreCase()  
    c) equalsIgnoreCase()  
    d) equals()  

18. What is the output of the following code? String s = "Hello"; System.out.println(s.replace('l', 'p'));

    a) Heppo  
    b) Hepllo  
    c) Heppo  
    d) Hello  

19. Which method is used to check if a string ends with a specified suffix?

    a) ends()  
    b) endsWith()  
    c) suffixWith()  
    d) finishWith()  

20. What is the result of the following code? String s = "Hello"; System.out.println(s.toLowerCase().equals("hello"));

    a) true  
    b) false  
    c) hello  
    d) Compilation error  

21. How do you extract a substring from a string in Java?

    a) sub()  
    b) substring()  
    c) extract()  
    d) cut()  

22. Which method is used to check if a string contains a specified sequence of characters?

    a) includes()  
    b) has()  
    c) contains()  
    d) matches()  

23. What is the output of the following code? String s = " Hello "; System.out.println(s.trim());

    a) Hello  
    b) Hello (with spaces)  
    c) " Hello "  
    d) Compilation error  

24. How do you join an array of strings into a single string with a delimiter?

    a) join()  
    b) concatenate()  
    c) merge()  
    d) combine()  

25. What is the result of the following code? String s = "Hello"; System.out.println(s.concat(" World"));

    a) Hello World  
    b) HelloWorld  
    c) Hello World (without space)  
    d) Hello  

26. Which method is used to find the last occurrence of a character in a string?

    a) lastIndex()  
    b) last()  
    c) lastIndexOf()  
    d) findLast()  

27. What is the output of the following code? String s = "abcabc"; System.out.println(s.replaceFirst("a", "x"));

    a) xbcxbc  
    b) xbcabc  
    c) abcxbc  
    d) abcabc  

28. How do you convert a string to a byte array in Java?

    a) getBytes()  
    b) toBytes()  
    c) getArray()  
    d) toArray()  

29. Which method is used to format a string in Java?

    a) format()  
    b) printf()  
    c) sprintf()  
    d) style()  

30. What is the result of the following code? String s = "Hello"; System.out.println(s.equals("hello"));

    a) true  
    b) false  
    c) hello  
    d) Compilation error  

### Answers and Explanations

1. **b) String s = new String("Hello");**  
   **Explanation:** This is the correct way to create a new string object in Java using the String class constructor.

2. **b) length()**  
   **Explanation:** The length() method is used to find the length of a string in Java.

3. **b) e**  
   **Explanation:** The charAt() method returns the character at the specified index. Index 1 in "Hello" is 'e'.

4. **a) toUpperCase()**  
   **Explanation:** The toUpperCase() method converts a string to uppercase.

5. **c) Both a and b**  
   **Explanation:** You can concatenate two strings using the + operator or the concat() method.

6. **b) Compares two strings for content equality**  
   **Explanation:** The equals() method compares two strings for content equality.

7. **b) ell**  
   **Explanation:** The substring() method returns a new string that is a substring of the original string. It starts at the specified beginIndex and extends to the character at index endIndex - 1.

8. **c) startsWith()**  
   **Explanation:** The startsWith() method is used to check if a string starts with a specified prefix.

9. **b) 2**  
   **Explanation:** The indexOf() method returns the index of the first occurrence of the specified character. 'l' first occurs at index 2 in "Hello".

10. **b) replace()**  
    **Explanation:** The replace() method replaces all occurrences of a specified character in a string.

11. **c) split()**  
    **Explanation:** The split() method splits a string into an array of substrings based on a specified delimiter.

12. **a) hello world**  
    **Explanation:** The toLowerCase() method converts all characters in the string to lowercase.

13. **b) trim()**  
    **Explanation:** The trim() method removes whitespace from both ends of a string.

14. **a) Compares two strings lexicographically**  
    **Explanation:** The compareTo() method compares two strings lexicographically.

15. **d) toCharArray()**  
    **Explanation:** The toCharArray() method converts a string to a char array.

16. **b) false**  
    **Explanation:** The isEmpty() method returns true if the string is empty, otherwise it returns false. "abc" is not empty.

17. **c) equalsIgnoreCase()**  
    **Explanation:** The equalsIgnoreCase() method compares two strings, ignoring case differences.

18. **c) Heppo**  
    **Explanation:** The replace() method replaces all occurrences of the specified character. 'l' is replaced with 'p'.

19. **b) endsWith()**  
    **Explanation:** The endsWith() method is used to check if a string ends with a specified suffix.

20. **a) true**  
    **Explanation:** The toLowerCase() method converts "Hello" to "hello",

 and the equals() method compares the strings for content equality.

21. **b) substring()**  
    **Explanation:** The substring() method extracts a substring from a string.

22. **c) contains()**  
    **Explanation:** The contains() method checks if a string contains a specified sequence of characters.

23. **a) Hello**  
    **Explanation:** The trim() method removes whitespace from both ends of a string.

24. **a) join()**  
    **Explanation:** The join() method joins an array of strings into a single string with a specified delimiter.

25. **a) Hello World**  
    **Explanation:** The concat() method concatenates "Hello" and " World".

26. **c) lastIndexOf()**  
    **Explanation:** The lastIndexOf() method finds the last occurrence of a character in a string.

27. **b) xbcabc**  
    **Explanation:** The replaceFirst() method replaces the first occurrence of the specified substring.

28. **a) getBytes()**  
    **Explanation:** The getBytes() method converts a string to a byte array.

29. **a) format()**  
    **Explanation:** The format() method is used to format a string.

30. **b) false**  
    **Explanation:** The equals() method compares two strings for content equality, and "Hello" is not equal to "hello" (case-sensitive).
