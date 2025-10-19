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
l1=['goal','new','user','sit','eat','dinner']
filter=[item for item in items if not re.search('e',item)]
print(filter)
```
## Output
<img width="718" height="354" alt="image" src="https://github.com/user-attachments/assets/3afba3cf-afda-43dc-ad0a-ff475cfab3d3" />


## Result
Thus the Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is created successfully.
