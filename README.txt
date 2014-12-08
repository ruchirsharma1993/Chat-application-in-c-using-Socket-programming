                              =======================================================
                                    CHAT APPLICATION IN C USING SOCKET PROGRAMMING
                              =======================================================
This is a client - server user-level application using sockets Programming in C. Server accepts strings from clients (even multiple
strings from each client) and replies with the reverse of the string.

For example:
when client sends “abcd”, Server replies with “dcba”.


Both server and client(s) output's both sending & receiving strings on the terminal.The server and client processes can run on same or 
different machines. Multiple client processes can connect to the same server.

Helper Functions:
(1) char *strrev(char *str)
To reverse and written the input string str.

=======================================================
                          USAGE
=======================================================
While executing the client process, the IP address and PORT number of server is to be passed as command line argument.

Ex: ./client.out 10.2.57.116 10011

=======================================================
                          OUTPUT
=======================================================

At Client End:
Please enter the message: abcd
Sending to SERVER: abcd
Received FROM SERVER: dcba

At Server End:
Server Received:abcd


=======================================================
                        NOTE
=======================================================

THE PORT USED BY SERVER: 10011
Change it accordingly in server.c line no 48

