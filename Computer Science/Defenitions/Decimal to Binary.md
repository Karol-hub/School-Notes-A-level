Make sure sum of all weights add to decimal number

example 231 to bin
is 231>128 (left most weight)
If yes put 1 in 128 
If no put 0 in 128

128| 64| 32| 16| 8| 4| 2| 1
---|---|---|---|---|---|---|---
1|

Is 231-128= 103 > 64 (left most value)
If yes put 1 in 64 
If no put 0 in 64

128| 64| 32| 16| 8| 4| 2| 1
---|---|---|---|---|---|---|---
1|1|

Is 103-64= 39 > 32 (left most value)
If yes put 1 in 32 
If no put 0 in 32

128| 64| 32| 16| 8| 4| 2| 1
---|---|---|---|---|---|---|---
1|1|1|

Repeat process till you get

128| 64| 32| 16| 8| 4| 2| 1
---|---|---|---|---|---|---|---
1|1|1|0|0|1|1|1