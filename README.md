# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")
r = float(input())
obj = cse()
obj.mech(r)
```

## Output
<img width="672" height="198" alt="517435762-81b6448f-62d0-4210-9a48-29921ac8ef6b" src="https://github.com/user-attachments/assets/a65ecfb9-7981-43b0-8df4-76affe7dcb18" />

## Result
Thus the program executed successfully.


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
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```

## Output
<img width="798" height="138" alt="517436176-007e18e7-2970-426f-8e1d-3014258adade" src="https://github.com/user-attachments/assets/bef4cb0f-4bb4-49a1-b458-94fd67a78ca4" />

## Result
Thus,the program has been executed successfully.


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
data=eval(input())
sort=dict(sorted(data.items()))
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sort.items():
    print(f"({key}, {value}) ",end="")
```

## Sample Output
<img width="816" height="70" alt="517436693-8862cc91-d572-4a89-bd07-fd9fffb14778" src="https://github.com/user-attachments/assets/e9a9e4e5-9b72-451b-a090-5df51d91358d" />

## Result
Thus the program executed successfully.


# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])
except IndexError:
    print("check index range")
```

## Output
<img width="506" height="225" alt="517437317-9500861d-a2da-401b-943f-9a034702963e" src="https://github.com/user-attachments/assets/d3ebc277-3549-49b8-a621-3a8446f8c34e" />

## Result
Thus the program executed successfully.

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program:
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```
## Output:

<img width="395" height="167" alt="439316102-584ecff1-9dfb-4670-b1c8-ee354a85ed3d" src="https://github.com/user-attachments/assets/4431addc-f14b-4326-a474-87a1484f8559" />

## Result:
   Thus,the program has been executed successfully.




## REVIEW PAGE FOR MODULE



<img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/171daa07-22ee-43f8-9c50-a8538cde52d0" />

   

