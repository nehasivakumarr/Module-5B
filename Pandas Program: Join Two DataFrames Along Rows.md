# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
data=pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(f"{data}")
print('-------------------------------------')
d=pd.DataFrame(eval(input()))
print(f"{d}")
print()
print("Join the said two dataframes along rows:")
print(pd.concat([data,d],axis=0))


```

## Output
<img width="811" height="748" alt="image" src="https://github.com/user-attachments/assets/dc7c71e9-6f53-497f-ac81-1e90ac8b065b" />


## Result
Thus, the Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame has been executed successfully.
