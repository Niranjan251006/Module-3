# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
Devolped by :NIRANJAN S
Reg no      :212224040221
```
```
def remove(str): 
  l=len(str) 
  a="" 
  n=int(input()) 
  for i in range(0,l): 
    if i==n: 
      a=a+"" 
    else: 
      a=a+str[i] 
print(a)
```

## Output
![438645734-989484d9-946b-44fb-a5f3-c64be0c6cd2d](https://github.com/user-attachments/assets/2b3b7c53-8f25-47c7-a79d-467538e58c13)

## Result
Thus the program has been successfully executed

