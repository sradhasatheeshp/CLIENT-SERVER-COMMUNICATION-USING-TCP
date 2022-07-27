# CLIENT-SERVER-COMMUNICATION-USING-TCP

Aim: To implement a client server communication using TCP.
Algorithm
/////////////////
SERVER

• Include appropriate header files.
• Create a TCP Socket.
• Fill in the socket address structure (with server information)
• Specify the port where the service will be defined to be used by client.
• Bind the address and port using bind() system call.
• Server executes listen() system call to indicate its willingness to receive connections.
• Accept the next completed connection from the client process by using an accept()
system call.
• Receive a message from the Client using recv() system call.
• Send a message to client using send() system call.

CLIENT

• Include appropriate header files
• Create a TCP Socket.
• Fill in the socket address structure (with server information)• Specify the port of the Server, where it is providing service
• Establish connection to the Server using connect() system call.
• Receive the message from the server using recv() system call.
• Write the result thus obtained on the standard output.
