## Programming Tasks
Keep solutions to all tasks in functions with names showing their purpose.

1. Run programs in terminal
2. Declare variables of different types (integers, real numbers, strings)
3. Write string to output (console or terminal)
4. Write other variables to output (integers, reals)
5. Read string from input with prompt
6. #basic Convert string to integer or real
7. #basic Convert string containing separators (like comma) to an array of strings
    - Example: “a, b, c, d” → [ “a”, “b”, “c”, “d” ]
8. #basic Convert string containing separators to an array of integers
    - Example: “1, 2, 3, 4” → [ 1, 2, 3, 4 ]
9. #basic Print out numbers from 1 to 10 using for loop
10. #basic Print out numbers: 2, 4, 6, 8, 10 using for loop
11. #basic Print out all numbers from range 1 to 100 which are divisible by 3
12. #basic Print out numbers from 100 to 1 (decreasing)
13. #basic Print out integer pair in format:
    - 1 1
    - 1 2
    - 1 3
    - 2 1
    - 2 2
    - 2 3
14. #prime Print out all prime numbers from range 1 to 100
15. #prime Check if a given number is prime
16. #fizzbuzz Implement Fizz buzz (https://en.wikipedia.org/wiki/Fizz_buzz)
  - 1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, Fizz Buzz, 16, 17, Fizz, 19, Buzz, Fizz, 22, 23, Fizz, Buzz, 26, Fizz, 28, 29, Fizz Buzz, 31, 32, Fizz, 34, Buzz, Fizz, etc. …
17. #basic Print out a length of an array
18. #basic Print out all elements of array [ 1, 2, 3, 4, 5 ], each element in new line, using for loop. After each number add word “odd” or “even” according to divisibility by 2
19. #basic Print out every second element of an array
20. #basic Print out a sum of all elements of an array of integers
21. #array Implement a function calculating an average value of all elements of an array of integers (can be real) - test it in a separate function by printing outputs from some calls
22. #array Implement a function finding maximum element of an array - test it separately
    - write automatic tests which check some corner case properties, for example displays:
      - “Maximum of [ 4, 3, 7, 1 ] is 7 and should be 7, test passed”
      - “Maximum of [ -4,- 3, -7, -1 ] is 0 and should be -1, test failed”
      - “Maximum of [ ] is 0 and should be undefined, test failed”
    - then of course fix the implementation of the function to pass all tests
23. #array Implement a function returning a maximum and minimum element of an array (using one for loop) - test it separately
24. #array Implement a function finding the longest string of an array of strings, together with it’s length - test it separately
25. #array Create an array from an arbitrary array of integers, containing only the values greater or equal 5
    - For example, for input [ 1, 2, 5, 8, 3, 9 ] will return [ 5, 8, 9 ]
    - Handle empty arrays and arrays with only negative elements
    - Do it two ways: using “for” loop, and using “while” loop
26. #array Create an array which is a reverse of a given array (of any length and content) using for loop (there is already reverse function, so don’t use it)
    - For example, for [ “a”, “b”, “c” ] it creates [ “b”, “c”, “a” ]
    - For [ 1, 2, 3, 4, 5 ] it creates [ 5, 4, 3, 2, 1 ]
27. #array Find the element in array which has the most occurences
    - For example for: [ 1, 2, 3, 4, 3, 5, 1, 3 ] it returns 3
28. For an array of products, e.g. [ “makaron”, “cukier”, “pieprz” ] generate an HTML table like:
```
        <table>
            <tr>
                <th>Number</th>
                <th>Product</th>
            </tr>
            <tr>
                <td>1</td>
                <td>makaron</td>
            </tr>
                ….     #(all remaining elements)
            </tr>
        </table>
```

29. For JS array objects like [ { name: “Tomek”, age: 12 }, { name: “Magda”, age: 15 } ] etc. generate an HTML table as in 29 containing headers and columns with sequence number, name and age.
30. #factorial Implement (and test separately) factorial function in two ways:
    - using for loop
    - using recursion
31. #hide_bad_words Write and test a function which hides bad words (fuck, shit, ass and motherfucker) by using “*” from a string
    - Number of stars should be equal to the number od characters in replaced string
    - For example for “What the fuck is this shit, you motherfucker?!” it should give “What the **** is this ****, you ************?!”
32. #random_notes_chord Write a function which given a sequence of cords, e.g “d, G, CMaj, CMaj” generates a random melody from notes of these chords, e.g. outputs “d f a, g d b, c e g, e g c”. Let’s suppose it generates 3 notes per chord. Hint: ask for help.
33. #string In a string containing letters find the longest sequence of the same letter.
    - For example for “aaabbbbccb” it should return “bbbb”
34. #string In a string containing letters reduce duplicates to one letter.
    - For example for “aaabbbbccb” it should return “abcb”
35. #string In a string containing letters remove duplicate sequences.
    - For example for “aaabbbbccbaaadccb” it should return “aaabbbbccbd”
36. #histogram In a text create histogram: the list of words with their occurences, ignoring case.
    - For example for “Ala ma kota i ala ma psa” it should be:
    - “ala” : 2, “ma” : 2, “kota” : 1, “i” : 1, “psa” : 1
37. Implement sorting algorithms:
    - merge sort
    - bubble sort
    - insertion sort
    - selection sort
    - quick sort
38. Solve task from https://adventofcode.com/2017/day/1


## Other sources
  - https://www.hackerrank.com/
  - https://www.codewars.com/
  - https://adventofcode.com/
