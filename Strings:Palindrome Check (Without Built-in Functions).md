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

original_string = "google"
reversed_string = original_string[::-1]
if original_string == reversed_string:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")

```

## Output
![Screenshot 2025-04-29 145600](https://github.com/user-attachments/assets/51921e30-2430-43e0-b06d-09152c50e5be)


## Result
       A python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions,is successfully executed.
