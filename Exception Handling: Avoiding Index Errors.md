# Ex 4d:Classes and Objects in Python: Multiplication & Floor Division using Class

## Aim
To write a Python program using a class to perform multiplication or floor division based on user choice.

## Algorithm
1.Start the program.

2.Create a class CSE with:
     setvalues() to read values of a and b
     mul() to perform multiplication
     div() to perform floor division

3.Read values of a and b using the object.

4.Read the user’s choice.

5.If choice = 1 → call multiplication method.

6.If choice = 2 → call division method.

7.If choice = 0 → print “Exiting!”

8.Otherwise → print “invalid choice”.

9.End the program.
## Program
```
class CSE:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def mul(self):
        print("Result: ", self.a * self.b)

    def div(self):
        if self.b != 0:
            print("Result: ", self.a // self.b)
        else:
            print("Cannot divide by zero")

a = int(input())
b = int(input())

obj = CSE()
obj.setvalues(a, b)
while True:
    choice = int(input())
    if choice == 1:
        obj.mul()
    elif choice == 2:
        obj.div()
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")
```

## Output
<img width="396" height="263" alt="image" src="https://github.com/user-attachments/assets/808a7e08-df86-42ab-bb5a-5f49cf174a18" />

## Result
Thus, the Python program using a class and conditional statements successfully performed multiplication or floor division based on the user's choice.
