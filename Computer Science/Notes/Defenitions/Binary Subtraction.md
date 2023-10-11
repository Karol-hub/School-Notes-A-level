One method is [[Binary Addition]] with [[Two's Compliment]]

Example of other method
Both number are just standard binary numbers

1|0|0|1|num 1
---|---|---|---|---
0|1|0|1|num 2

Going from left to right

1|0|0|1|num 1
---|---|---|---|---
0|1|0|1|num 2
 | | | |0|result

Same for next bit

1|0|0|1|num 1
---|---|---|---|---
0|1|0|1|num 2
 | | |0|0|result

Have to borrow from next bit then carry on

0|2|0|1|num 1
---|---|---|---|---
0|1|0|1|num 2
 |0|1|0|0|result

num1 = 9
num2 = 5
9-5 = 4 = 0100