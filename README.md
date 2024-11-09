# Ex.No: 12 Pytest Python program for Addition

### DATE: 24/09/2024                                                                          
### REGISTER NUMBER :  212222040013
### AIM: 
To write a python program for addition of two numbers and test the test cases using
Pytest.

### Algorithm:
1. Write the python program for addition of two numbers
2. Make sure that function name should be “def test_*():” and the line to be tested should have assert keyword at the beginning
3. Write some test cases for to be tested and save it as “test_add.py”.
4. Open command prompt and change the directory to where pytest and program is saved and type “pytest test_add.py” and run it.

### Program:
```
def add(a,b): 
return a+b 
def test_3_plus_5_equals_8(): 
assert add(3,5) == 8 
def test_2_plus_3_equals_5(): 
assert add(2,3) == 6
```

### Output:
![STLN](https://github.com/user-attachments/assets/d0106d73-6fde-4b40-af9f-b7150ef8b7b7)

### Result:
Thus, the python program for addition is tested using pytest and executed and output is verified successfully.
