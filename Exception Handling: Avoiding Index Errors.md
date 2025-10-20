# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program

```
lst=[5, 10, 20]

try:
    print(lst[5])
except IndexError:
   print("You're out of list range")
```


## Output
![WhatsApp Image 2025-10-19 at 19 57 07_8c775b33](https://github.com/user-attachments/assets/bdffc442-6460-46a2-872a-e72153188b20)



## Result
The program successfully handles an IndexError when attempting to access a list element beyond its range.
Instead of crashing, it prints a custom message, informing the user that the requested index is out of range.
