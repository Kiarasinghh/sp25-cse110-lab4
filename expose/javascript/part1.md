
1) Line 9 prints "values added: 20" 
2) Line 13 prints "final result: 20"
3) Var should not be used as it has no block scope, meaning they can be accesed anywhere in the current function or in the whole code if declared outside a function. 
4) Line 9 prints "values added: 20"
5) Line 13 gives a Reference Error where "result is not defined". This is becuase since we used the keyword "let", result is only visible insdie the code block from line 3-11. Since line 13 is not part of that code block, result does not defined there. 
6) Nothing is printed by line 9 as there is an error in line 7: "TypeError: Assignment to constant variable". This is because result was declared as a constant meaning it's value cannot be changed and in line 7 we are trying to assign it another value. 
7) Nothing is printed by line 13 as there is an error in line 7: "TypeError: Assignment to constant variable". This is because result was declared as a constant meaning it's value cannot be changed and in line 7 we are trying to assign it another value. 