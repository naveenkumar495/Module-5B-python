
# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
x=np.array(eval(input()))
sorted=np.sort(x,axis=1)
print("Given array ")
print("",x,"\n")
print(sorted)

```
## Output
![447279329-cc08628a-f70d-4606-b262-996fc3272491](https://github.com/user-attachments/assets/c4ea0a82-7b6c-46d5-9181-b31bdc89c9a2)

## Result
Thus,the program has been executed successfully.
