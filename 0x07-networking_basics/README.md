# 0x07. Networking basics #0

### Concept
	1. OSI model (Open Systeme Interconnection model)
	2. LAN (Local Area Network)
	3. WAN (Wide Area Network)
	4. Internet
	5. TCP/UDP

## OSI model
	-> The model partitions the flow of data in a communication system into seven *abstraction layers*.
	-> The OSI model standardizes telecommunication or computer communication functions.

### The Seven Layers of OSI model

####	1. Physical Layer

		* It is the lowest layer in the model
		* Recieves and transmits raw data

####	2. Data Link Layer
		* Provides node-to-node data transfer between two directly connected nodes
		* Can detect and correct errors that may occur in physical layer
		* Establish and terminates connection between two physucally connected devies by difining their protocal
		* Defines protocal for flow control between the two physically connected devices

		Data Link Layer Sublayers as per the IEEE 802
			* **Medium Access Control** (MAC) layer - control device in a network access to a medium and data transmissin permission
			* **Logical Link Control** (LLC) layer - identify and encapsulate network layer protocols, and controls error checking and frame sychronization

#### 	3. Network Layer
		* Netowrk - interconnection of many nodes
		* Every node has its own address
		* Network permits a node to transfer messeges to other nodes connected to it. The network provides the contents of the messege and the destination address of the messege. The network finds a way to deliver the messege by routing it through the intermediaate nodes. Large messeges may be splitted and resend as fragments from different nodes.

####	4. Trnsport Layer
		* provides the functional and procedural for transferng data sequences from source to a destination host, while maintaining the quality of the functions.
		* Connection-mode transport protocals classes ranges from class 0 to class 4. i.e TP0, TP1, TP2, TP3, and TP4.

####	5. Session layer

		* Controls dialogues(connections) between computers.

####	6. Presentation layer

		* Transform data into the format that the application accepts

####	7. Application layer

		* Is closer to the end user

		









	 














