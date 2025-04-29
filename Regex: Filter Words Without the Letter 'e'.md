# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1=[]
for i in items:
    if re.search(r'e',i) is None:
        l1.append(i)
print(l1)


```
## Output
![Screenshot 2025-04-29 143902](https://github.com/user-attachments/assets/adb8867f-a3f4-49e8-91eb-843faaba9d49)


## Result
       A Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex),is successfully executed.
