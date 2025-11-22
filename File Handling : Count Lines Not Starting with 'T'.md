#  Ex 4e:Generate Fibonacci Series

## Aim
To write a Python program that generates the Fibonacci series up to a given number of terms.

## Algorithm

1.Start the program.

2.Read the number n from the user.

3.Initialize the first two Fibonacci numbers: a = 0, b = 1.

4.Use a loop to print n Fibonacci numbers:
      Print a
      Compute the next number as c = a + b
      Update a = b, b = c

5.End the program.
## Program
```
n = int(input())
a, b = 0, 1

for i in range(n):
    print(a)
    a, b = b, a + b
```
## Sample Output
<img width="355" height="377" alt="image" src="https://github.com/user-attachments/assets/7ae7b98a-2882-4c20-8ff0-80b7cae3d728" />

## Result
Thus, the program successfully generated the Fibonacci series for the given number of terms.
