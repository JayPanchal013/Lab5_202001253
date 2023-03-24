<h1><p align="center">  Lab5_202001253 </p> </h1>

## IT314 - Software Engineering
## Lab 5 - Static Analysis
![image](https://user-images.githubusercontent.com/123714655/227495122-603f72e9-625a-4a99-813e-adab992be88d.png)

## ID: 202001253
## Name: Panchal Jaykumar Ghanshyambhai




* Using ‘mypy’ as a static analysis tool for python files stored in github repository.
* First step is to install mypy on the local system using the following command.

* pip install mypy

* Then from github repository on the link 
https://github.com/OmkarPathak/Python-Programs

Checking files from numpy Folder using mypy


**File** : Intro and Basics of Numpy <br>
**Error**: Cannot find implementation or library stub for module named "numpy"

![image](https://user-images.githubusercontent.com/123714655/227496383-21113bf0-8ecc-4be8-8ffd-6ae8ecf094d3.png)


**File** : HackerEarth: Basics of Input Output <br>
**Error**: List comprehension has incompatible type List[int]; expected List[str]  [misc]
 Unsupported operand types for + ("int" and "str")  [operator] etc.
 
 ![image](https://user-images.githubusercontent.com/123714655/227496622-891c354d-f0f3-4e14-8db5-2d48c1e1bacc.png)


**File** : HackerEarth: Data Structures: Arrays <br>
**Error**: Incompatible types in assignment (expression has type "deque[str]", variable has type "List[str]")  [assignment]
test.py:35: error: "List[str]" has no attribute "rotate"  [attr-defined]

![image](https://user-images.githubusercontent.com/123714655/227496914-9c546ce1-5151-4d61-931a-ac0c6740f835.png)

---
## Understanding of errors

* Unsupported operand type: using string data type with integer with arithmetic operation. 

* Incompatible types in assignment : using different data type on the both side of assignment*  ex. A = “abc” with integer datatype of A.

* "List[str]" has no attribute "rotate": using non-defined attribute of class List.

* Cannot find implementation or library stub for module named "numpy"  [import] : External module numpy is not imported in the current file to use its functionality.
