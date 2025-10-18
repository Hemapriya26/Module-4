## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges *two dictionaries* and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries dict1 and dict2 with some key-value pairs.
2. Define a function merge() that merges the two dictionaries using the ** unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
3. Call the merge() function and print the merged dictionary.

## 🧾 Program

```
dict1=eval(input())
dict2=eval(input())
merged_dict=dict1.copy()
merged_dict.update(dict2)
print(merged_dict)
```

## Output

<img width="771" height="279" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/e70375d7-eb35-47e5-a819-44973d648a5b" />

## Result
Thus, the program has been executed successfully.
