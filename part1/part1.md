1. The console will print prices.length. This is because var has global scope, so i exists outside of the for loop.
2. The console will print the discounted price of the last item in the prices array. This is because var has global scope, so discountedPrice exists outside of the for loop.
3. The console will print the final price of the last item in the prices array. This is because var has global scope, so finalPrice exists outside of the for loop.
4. The function will return an array containing [50, 100, 150]. This is because we have applied a 50% discount to the original items [100, 200, 300].
5. This line will result in an error. The variable i only exists in the for loop, so it is not defined here.
6. This line will result in an error. The variable discountedPrice only exists in the for loop, so it is not defined here.
7. The console will print the final price of the last item in the prices array. This is because let was declared before the for loop in the same block of code as the console.log() statement, so finalPrice exists outside of the for loop.
8. The function will return an array containing [50, 100, 150]. This is because we have applied a 50% discount to the original items [100, 200, 300].
9. This line will result in an error. The variable i only exists in the for loop, so it is not defined here.
10. This line will result in an error. The variable discountedPrice only exists in the for loop, so it is not defined here.
11. Assuming line 7 does not result in an error, this line will print out a 0. Since we assigned finalPrice as a constant, it will keep its original value of 0.
12. This function will return [50, 100, 150] as usual, assuming the assignment on line 7 works as intended.
13a. student.name
13b. student['Grad Year']
13c. student.greeting()
13d. student['Favorite Teacher'].name
13e. student.courseLoad[0]
14a. 32, the 2 is converted into a string, which is then concatenated with the "3".
14b. 1, the "3" is converted into a number, and then an arithmetic operation occurs.
14c. 3, the null is converted into 0, which is then added to the 3.
14d. 3null, the null is converted into a string, which is then concatenated with the "3".
14e. 4, true is converted into a 1, which is then added to 3.
14f. 0, false is converted into a 0, and null is also converted into a zero, and they are added together.
14g. 3undefined, undefined is converted into a string, which is then concatenated with a "3".
14h. NaN, since neither of these values is a number, a subtraction cannot take place so this results in a NaN.
15a. true, "2" is converted into a number, which is greater than 1.
15b. false, "2" is lexographically less than "12".
15c. true, the "2" is converted into a number which is equal to 2.
15d. false, these values are not of the same type, so the strict equality operator returns false.
15e. false, true is converted into the number 1, which is not equal to 2.
15f. true, the value of Boolean(2) is true.
16. The === operator is known as the strict equality operator. This means that it checks equality without making type conversions beforehand. For example, (0 == false) will result in true, while (0 === false) will result in false.
17. "How are you?" will get printed. This is because true gets converted into the number 1, which is not equal to 2. Additionally, 2 gets converted into true in the second conditional, so that block will execute.
18. See part1-question18.js
19. This function call will return [6, 8, 10]. For each number in the original array, modifyArray will call doSomething, passing in the array element as the first argument and the unnamed function as the second argument. doSomething will then add 2 to the element, then call the unnamed function on it, which multiplies the value by 2. This new element will then be added to the new array. Essentially, this function adds 2 to each element then multiplies it by two.
20. See part1-question20.js
21. This will print out:
1
4
3
2
