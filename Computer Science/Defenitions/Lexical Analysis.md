Whitespace and comments are removed

This code
```
While    True: #prints no
	print      (    "no"  )
```
Turns into
```
While True:
	print("no")
```

- Rest of code is analysed for keywords, names of variables and constants 
- These are replaced with tokens
- Info about each token is stored in a symbol table