1) Line 12 prints 3 as prices has 3 elements and i increases until it is equal to the length of prices. Therefore it is 3. 
2) Line 13 prints 150. This is because the last value of discounted prices was for prices[2] which is 300. 300*0.5 = 150. Therefore when we print the value of discountedPrice, it is 150. 
3) Line 14 prints 150. This is because the last value of final prices would be discountedPrice (the last value was 150) * 100 = 15000 and then 15000/100=150. Therefore the last value of finalPrice after the loop ends is 150. 
4) It returns [50,100,150] as that is the value of all the prices with a 50% discount.
5) There is an error saying i is not defined. This is because we used the "let" keyword to define i, meaning it is only visible in the for loop code block. Since line 12 is outide this code block, it cannot read i.
6) There will be an error saying discountedPrice is not defined. This is because we used the "let" keyword to define discountedPrice, meaning it is only visible in the for loop code block. Since line 13 is outide this code block, it cannot read the variable discountedPrice.
7) It prints 150. This is because we used the let keyword for finalPrice and it is inside the function. Since line 14 is also inside the same function, it can access the finalPrice varaible. The last value of finalPrice was 150 from the for loop so that is why 150 is printed. 
8) It would return [50,100,150] as we used the let keyword for fdiscounted and it is inside the function. Since line 16 is also inside the same function, it can access the discounted varaible. The finalPrice of all the prices after a disount is applied is pushed into disounted in the loop which is why it is [50,100,150] by the time we return it. 
9) At line 11 a refrence error will happen where i is not defined. This is because we used the "let" keyword to define i, meaning it is only visible in the for loop code block. Since line 11 is outide this code block, it cannot read i.
10) Line 12 prints 3 as the value of length was set in line 4 to prices.length (which is 3 as there are 3 values in prices). Since it is a const it's value can't get changed so it is still 3 when we print it. 
11) The function returns [50,100,150]. Even though we said the array is a const, pushing to it doesn't change the discounted array itself, just its contents. That is why we are able to add to it and the function doesn't return just []. 
12) 
    a. student.name;
    b. student[major]['Grad Year'];
    c. student.greeting();
    d. student[Favourite Teacher].name;
    e. student.courseLoad[0]
13) 
    a. 32 since integers map to their exact string represntation and adding a number and string results in string concatentation 
    b. 1  since you can't subtract from strings so the 3 gets converted into a number and subtracts 2, giving 1. 
    c. 3 since null is equivelant to 0 so 3+0=3
    d. 3null since adding a number (null which is 0) and string results in string concatentation. 
    e. 4 since true becomes 1 so it is 1+3=4
    f. 0 since false becomes 0 and null becomes 0 so it is 0+0=0
    g. 3undefined since undefined is not a number, so it is treated as a stirng and so both strings get concatenated. 
    h. NaN as you cannot converted undefined to a number, it is not a number. Therefore performing subtraction with NaN results in the answer being NaN. 
14) 
    a. true as the string 2 becomes the number 2 and 2 is greater than 1.
    b. false as according to a dictionary comparision, the "2" is greater than "12"'s first character "1". 
    c. true as the string '2' is converted into an integer and it is still 2. 
    d. false as === checks if 2 values are the same without performing type conversion and here one is a string and one is a integer. 
    e. false as true becomes 1 and 1 is not equal to 2. 
    f. true as the boolean of 2 is true therefore the comparision is true. 
15) == compares 2 objects after perofrming type conversion if they are not of the same type. However, === doesn't perform type conversion and compares objects as they are. 
17) The result would be [2,4,6]. This is because in modifyArray, we go through every element in the oinput array and call the doSomething function on it. Whatever doSomething returns, that vallue is appeneded to the newArr which is returned at the end. Since doSomething mulitplies the input by 2, all values in newArr are just the value in array*2. 
19) The output of this code will be 1 then 4 then 3 then 2. Since there are 2 timeout functions, those will be outputted after the line 2 and 5. Then, since line 4 has a smaller delay than line 3, the next number to be outputted is 3. Finally, 2 gets outputted last. 