let's say we want to convert 53432 to hex 

53432 // 16^3 = 13 = D goes to left most box 

(53422-(16^3 * 13)) // 16^2 = 0 goes in next box 

(53422-(16^3 * 13)-(16^2 * 0)) // 16 = 11 = B 

(53422-(16^3 * 13)-(16^2 * 0)-(16^11)) = 8 

|16^3|16^2|16^1|16^0|
|---|---|---|---|
|D|0|B|8|