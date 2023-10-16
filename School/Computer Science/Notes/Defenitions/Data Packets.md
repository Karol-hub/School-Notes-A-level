Segments of data
Composed of:
- Header 
	- Sender and recipient IP address
	- [[Protocols|Protocol]] being used
	- Order of packets
		- Packet number
		- Total amount of packets
	- Time to live / Hop limit
		- Tells when the packet should expire so it doesn't travel forever
		- Ensure that data packets do not linger indefinitely in the network
		- Promotes efficient and reliable packet delivery
- Payload
	- Raw data to be transmitted
- Trailer
	- Checksum or cyclical redundancy check
		- Checks if any errors happened during transmission
		- Makes sure the raw data the sender sent is the same as the recipient receives