Responsible for linking the code and the external library
Two types
- Static
	- Libraries are added directly to the code increasing file size 
	- Any updates to the library won't affect the code
- Dynamic
	- Addresses of modules and libraries are used in the code
	- Files remain at the size as the library isn't imported
	- [[Loaders]] retrieves program at specified address so it can be executed
	- An update to the library will feed into the main file 

