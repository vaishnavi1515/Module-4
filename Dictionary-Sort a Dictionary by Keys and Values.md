# Ex 4c:File Handling in Python: Reverse file contents and save to another file

## Aim
To write a Python script that reads the contents of a file, reverses the text, and saves the reversed content into another file.
## Algorithm

1.Start the program.

2.Create a function to write content into the input file.

3.Create another function to read content from a file.

4.Create a function to reverse the content: 
      Read the content from the input file.
      Reverse the string using slicing.
      Write the reversed content into the output file.

5.Take input text from the user.

6.Call the functions to create the input file, reverse its content, and display the output.

7.End the program.
## Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

def reverse_file_content(input_file_path, output_file_path):
    with open(input_file_path, 'r') as file:
        content = file.read()
    with open(output_file_path, 'w') as file:
        file.write(content[::-1])
```

## Output
<img width="1090" height="333" alt="image" src="https://github.com/user-attachments/assets/673c573e-9af7-4589-956f-e8821211ec68" />

## Result
Thus, the Python program successfully reversed the contents of a file and saved the reversed text into another file.
