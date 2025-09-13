# Week 1 - CSC207
## 11 September, 2024

### Notes during iRAT/tRAT:
- psvm is considered the "starting point of the program" because it is the **first method on the call stack**.
- This occurs because it is a **static** method in the class; this is the equivalent of it being a **top-level** function in Python. 
- In other words, it is **not** tied to any class instance, and so is called before any constructor of a class (i.e. before any object is instantiated)
- Think of it like it being the first top-level function of a program in Python, except that Java puts this functions on the call stack right away.