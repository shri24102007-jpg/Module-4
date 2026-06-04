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
```
my_dict = { 'banana': 'yellow', 'apple': 'red', 'grape': 'green', 'orange': 'orange' }

print("Sorted by Keys:") for key, value in sorted(my_dict.items()): print(key, ":", value)

print("\nSorted by Values:") for key, value in sorted(my_dict.items(), key=lambda item: item[1]): print(key, ":", value)
```

## Sample Output
Sorted by Keys: apple : red banana : yellow grape : green orange : orange

Sorted by Values: grape : green orange : orange apple : red banana : yellow



## Result
Thus, the Python program to sort a dictionary by keys and values was successfully executed and verified.
