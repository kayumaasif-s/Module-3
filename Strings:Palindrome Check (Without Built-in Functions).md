# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = 'google'
rev = s[::-1]

if s==rev:
    print("\"Google\" is a palindrome")
else:
    print("\"Google\" is not a palindrome")
```
## Output
<img width="362" height="33" alt="image" src="https://github.com/user-attachments/assets/2e81cd85-9f78-4b84-8b36-e39fbf5d70c1" />

## Result
Thus the program has been executed successfully
