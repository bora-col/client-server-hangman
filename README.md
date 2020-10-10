# python-client/server-hangman
This project is a multithreaded client/server hangman game.
The server serves the game, clients join and play concurrently.
TCP/IP communication is used to establish the communication.


## How to play?

###### Important Note:
```
All the computers participating in the game should be in the same Local Area Network(LAN).
This can be achieved by connecting all the computers to the same Wi-fi.
```

1. Run the server:
> Open a command line window and run the following command.
```
python3 tcp-server.py
```

2. Specify the number of players:
> The server program will ask you to specify the number of players from the command line prompt as follows.
```
Number of players: 
```

3. Run the clients
> If you specified 'N' number of players, open 'N' different command line windows and run the following command.
```
python3 tcp-client.py
```
