# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```p
d = {'c': 'cat', 'a': 'apple', 'b': 'ball'}

print("Original Dictionary:", d)

sorted_keys = dict(sorted(d.items()))
print("Sorted by Keys:", sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_values)
```
## Sample Output
<img width="1528" height="261" alt="image" src="https://github.com/user-attachments/assets/adbcd7cf-fed9-4bf8-b6b3-6a9a60eedfd0" />

## Result
Thus, the Python program to sort a dictionary by keys and values using the sorted() function was implemented and executed successfully.
