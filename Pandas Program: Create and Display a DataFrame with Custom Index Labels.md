# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd

exam_data = {
    'name': ['Alice', 'Bob', 'Charlie', 'David'],
    'score': [85, 90, 88, 92],
    'attempts': [1, 2, 1, 1],
    'qualify': ['Yes', 'Yes', 'Yes', 'No']
}

labels = ['a', 'b', 'c', 'd']

df = pd.DataFrame(exam_data, index=labels)

print(df)
````

## Output
```
      name  score  attempts qualify
a    Alice     85         1     Yes
b      Bob     90         2     Yes
c  Charlie     88         1     Yes
d    David     92         1      No
```
## Result
The program successfully creates a DataFrame from the given dictionary and applies custom index labels to the rows, then displays the DataFrame.
