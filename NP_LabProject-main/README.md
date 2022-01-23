# NP_LabProject

Implement simple file server using sockets. The file server should be able to take the request from any client and return the requested file to client or return error message, status to client. Consider all the possible inputs for the file server. Implement using programming. Compare this result with FTP by using suitable tools.

1.	Server<br>
The server performs the following functions.
1. Start the program. 
2. Declare the variables and structures required. 
3. The socket is created using the socket function.
4. The socket is binded to the specific port. 
5. Start listening for the connections.
6. Accept the connection from the client. 
7. Creates a child process to handle request client among multiple clients. 
8. Close server socket descriptor 
9. Create a new file. 10. Receives the data from the client. 
11. Write the data into the file. 
12. The program is stopped.
13. </n></n>

2.	Client<br>
The client performs the following functions.
1. Start the program 
2. Declare the variables and structures required. 
3. A socket is created and the connect function is executed. 
4. The file is opened. 
5. The data from the file is read and sent to the server. 
6. The socket is closed. 
7. The program is stopped
