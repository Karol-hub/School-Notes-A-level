- Prevents unauthorised access to a network
- Packets are passed through [[Network Interface Card (NIC)]] and compares them against a set of rules defined by the admin
- Preconfigured rules are called packet filters
	- Limits network access
	- Works by checking the IP addresses on the packets and the protocols being used

When a firewall denies access two things can occur
- Packet is rejected
	- Sends an alert back to sender to say packet is rejected
- Packet is dropped
	- Doesn't send an alert back to sender