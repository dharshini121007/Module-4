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
my_dict = {'b': 3, 'a': 1, 'd': 4, 'c': 2}

print(dict(sorted(my_dict.items())))                 
print(dict(sorted(my_dict.items(), key=lambda x: x[1])))  
```

## Sample Output
<img width="1917" height="787" alt="image" src="https://github.com/user-attachments/assets/b1c6cd8f-3e13-4cf3-a156-f522403d7eec" />

## Result
The program sorts the dictionary keys in alphabetical order and also sorts the dictionary values in alphabetical order, then displays the sorted results.
