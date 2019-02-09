> Written with [StackEdit](https://stackedit.io/).

# Introduction to Python Text Basics

- Understand how to open a normal `.txt` and `.pdf` files with basic Python libraries.
- Learn some basic regular expressions.

## Working with text files with Python - Part One

### Write a `.txt` file using Jupyter and magic cells

```python
%%writefile test.txt
Hello, this is a quick test file.
This is the second line of the file.
```

### Read a file

First you need to open the file:
```python
myfile = open('test.txt')
```
Then read the file:
```python
content = myfile.read()
```
Print the content for example:
```python
content
```
the content is going to be this save string of the file:
```
'Hello, this is a quick test file.\nThis is the second line of the file.\n'
```
Content is going to be this save string of the file and since it has its backslash `\n` if ever what actually want to print the content:
```python
print(content)
```
output:
```
Hello, this is a quick test file.
This is the second line of the file.
```
Finally close always the file:
```python
myfile.close()
```
In summary, to read a file:
```python
myfile = open('test.txt')
content = myfile.read()
print(content)
myfile.close()
```
You can change the cursor to index position 0 which essentially resets the cursor:
```python
myfile.seek(0)
```
Use:
```python
myfile.readlines()
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2ODc1MDAxMjYsLTU4ODczNTU0NSwtMj
A0MTcxMzU2MF19
-->