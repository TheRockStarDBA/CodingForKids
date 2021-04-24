#### Number guessing game (April 24 2021)

- The user needs to guess what that number is. (In other words, the user needs to be able to input information.) 

- If the user’s guess is wrong, the program should return some sort of indication as to how wrong (e.g. The number is too high or too low). 

- If the user guesses correctly, a positive indication should appear. (e.g. you got it correct)

- Rules of Game :
  - To guess a number between 1 to 10
  - A player gets 3 chances

- pseudo code

```
- use random module
- infinite loop
   - variable for chances (remember to increment this everytime the answer is wrong)
   - pick number between 1 - 10
   - compare using if .. elif ... else for greater, less or equal 
   - if chances are done, print - loose and the number what was chosen.
   - ask if user wants to play again 
   - if N , then break out of loop
```

#### Concepts that are included 

- Random function / module
- Variables
- Integers
- Input/Output
- Print
- While loops
- If/Else statements
