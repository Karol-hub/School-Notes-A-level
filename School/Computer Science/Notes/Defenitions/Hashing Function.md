Turn an input (sometimes called key) into a unique fixed size hash (not always unique but should be)

Good hash functions should have:
- A low chance of [[Hashing Collisions|Collisions]]
- Hash should be smaller than the input (If used in a [[Hash Tables|Hash Table]])
	- Otherwise searching for a hash would take longer than searching for a key