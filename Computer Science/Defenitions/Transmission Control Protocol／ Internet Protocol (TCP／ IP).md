A [[Stack]] of [[Networks|Networking]] [[Protocols]] that allow transmission of [[Data Packets]]

Layers
- Application Layer
	- Specifies which [[Protocols|Protocol]] should be used depending on the application that's sending the packet
	- eg. a web browser would probably use HTTPS or POP3 or FTP 
- Transport Layer
	- Establishes an end to end connection between the sender and receiver
	- Splits data into packets which contain:
		- Packet Number
		- Total amount of packets
		- Port being used for communication
- [[Networks|Network]]/[[Internet]] Layer
	- Adds source and destination IP address 
		- Combination of IP address and port number is called a socket address
	- Routers operate on the Network layer and use IP address to send the packets
	- Sockets are used to specify which device is the receiver and the application being used on that device
- Link Layer
	- Connection between the two devices
	- Adds the [[MAC addresses]] of the sender and receiver
	- For devices on the same network the destination [[MAC addresses|MAC address]] is the address of recipient computer
	- For devices using the internet the destination [[MAC addresses]] is the address of the recipient's router

Important to realise [[Stack]] nature so sender will go through in process described above but receiver will start at the end
![[Stack rep of TCPIP.png]]