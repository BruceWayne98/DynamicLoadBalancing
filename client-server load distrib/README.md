This is a set of programs that demonstrates how a server can divide and assign work to multiple clients in a distributed environment.

Requirements: Python 3.6, Windows

To run this program,
  1. Download this project folder into a location on your computer
  2. Extract this folder. 
  3. Open 2 powershell windows here
  4. In the first one, let's say for the server, enter a command similar to this `python .\launch_server.py 15 10001`
  5. In the second one, for creating clients, enter a command similar to this `.\launch_clients.ps1 10 10001`
 
15 indicates the number of tasks the server's pool should contain, 10001 indicates the port number on which to start the server

10 indicates the number of clients to spawn, 10001 indicates the port to connect to. 