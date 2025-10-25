## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 5, 'd': 7, 'e': 9}

def merge(d1, d2):
    merged = {**d1, **d2}
    return merged

result = merge(dict1, dict2)
print(result)
```
## Output

<img width="522" height="188" alt="image" src="https://github.com/user-attachments/assets/2d946546-5e6a-4450-8b84-34b69067b46c" />


## Result
Thus,a Python program that merges **two dictionaries** and combines their key-value pairs is executed successfully.
