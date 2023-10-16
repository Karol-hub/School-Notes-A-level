- Method of [[Lossless Compression]]
- Frequent data occurrences are replaced with and index to a dictionary which is created alongside the compressed file 
- example
	- We shall go on to the end.
	  We shall fight in France,
	  we shall fight on the seas and oceans,
	  we shall fight with growing confidence and growing strength in the air,
	  we shall defend our island, whatever the cost may be.
- becomes
	- 1 go on to 3 end.
	  1 2 5 France,
	  1 2 on 3 seas 6 oceans,
	  1 2 with growing confidence 6 growing strength 5 3 air,
	  1 defend our island, whatever 3 cost may be.
	- With the dictionary

Index| Phrase
---|---
1| We shall
2| fight
3| the
4| on
5| in
6| and

- Note if dictionary is lost the data is unusable 