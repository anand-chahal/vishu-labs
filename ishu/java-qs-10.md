### Loops, Accumulators, Incrementors

1. Which of the following is the correct syntax for a `for` loop in Java?

   a) for (int i = 0; i < 10; i++)  
   b) for (i < 10; int i = 0; i++)  
   c) for (int i = 0; i++)  
   d) for (int i = 0; i < 10; i--)  

2. What is the output of the following code?  
   `for (int i = 0; i < 5; i++) { System.out.print(i + " "); }`

   a) 0 1 2 3 4  
   b) 0 1 2 3 4 5  
   c) 1 2 3 4 5  
   d) 1 2 3 4 5 6  

3. Which of the following statements about the `while` loop is true?

   a) It runs a set number of times.  
   b) It checks the condition after the loop executes.  
   c) It may never execute if the condition is false initially.  
   d) It must always have an increment statement.  

4. What is the output of the following code?  
   `int i = 0; while (i < 3) { System.out.print(i + " "); i++; }`

   a) 0 1 2  
   b) 1 2 3  
   c) 0 1 2 3  
   d) 1 2 3 4  

5. Which of the following is an infinite loop?

   a) for (int i = 0; i < 10; i++)  
   b) while (true) {}  
   c) for (int i = 0; i < 10; i--)  
   d) Both b and c  

6. What does the `break` statement do in a loop?

   a) It exits the loop and continues with the next iteration.  
   b) It skips the current iteration and continues with the next one.  
   c) It exits the loop entirely.  
   d) It does nothing.  

7. How do you skip the current iteration of a loop?

   a) break  
   b) continue  
   c) skip  
   d) return  

8. What is the output of the following code?  
   `int sum = 0; for (int i = 1; i <= 5; i++) { sum += i; } System.out.println(sum);`

   a) 5  
   b) 10  
   c) 15  
   d) 20  

9. Which of the following loops always executes at least once?

   a) for loop  
   b) while loop  
   c) do-while loop  
   d) All of the above  

10. What is the result of the following code?  
    `int sum = 0; int i = 0; while (i < 4) { sum += i; i++; } System.out.println(sum);`

    a) 4  
    b) 6  
    c) 10  
    d) 3  

11. How do you declare an accumulator variable for summing values?

    a) int sum;  
    b) int sum = 0;  
    c) sum = 0;  
    d) int accumulator;  

12. What is the output of the following code?  
    `for (int i = 1; i <= 3; i++) { for (int j = 1; j <= 3; j++) { System.out.print(i * j + " "); } System.out.println(); }`

    a) 1 2 3  
       2 4 6  
       3 6 9  
    b) 1 4 9  
       2 5 8  
       3 6 9  
    c) 1 2 3  
       4 5 6  
       7 8 9  
    d) 1 3 5  
       2 4 6  
       3 6 9  

13. How do you increment a variable by 1 in Java?

    a) i++  
    b) i += 1  
    c) i = i + 1  
    d) All of the above  

14. What is the output of the following code?  
    `int i = 10; while (i > 0) { i--; System.out.print(i + " "); if (i == 5) break; }`

    a) 10 9 8 7 6  
    b) 9 8 7 6 5  
    c) 10 9 8 7 6 5  
    d) 9 8 7 6 5 4  

15. Which loop is used to iterate over elements in a collection (like an array or ArrayList)?

    a) for loop  
    b) while loop  
    c) do-while loop  
    d) enhanced for loop  

16. What is the result of the following code?  
    `int sum = 0; for (int i = 1; i < 5; i += 2) { sum += i; } System.out.println(sum);`

    a) 4  
    b) 6  
    c) 8  
    d) 10  

17. Which of the following is the correct way to write a `do-while` loop?

    a) do { // code } while (condition);  
    b) do { // code } (condition) while;  
    c) while (condition) { // code } do;  
    d) while (condition) do { // code };  

18. What is the purpose of an incrementor in a loop?

    a) To decrease the loop counter  
    b) To control the number of iterations  
    c) To skip iterations  
    d) To add a fixed value to the loop counter each time  

19. What is the output of the following code?  
    `int count = 0; for (int i = 0; i < 10; i++) { if (i % 2 == 0) continue; count++; } System.out.println(count);`

    a) 5  
    b) 4  
    c) 3  
    d) 2  

20. How do you terminate a loop immediately?

    a) return  
    b) continue  
    c) break  
    d) exit  

21. What is an accumulator variable used for?

    a) To keep track of the number of iterations  
    b) To store the result of a cumulative operation  
    c) To control the loop condition  
    d) To initialize the loop  

22. What is the output of the following code?  
    `for (int i = 0; i < 5; i++) { if (i == 3) break; System.out.print(i + " "); }`

    a) 0 1 2 3 4  
    b) 1 2 3 4  
    c) 0 1 2  
    d) 0 1 2 3  

23. What is the output of the following code?  
    `int sum = 0; for (int i = 0; i <= 5; i++) { sum += i; } System.out.println(sum);`

    a) 10  
    b) 15  
    c) 20  
    d) 25  

