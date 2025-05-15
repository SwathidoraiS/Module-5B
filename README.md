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
DEVELOPED BY: JANARTHANAN K
REGISTER NO: 212223040072

import numpy as np 
a=np.array(eval(input())) 
print("Given array") 
print(end=" ") 
print(a) 
print() 
print(np.sort(a,axis=0))
```
## Output
![image](https://github.com/user-attachments/assets/344b56e0-aa8b-4801-9bbe-82ded1fa8498)

## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.

# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
DEVELOPED BY: JANARTHANAN K
REGISTER NO: 212223040072

import numpy as np  
x=eval(input()) 
y=eval(input()) 
l1=np.array(x) 
l2=np.array(y) 
print(np.where(l1>l2)) 
print(np.where(l1==l2))
```
## Output
![image](https://github.com/user-attachments/assets/737234fc-2c88-420c-af1c-189af910bee5)

## Result
Thus the python program for element wise comparison between two numpy array has been implemented and executed successfully.

# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
DEVELOPED BY: JANARHTANAN K
REGISTER NO: 212223040072

import numpy as np  
a=np.array(eval(input())) 
b=np.array(eval(input())) 
print("Printing Original array") 
print(a) 
print("Array after deleting column 2 on axis 1") 
c=np.delete(a,1,axis=1)  
print(c) 
print("Array after inserting column 2 on axis 1") 
print(np.insert(c,1,b,axis=1))
```
## Output
![image](https://github.com/user-attachments/assets/a8806243-4231-42ae-9209-d830dd16924c)

## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.

# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
DEVELOPED BY: JANARHTANAN K
REGISTER NO: 212223040072

import numpy as np  
a=np.array(eval(input())) 
b=np.array(eval(input())) 
print("Printing Original array") 
print(a) 
print("Array after deleting column 2 on axis 1") 
c=np.delete(a,1,axis=1)  
print(c) 
print("Array after inserting column 2 on axis 1") 
print(np.insert(c,1,b,axis=1))
```
## Output
![image](https://github.com/user-attachments/assets/a8806243-4231-42ae-9209-d830dd16924c)

## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.
# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
DEVELOPED BY: JANARHTANAN K
REGISTER NO: 212223040072

import numpy as np  
a=np.array(eval(input())) 
b=np.array(eval(input())) 
print("Printing Original array") 
print(a) 
print("Array after deleting column 2 on axis 1") 
c=np.delete(a,1,axis=1)  
print(c) 
print("Array after inserting column 2 on axis 1") 
print(np.insert(c,1,b,axis=1))
```
## Output
![image](https://github.com/user-attachments/assets/a8806243-4231-42ae-9209-d830dd16924c)

## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.

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
DEVELOPED BY: JANARTHANAN K
REGISTER NO: 212223040072

import pandas as pd 
student_data1 = pd.DataFrame({ 
'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'], 
'name': ['Danniella Fenton', 'Ryder Storey', 'Bryce Jensen', 'Ed Bernal', 'Kwame Morin'],  
'marks': [200, 210, 190, 222, 199]}) 
student_data2 = pd.DataFrame({ 
'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'], 
'name': ['Scarlette Fisher', 'Carla Williamson', 'Dante Morse', 'Kaiser William', 'Madeeha Preston'],  
'marks': [201, 200, 198, 219, 201]}) 
print("Original DataFrames:") 
print(student_data1) 
print("-------------------------------------") 
print(student_data2) 
print("\nJoin the said two dataframes along rows:") 
result_data = pd.concat([student_data1, student_data2]) 
print(result_data)
```
## Output
![image](https://github.com/user-attachments/assets/e9ad6fb2-b409-4748-a3b9-07d2acb1e6b2)

## Result
Thus, the Python program has been successfully created and executed successfully to join the two DataFrames row-wise using pd.concat() and all records from both DataFrames were included in the final output
