AIM:To develop and demonstrate fundamental programming concepts in C++ through multiple small-scale applications that perform arithmetic calculations, logical checks, and decision-making tasks. The programs include:

1.A simple calculator performing basic arithmetic operations.
2.An even or odd number checker.
3.A program to find the largest among three numbers.
4.A menu-driven movie review selector.
5.A vowel or consonant checker for single alphabet inputs.
THEORY:
Decision-making statements in C++ are used to control the flow of program execution based on certain conditions. They allow a program to choose different paths or actions depending on whether a condition is true or false, making programs dynamic and responsive.

1. Purpose of Decision-Making Statements
Decision-making statements help a program to make logical decisions and execute specific blocks of code accordingly. This enables programs to react differently to different inputs or situations, which is essential for creating interactive and functional software.

2. Types of Decision-Making Statements
C++ provides several decision-making constructs:

if statement: Executes a block of code if a specified condition is true.
if-else statement: Executes one block of code if the condition is true, otherwise executes an alternate block.
else-if ladder: Handles multiple conditions sequentially, executing the first true condition’s block.
switch statement: Used when multiple discrete values need to be checked for a variable, improving readability over multiple if-else statements.

ALGORITHM:-
1. Simple Calculator
Start program.
Display supported operations.
Input num1, op, num2.
Check operator:
+: Display sum.
-: Display difference.
*: Display product.
/: If num2 != 0, display quotient; else show error.
Else: Invalid operator message.
End program.

2. Even or Odd Checker
Start program.
Input number.
If num % 2 == 0, display even.
Else, display odd.
End program.

3. Largest of Three Numbers
Start program.
Input num1, num2, num3.
Compare:
If num1 >= num2 && num1 >= num3, display num1.
Else if num2 >= num1 && num2 >= num3, display num2.
Else, display num3.
End program.

4. Movie Review Selector
Start program.
Display menu of movies (1–6).
Input choice.
Use switch:
Case 1–6: Display movie and rating.
Default: Invalid choice message.
End program.

5. Vowel or Consonant Checker
Start program.
Prompt user for input.
Validate: Input must be a single alphabet.
Convert to lowercase.
If character is a, e, i, o, u → vowel.
Else → consonant.
End program.

CONCLUSION:-
These five programs collectively reinforce foundational programming skills in C++. They provide hands-on experience with:

Input handling
Arithmetic operations
Conditional logic
Loops
Error handling

