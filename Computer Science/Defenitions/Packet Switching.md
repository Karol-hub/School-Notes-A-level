
 - Data is communicated using [[Data Packets|Packets]] 
 - [[Data Packets|Packets]] are sent across the most efficient route which can vary for each packet

Adv|Dis
---|---
Multiple methods ensure data arrives intact (Checksums and cyclic redundancy checks)| Time is spent deconstructing and reconstructing the packets
Multiple routes can be used between devices so if one path breaks another can be used| Must wait for all packets to arrive before data can be used
Packets can be transferred over very large networks to allow communication globally| 