# Dynamic Star Network

The final project for my Computer Networking course. It was a project that involved reliably broadcasting ASCII strings or files to other nodes in a network.
The network, [a star network](https://en.wikipedia.org/wiki/Star_network), is both self-organizing and dynamic. It reorganizes itself (the number of nodes in the network and the hub node both change) 
to ensure that sending messages is as quick as possible.    


## Running the Star-Node
To run the star-node, you must run this following command:

```python star-node.py <name> <local_port> <poc_address> <poc_port> <n>```

The arguments are as such:
* **name**: This is the name of the star-node. Must be an ASCII string between 1 and 16 characters long.
* **local_port**: The port number that this star-node is running on.
* **poc_address**: This is the address that the POC of this star-node is running at. If this star-node doesn't have a POC, set it to 0.
* **poc_port**: This is the port number that the POC of this star-node is running at. If this star-node doesn't have a POC, set it to 0.
* **n**: This is the maximum number of star-nodes in this network.
