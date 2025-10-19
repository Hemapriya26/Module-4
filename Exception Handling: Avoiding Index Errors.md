# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an *IndexError* when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list list1 with some integer elements.
2. Use a *try-except* block:
   - In the try block, attempt to access an index that is out of range (e.g., list1[5]).
   - In the except block, catch the error and print a custom message "check index range".
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
    L=eval(input())
    print(L[4])
except IndexError:
    print("check index range")
```
## Output

<img width="1113" height="213" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/d50d3ac5-c1e9-4786-bf4d-111ac91abbda" />

## Result
Thus the program has beeen executed successfully.
