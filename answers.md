1. Challenge 1:
  - Answer: b
  - Explanation: a variable declared with let in the global scope can be updated from inside a function


2. Challenge 2:
  - Answer: c
  - Explanation: a new varaible called a is defined inside the function, it is first given the value of a (1) and then changed to 10 within the function scope. the variable a on the global scope is not touched, the variable name is shadowed, which can cause confusion


3. Challenge 3:
  - Answer: c
  - Explanation: the function definition gets hoisted to the top so it is able to execute it even though the execution comes before the definition


4. Challenge 4:
  - Answer: c
  - Explanation: b and a both reference the same object so a change in one will be reflected in the other


5. Bonus - Challenge 5:
  - Answer: c
  - Explanation: the function just returns a new object that was defined in the function itself so the original is not changed
