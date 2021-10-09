# pype
Python as a command line utility

```
usage: pype [-h] [--verbose] PYTHON_CODE

Pythonic utiliy to transform stdin.

positional arguments:
  PYTHON_CODE    Python 3 code that processes a line of stdin, 
                 available as a `l` or `line` variables.
                 
                 The code is evaulated in a function. Use 2-spaces indentation.
                 
                 Return values are printed. If the retun value is a non-string iterable, each value will be printed separately.
                 You can also print using the built-in `print` function, abbreviated as `p`.

optional arguments:
  -h, --help     show this help message and exit
  --verbose, -v
```

