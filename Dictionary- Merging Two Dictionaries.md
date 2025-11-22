# Ex 4b:Exception Handling in Python: Check negative age and raise exception

## Aim
To write a Python program that checks whether the entered age is negative and raises an exception using the raise keyword.

## Algorithm
1.Start the program.

2.Read the age from the user.

3.Print the entered age.

4.Check if the age is negative.

5.If negative, use raise to throw an exception.

6.Otherwise, do nothing (valid age).

7.End the program.
## Program
```
age = int(input())
print("Age is:")
print(age)

try:
    if age < 0:
        raise ValueError("Input Correct age.")
    else:
        year_of_birth = 2022 - age
        print("Year of Birth is:")
        print(year_of_birth)
except ValueError as e:
    print(e)

```
## Output
<img width="508" height="246" alt="image" src="https://github.com/user-attachments/assets/03aa7b3e-76a7-48d6-809c-b1bac37b067c" />

## Result
Thus, the program successfully checks if the age is negative and raises an exception using the raise keyword.
