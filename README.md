# 🛑 TypeError: Can Only Concatenate str (not "int") to str

## ❓ Why This Happens
This error occurs when trying to concatenate a string and an integer using `+`. Python does not allow adding a string (`str`) and an integer (`int`) together directly.

## 🔍 Problem Example
```python
print("Number of letters in your name: " + len(input("Enter your name")))  # ❌ Causes an error
```

## ✅ Correct Code
Convert the integer to a string using `str()` before concatenation:
```python
name_of_the_user = input("Enter your name")
length_of_name = len(name_of_the_user)
print("Number of letters in your name: " + str(length_of_name))  # ✅ Works correctly
```
