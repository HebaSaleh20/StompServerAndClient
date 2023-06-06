# StompServerAndClient
The world cup is upon us, and you want to stay updated. Thus, in this assignment, you will implement a ”community-led” world cup update subscription
service. Users can subscribe to a game channel and report and receive reports
about the game to and from the other subscribed users.
For the above-mentioned purpose, you will implement both a server, which
will provide STOMP server services and a client, which a user can use in
order to interact with the rest of the users. The server will be implemented
in Java and will support both Thread-Per-Client (TPC) and the Reactor,
choosing which one according to arguments given on startup. The client will be
implemented in C++ and will hold the required logic as described below.
All communication between the clients and the server will be according to
STOMP ‘Simple-Text-Oriented-Messaging-Protocol’.
In order to get you started, we supply a few examples for different protocols
and clients, the most complete ones being newsfeed and echo, we recommend
you go over them. Specifically, note how they can use both TPC or Reactor
server implementations.
