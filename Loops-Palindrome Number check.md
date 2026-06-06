## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev == num:
    print(f"{num} is a palindrome number.")
else:
    print(f"{num} is not a palindrome number.")
```
## Output

<img width="401" height="242" alt="image" src="https://github.com/user-attachments/assets/1fd7679b-e7e6-4094-885d-cf4d7d9e367a" />

## Result


The Python program to check whether a given number is a palindrome using a while loop was successfully written, executed, and verified.
