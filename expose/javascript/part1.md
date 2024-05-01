# Part1. A Quick Introduction
1. ```values added:  20``` is printed by line 9.
2. ```final result:  20``` is printed by line 13.
3. ```values added:  20``` is printed by line 9.
4. The code returns an error in line 13 and says **ReferenceError: result is not defined**. This happens because the ```result``` variable  is declared with ```let``` keyword inside the ```if``` block, which, therefore, it's only visible inside that block scope and javascript does not recognize ```result``` outside the scope.
5. The code returns an error in line 9 and says **TypeError: Assignment to constant variable.**. This happens because the ```result``` variable is declared with ```const``` keyword, which prevent the variable's value from being reassigned after it is assigned.
6. The code returns an error in line 13 and says **ReferenceError: result is not defined**. This happens because the ```result``` variable is declared with ```const``` keyword inside the ```if``` block, which therefore, it's only visible inside that block scope and javascript does not recognize ```result``` outside the scope.