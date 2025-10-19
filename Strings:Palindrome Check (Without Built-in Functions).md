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
a = input()
if a==a[::-1]:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="1299" height="417" alt="image" src="https://github.com/user-attachments/assets/4ced3cac-5b2a-4b1b-a19b-2462e38be267" />

## Result
Thus the program is executed successfully.
