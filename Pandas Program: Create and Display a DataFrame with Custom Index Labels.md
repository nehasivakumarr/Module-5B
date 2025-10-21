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
import numpy as np
x=eval(input())
b=eval(input())
print(pd.DataFrame(x,index=b))
```

## Output
<img width="767" height="346" alt="image" src="https://github.com/user-attachments/assets/069349c6-2294-4906-bcfc-82bbf142b777" />


## Result
Thus, the python program to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows has been executed successfully.

