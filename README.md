# chatapp_socket
We’ve created a chat application through which the client can talk with the server. It is
achieved with the help of Socket and some basic GUI with NetBeans.

Project detail description including functionalities:

To implement this chat application, we’ve used the concept of socket programming. There
are two files in the program - server.java, client.java. An important thing to note is first we
need to compile the server.java, as it creates the socket required by the client to connect.
Once connection is established using socket, a chat box appears (GUI created using
NetBeans with simply drag and drop) through which client and server can communicate.

Socket:

A socket is one endpoint of a two-way communication link between two programs running on
the network. The server creates a socket (ServerSocket) with a specific port number which
helps the client to connect. When the client sends a connection request, it accepts it and a
connection is established.

GUI:

When the server and client are connected, a chat box pops up which is created with the help
of NetBeans. Now the program reads and writes with the help of DataInputStream and
DataOutputStream classes
