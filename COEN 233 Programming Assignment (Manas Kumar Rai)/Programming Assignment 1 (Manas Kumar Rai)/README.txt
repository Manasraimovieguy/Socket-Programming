Program Assignment 1:

Client using customized protocol on top of UDP protocol for sending information to the server.

Pre-requisite:
Install gcc on Linux for C program compiler

How to compile and run in Linux:

1. Copy the files 'client.c', 'server.c' and 'sample_input_pa1.txt' to the desired location, preferrably desktop for ease of access.
2. Run the below commands to compile both the C programs:
	gcc server.c -o server
	gcc client.c -o client
3. First the server should be started. To start the server, run the following code on terminal:
	./server
4. Open a new terminal window, run the code below for running the client program:
	./client
5. Packets would start transmitting and output will be visible