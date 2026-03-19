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
def init(self,a,b):
self.roll=a
self.name=b
def show(self):
print("Hello my id is :", self.roll)
print("My name is :", self.name)
name=input()
roll=input()
s1 = Student(name,roll)
s1.show()
```

### OUTPUT
<img width="723" height="218" alt="image" src="https://github.com/user-attachments/assets/2160baa0-1d22-4eae-9a87-bc564a356c69" />

### RESULT
Thus a Python code to create a class for a person with a parameterized constructor, which will take the name and userid of the person as parameters and print the userid of the person has been implemented and executed.
