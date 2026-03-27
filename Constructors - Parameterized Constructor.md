# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM
```
class Student:
    def __init__(self,n,a):
        self.n=n
        self.a=a
    def display(self):
        print("Student name is :",self.n)
        print("Student age is : ",self.a)
name=input()
age=int(input())
g=Student(name,age)
g.display()
```
### OUTPUT
<img width="1188" height="215" alt="image" src="https://github.com/user-attachments/assets/b1565d67-6e2e-426a-8fe4-ce476bb57f28" />

### RESULT
Therefore, the output is the example to write a Python code to create a class for a person with a parameterized constructor, which will take the name and userid of the person as parameters and print the userid of the person.
