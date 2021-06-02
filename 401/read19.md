# Python Regular Expression Tutorial

```
import re
```

The match() function returns a match object if the text matches the pattern.


```
pattern = r"Cookie"
sequence = "Cookie"
if re.match(pattern, sequence):
    print("Match!")
else: print("Not a match!")
```

# Wild Card Characters: Special Characters

Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression. For simple understanding, they can be thought of as reserved metacharacters that denote something else and not what they look like.

Let's check out some examples to see the special characters in action...

But before you do, the examples below make use of two functions namely: search() and group().
With the search function, you scan through the given string/sequence, looking for the first location where the regular expression produces a match.
The group function returns the string matched by the re. You will see both these functions in more detail later.

Back to the special characters now.

```
re.search(r'Co.k.e', 'Cookie').group()

```



# shutil — High-level File Operations¶


Copying Files


```
shutil_copyfile.py
import glob
import shutil

print('BEFORE:', glob.glob('shutil_copyfile.*'))

shutil.copyfile('shutil_copyfile.py', 'shutil_copyfile.py.copy')

print('AFTER:', glob.glob('shutil_copyfile.*'))
```
