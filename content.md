The Python Standard library is a collection of code that comes bundled with Python, providing a wide range of functionality that is useful across many use cases. If some functionality you want use exists in the Standard Library, it is almost always preferable to use it, rather than write your own code as it will save you time and effort, and the code will have been tested and optimised by many users.
    
The full list of these packages is given in the [Python documentation](https://docs.python.org/3/library/index.html).

# Importing from the Standard Library

To use a module from the Standard Library, you need to import it using the `import`{.python} statement. For example, to use the `math`{.python} module, which provides mathematical functions and constants, you would write:

```py-cell
import math
```

You can then use the functions and constants provided by the `math`{.python} module, such as `math.pi`{.python}, which is a variable which contains the value of $\pi$.

```py-cell
print(math.pi)
```

In order for the above cell to work, you need to run the first cell containing the import statement first. If you try to run the second cell without running the first cell, you will get an error saying that `math`{.python} is not defined. This is because we need to import from the Standard Library before we can use it. Try reloading the page and running the second cell first to see this error for yourself.
