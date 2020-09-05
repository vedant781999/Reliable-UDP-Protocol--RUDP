# Reliable-UDP-Protocol--RUDP
This is an application layer reliable protocol over UDP for a P2P setup.

Handled various situations like packet loss, packet corruption, packet delay, and packet reordering  and implemented features like congestion window and Selective Repeat.

Built a chat application on top of the designed protocol and analyzed its performance in different situations

## Following  tasks have been completed
1. Create a chat client that uses two threads, one for listening and 
one for sending
2. Create Reliable protocol with following features
    	1. handshaking
	2. sequence num
	3. acks
	4. retransmission