24. What is the result of the following code?  
    `int i = 1; while (i <= 10) { System.out.print(i + " "); i += 2; }`

    a) 1 2 3 4 5 6 7 8 9 10  
    b) 1 3 5 7 9  
    c) 1 3 5 7 9 11  
    d) 2 4 6 8 10  

25. How do you create a decrementor in a loop?

    a) i--  
    b) i -= 1  
    c) i = i - 1  
    d) All of the above  

26. What is the output of the following code?  
    `int sum = 0; for (int i = 10; i > 0; i -= 2) { sum += i; } System.out.println(sum);`

    a) 20  
    b) 30  
    c) 40  
    d) 50  

27. How do you declare a `while` loop in Java?

    a) while (condition) { // code }  
    b) while condition { // code }  
    c) while (condition); { // code }  
    d) do { // code } while (condition);  

28. What is the result of the following code?  
    `int product = 1; for (int i = 1; i <= 4; i++) { product *= i; } System.out.println(product);`

    a) 4  
    b) 8  
    c) 16  
    d) 24  

29. What is the purpose of a loop control variable?

    a) To store the result of the loop  
    b) To control the flow of the loop  
    c) To initialize the loop  
   

 d) To accumulate values in the loop  

30. What is the output of the following code?  
    `for (int i = 0; i < 3; i++) { for (int j = 0; j < 3; j++) { if (i == j) continue; System.out.print(i + "," + j + " "); } }`

    a) 0,1 0,2 1,0 1,2 2,0 2,1  
    b) 0,0 0,1 0,2 1,0 1,1 1,2 2,0 2,1 2,2  
    c) 0,1 1,2 2,0  
    d) 0,0 1,1 2,2  

### Answers and Explanations

1. **a) for (int i = 0; i < 10; i++)**  
   **Explanation:** This is the correct syntax for a `for` loop in Java.

2. **a) 0 1 2 3 4**  
   **Explanation:** The loop runs from 0 to 4, printing each value.

3. **c) It may never execute if the condition is false initially.**  
   **Explanation:** If the condition is false initially, the `while` loop may never execute.

4. **a) 0 1 2**  
   **Explanation:** The loop runs while `i` is less than 3, printing each value.

5. **d) Both b and c**  
   **Explanation:** `while (true) {}` and `for (int i = 0; i < 10; i--)` are infinite loops.

6. **c) It exits the loop entirely.**  
   **Explanation:** The `break` statement exits the loop entirely.

7. **b) continue**  
   **Explanation:** The `continue` statement skips the current iteration and continues with the next one.

8. **c) 15**  
   **Explanation:** The loop adds each value from 1 to 5 to `sum`.

9. **c) do-while loop**  
   **Explanation:** The `do-while` loop always executes at least once because the condition is checked after the loop body.

10. **b) 6**  
    **Explanation:** The loop adds 0, 1, 2, and 3 to `sum`.

11. **b) int sum = 0;**  
    **Explanation:** This declares and initializes an accumulator variable for summing values.

12. **a) 1 2 3**  
        2 4 6  
        3 6 9  
    **Explanation:** The nested loops multiply `i` and `j` values and print the result.

13. **d) All of the above**  
    **Explanation:** All options are valid ways to increment a variable by 1.

14. **b) 9 8 7 6 5**  
    **Explanation:** The loop decrements `i` and breaks when `i` equals 5.

15. **d) enhanced for loop**  
    **Explanation:** The enhanced `for` loop is used to iterate over elements in a collection.

16. **b) 6**  
    **Explanation:** The loop adds 1 and 3 to `sum`.

17. **a) do { // code } while (condition);**  
    **Explanation:** This is the correct syntax for a `do-while` loop in Java.

18. **d) To add a fixed value to the loop counter each time**  
    **Explanation:** An incrementor adds a fixed value to the loop counter each time.

19. **a) 5**  
    **Explanation:** The `continue` statement skips the even values, incrementing `count` for odd values only.

20. **c) break**  
    **Explanation:** The `break` statement terminates a loop immediately.

21. **b) To store the result of a cumulative operation**  
    **Explanation:** An accumulator variable is used to store the result of a cumulative operation.

22. **c) 0 1 2**  
    **Explanation:** The loop breaks when `i` equals 3, so only 0, 1, and 2 are printed.

23. **b) 15**  
    **Explanation:** The loop adds each value from 0 to 5 to `sum`.

24. **b) 1 3 5 7 9**  
    **Explanation:** The loop increments `i` by 2 each time, printing odd numbers from 1 to 9.

25. **d) All of the above**  
    **Explanation:** All options are valid ways to decrement a variable by 1.

26. **c) 40**  
    **Explanation:** The loop adds 10, 8, 6, 4, and 2 to `sum`.

27. **a) while (condition) { // code }**  
    **Explanation:** This is the correct syntax for a `while` loop in Java.

28. **d) 24**  
    **Explanation:** The loop multiplies 1, 2, 3, and 4 to `product`.

29. **b) To control the flow of the loop**  
    **Explanation:** A loop control variable is used to control the flow of the loop.

30. **a) 0,1 0,2 1,0 1,2 2,0 2,1**  
    **Explanation:** The `continue` statement skips the iterations where `i` equals `j`, printing the other combinations.
