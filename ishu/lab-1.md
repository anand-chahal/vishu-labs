## String parsing (Very important for input processing in CP)
Get familiar with all variables in `string` module (`import string`) and string methods!

### Write code to convert the inputs below to the outputs:

|Input|Output|Data Type|Notes
|-|-|-|-|
|"hello world"|["hello", "world"]|list[str]|
|"         abc    "| "abc"| str| remove leading and trailing white spaces/tabs
|"1,2,3,4,5"|[1, 2, 3, 4, 5]|list[int]|
|"1.3, 2.8, 3.96, 4.1, 5.0"|[1.3, 2.8, 3.96, 4.1, 5.0]|list[float]|
|"joe:john:huell:sean:emma"|["joe", "john", "huell", "sean", "emma"]|list[str]|
|"[1, 5.2, 6.5, -8.3, -10.0]"|[1, 5.2, 6.5, -8.3, -10.0]|list[float]|
|"{a: 1, b: 3, c: 10, d: 2}"|{a: 1, b: 3, c: 10, d: 2}|dict[str, int]|
|"john, 1, 2, 3, 4, 5;james, 10, 20, 10, 23, 12;emma, -2, 1, 4, 5, 6"|{"john: [1, 2, 3, 4, 5], "james: [10, 20, 10, 23, 12], "emma": [-2, 1, 4, 5, 6]|dict[str, list[int]]|
|"James, M10, S20, E30:Emma, M20, S10, E40:Adam, M19, S23, E40"|{"James: {"M": 10, "S": 20, "E": 30...}|dict[str, dict[str, int]]|

### String formatting (Very important for printing output in CP)
write
|Input|Output|
|-|-|
|"3.4545"|"3.45"|
|"3.4545"|"345.45%"|
|"[1, 2, 3, 4, 5]"|"[1.0, 2.0, 3.0, 4.0, 5.0]"||
|"[1.00, 2.00, 3.00, 4.00, 5.00]"|"[1, 2, 3, 4, 5]"||

## Recursion

### P1
https://leetcode.com/problems/fibonacci-number/description/

### Hints
1. Solve using recursion
2. Solve using memoization (lru.cache)

### P2
Implement $x^n$
https://leetcode.com/problems/powx-n/description/

What's the time complexity of your implementation? How fast can you make it?

## Numpy

Answer one the following questions in 1-line

https://www.geeksforgeeks.org/python-numpy-practice-exercises-questions-and-solutions/

## Pandas
Read the file titanic.csv using pandas and answer the following questions using pandas:

1. Plot the percentage of male and female passengers? Which plot type is best suited for this?
2. What's the average age of male passengers? Median?
3. What percentage of male passengers survived?
4. Do you know what's a histogram? Plot the histogram of the age of male passengers? female passengers?

5. Can you implement a simple dashboard using radio buttons for selecting male/female passengers and updating the plots based on what's selected?