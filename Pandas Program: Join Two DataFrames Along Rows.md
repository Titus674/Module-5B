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

student_data1 = {
    'name': ['geri', 'sharun'],
    'age': [20, 22],
    'score': [85, 92]
}

student_data2 = {
    'name': ['muthu', 'vicky'],
    'age': [23, 21],
    'score': [76, 88]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

df_combined = pd.concat([df1, df2], axis=0, ignore_index=True)

print("Result:\n", df_combined)
```

## Output
![439813711-6202671b-db26-427f-9fc5-59caf7b83e4d](https://github.com/user-attachments/assets/a49b6648-00a5-4f76-a2c8-fbbdce732cb6)
## Result
Thus the program has been successfully executed
