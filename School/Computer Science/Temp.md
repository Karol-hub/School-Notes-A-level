```
// variables
int total
// removes everything but the things between the first 2 dots
siteName = siteName[:locate(siteName,".")]
siteName = siteName[locate(siteName,"."):]
// makes sitename uppercase
siteName = upper(siteName)
// adds value of ascii
for x in range(length(siteName))
	total += asc(siteName[x])
//returns total
return total
```