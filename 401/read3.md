# Reading and Writing Files in Python :


## to know about files :

-  Files on most modern file systems are composed of three main parts:

        Header: metadata about the contents of the file (file name, size, type, and so on)
        Data: contents of the file as written by the creator or editor
        End of file (EOF): special character that indicates the end of the file
- file name consists of file name and exitention that determines the file type

## Opening and Closing a File in Python :

      `file = open('raneemGhlion.txt')
      `

Important : We always Need To close the file after finish working with

 we can close a file using the try statement or the with statement :

      using try :
              `
              reader = open('raneem.txt')
        try:

        finally:
            reader.close()`



      using with :
          `with open('raneem.txt') as reader:
    # Further file processing goes here
    `


## options for modes:

    'r'	Open for reading (default)
    'w'	Open for writing, truncating (overwriting) the file first
    'rb' or 'wb'	Open in binary mode (read/write using byte data)



## Reading and Writing Opened Files


   - .read(size=-1)	:
            This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.

   - .readline(size=-1)	This reads at most size number of characters from the line. This continues to the       end of the line and then wraps back around.
      If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.

    - .readlines()	This reads the remaining lines from the file object and returns them as a list.


## Python Exceptions :
  note :while Syntax errors occur when the parser detects an incorrect statement.Where exception error This type of error occurs whenever syntactically correct Python code results in an error.

syntaxError Example:


    ```
    >>> print( 0 / 0 ))
  File "<stdin>", line 1
    print( 0 / 0 ))
                  ^
SyntaxError: invalid syntax

```


exception error Example:

```>>> print( 0 / 0)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: integer division or modulo by zero
```




## how the code should look like ?

![image](/401/try_except_else_finally.webp)


Example :

```
    try:
    linux_interaction()
except AssertionError as error:

    print(error)
else:
    try:
        with open('file.log') as file:
            read_data = file.read()

    except FileNotFoundError as fnf_error:
        print(fnf_error)
finally:
    print('Cleaning up, irrespective of any exceptions.')


    ```



