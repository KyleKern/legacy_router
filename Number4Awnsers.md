4. Answers to these questions:

 a. Why didn’t the original program forward packets between the hosts? 
	The program was sending it data to 10.0.0.1 and 10.0.0.2 and the way i had my network 	
	Set up is for routing through 127.0.0.1 and 127.0.0.2 once i changed it to that it worked.

b. Is the line ‘r1.cmd('sysctl -w net.ipv4.ip_forward=1')’ required?
	Yes 

c. Intentionally break your working program, e.g.: change a subnet length, IP address, or default route for a host. Explain why your change caused the network to break.
	I changed it to 257.0.0.1 and it broke because now the IP address was to long. Mainly it made it become longer than 32 bits.
