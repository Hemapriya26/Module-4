DATE : 17.10.2025
---
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the *area of a circle* based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

## 🧠 Algorithm
1. *Get user input*: Take the radius of the circle as input from the user.
2. *Define the class*: Create a class named cse.
3. *Define the method*: Inside the class, define the method mech to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. *Execute the program*: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math as m
class pen:
    def stationary(self,a):
        self.a=a
    def f(self):
        print(f"Area of circle: {self.a*self.a*m.pi:.2f}")
d=int(input())
s=pen()
s.stationary(d)
s.f()
```
## Output
![WhatsApp Image 2025-10-19 at 19 51 59_c85a28c5](https://github.com/user-attachments/assets/975e2f70-7c72-4b8d-86dc-382ac6900914)

## Result
The program successfully calculates the area of a circle using classes and objects

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

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values


## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order


## 🧠 Algorithm

1. *Start the program.*
2. *Define* a dictionary with key-value pairs.
3. *Sort by Keys*:
   - Use sorted(dictionary.items())
   - Convert the result to a dictionary using dict()
4. *Sort by Values*:
   - Use sorted(dictionary.items(), key=lambda item: item[1])
   - Convert the result to a dictionary using dict()
5. *Display* the original and sorted dictionaries.
6. *End the program.*


## 🧪Program

```
my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'cherry': 'dark red',
    'blueberry': 'blue'
}
sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Original Dictionary:")
print(my_dict)
print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)
print("\nDictionary Sorted by Values:")
print(sorted_by_values)
```

## Sample Output
![442481898-dd21a240-bb09-4e3e-b45c-742df8eb321a](https://github.com/user-attachments/assets/1071a478-bb18-4a0b-a40d-f502b632cb66)


## Result
Thus , the program has been executed successfully.

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

## File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file story.txt that do *not* start with the alphabet 'T'.

## 🧠 Algorithm
1. Open the file story.txt in *read mode*.
2. Initialize a counter count to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is *not* 'T'.
   - If the line does not start with 'T', increment the count by 1.
4. After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

## 🧾 Program
```
def count_non_T_lines(filename):
    count = 0
    try:
        with open(filename, 'r') as file:
            for line in file:
                if not line.lstrip().startswith('T'):
                    count += 1
        print(f"Number of lines not starting with 'T': {count}")
    except FileNotFoundError:
        print(f" File '{filename}' not found.")
count_non_T_lines("story.txt")
```
## Output
![442482348-533398cd-8873-48fe-8ce1-b341b9aec84f](https://github.com/user-attachments/assets/f215bb05-22a0-45e5-96a4-12c81f2c8901)

## Result
Thus the program has been executed successfully.
