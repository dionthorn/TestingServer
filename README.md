# TestingServer
Very basic Threaded http server.
Server.java listens forever for incoming connections and begins a new thread of ClientConnection per .accept() so as to not hang the server.

ClientConnection.java handles the individual client response.
