# Part 1a

1. It will print the number 10.
2. It will print the number 10.
3. It will print the number 10.
4. It will return an error. This is because "let" has block scope so result is undefined outside of the if statement.
5. The code will return an error because it attempts to reassign a const.
6. The code will return an error because it attempts to reassign a const.
7. It will print the number 3.
   
# Part 1b

1. It will print the number 3.
2. It will print the number 150.
3. It will print the number 150.
4. It will return a list containing the numbers: [50, 100, 150].
5. It will return an error because i is only initialized within the for loop so it is undefined outside of it.
6. It will return an error because discountedPrice is initialized the for loop and since we use "let" it will be undefined.
7. It will return the number 150.
8. It will return a list containing the numbers: [50, 100, 150].
9. It will return an error because i is only initialized within the for loop and will be undefined outside of it.
10. It will return the number 3. 
11. It will return a list containing the numbers: [50, 100, 150].
12. (a) student.name;
    (b) student['Grad Year'];
    (c) student.greeting();
    (d) student['Favorite Teacher'].name;
    (e) student.courseLoad[0];
13. (a) '32' because integers map to the string representation so it concatenates '3' and '2'.
    (b) 1 because the subtraction operation cannot concatenate so it converts '2' to an int.
    (c) 3 because the number value of null is 0.
    (d) 3null because it concatenates '3' and converts null to a string.
    (e) 4 because the number value of true is 1.
    (f) 0 because the number value of false and null is both 0.
    (g) 3undefined because it converts undefined to a string and concatenates them together.
    (h) NaN because you are subtracting a number with undefined.
14. (a) true because it will convert '2' to a string and 2 is greater than 1.
    (b) false because alphabetically '1' comes before '2'.
    (c) true because it will convert '2' to an int.
    (d) false because === will always return false if comparing different types.
    (e) false because the number equivalent of true is 1.
    (f) true because Boolean(2) is converted to true.
15. The === operator checks both value and type while == only checks value.
17. It will return the a list containing [2, 4, 6]. The reason is because modifyArray will iterate through every value in the array and for each value it calls the function doSomething. doSomething essentially doubles the passed in value so original array will return a new array with each of its values doubled.
19. 1, 4, 3, 2   