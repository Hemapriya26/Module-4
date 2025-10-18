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
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}
merged_dict = dict1.copy() 
merged_dict.update(dict2)
print("Merged Dictionary:", merged_dict)
```

## Output
![442481750-aad5cc3e-2ed6-479e-8779-a37f27bac877](https://github.com/user-attachments/assets/ab703d7f-abbf-42aa-afba-b422b66929de)

## Result
Thus, the program has been executed successfully.
