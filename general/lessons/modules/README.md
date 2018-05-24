# Modules
 As projects get more and more complex, one will find it inconvenient to place all of one's code in one file, especially if the project uses more than one language. The solution to this is **modules**. Modules let one use classes and functions and the like in a different file than originally in.
## Syntax
To include a moduled file, use
```python
import <directory.subdirectory...filename>
###### Be advised that the . is in place of where a / might be intuative. Be careful.
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

## Libraries
There's just one last thing. Some modules come standard with Python 3.6 and these are included using the exact same syntax, but do not require their filepath (because, of course, there isn't one). A list of libraries can be found [here](https://docs.python.org/3/py-modindex.html).

###### For times where things appear in <angle brackets>, the brackets should be excluded and what's in the brackets should be re    placed with a fit. Example:
```python
import <filename>
```
###### becomes
```python
import programmer_training
```
