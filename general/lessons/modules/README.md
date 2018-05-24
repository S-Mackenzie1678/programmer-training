# Modules
 As projects get more and more complex, one will find it inconvenient to place all of one's code in one file, especially if the project uses more than one language. The solution to this is **modules**. Modules let one use classes and functions and the like in a different file than originally in.
## Syntax
To include a moduled file, use
```python
import <filename>
```
An example would be something like this
```python
# module.py
def add_one(addend):
    return addend + 1
```
```python
# importer.py
import module
print add_one(3)
```
That will print 4 because of the import statement. Without that import statement, trying to ```add_one()``` won't work.

###### For times where things appear in <angle brackets>, the brackets should be excluded and what's in the brackets should be re    placed with a fit. Example:
```python
import <filename>
```
###### becomes
```python
import programmer_training
```
