Program Assignment 2:

Client using customized protocol on top of UDP protocol for requesting identification from server for access permission to the network.

Pre-requisite:
Install gcc on Linux for C program compiler

How to compile and run in Linux:

1. Copy the files 'client2.c', 'server2.c', 'sample_input_pa2.txt' and 'Verification_Database.txt' to the desired location, preferrably the desktop for ease of access.
2. Run the below commands to compile the C programs on terminal:
	gcc server2.c -o server2
	gcc client2.c -o client2
3. First the server should be started. To start the server on terminal, run the code below:
	./server2
4. Open a new terminal window, run the following line below in order to run the client program:
	./client2
5. Packets will start transmitting and the output should be visible