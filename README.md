## ft_irc
ft_irc is a project to develop an IRC (Internet Relay Chat) system as part of the curriculum at Ecole 42. The goal is to create both an IRC server and a client capable of connecting to this server and communicating with other users through chat channels.

## Project Structure
The project is structured as follows:

- **commands/ : This directory contains source files for various commands supported by the IRC client.**
- **include/ : This directory contains header files necessary for compiling the project.**
- **makefile : The makefile contains compilation rules to simplify the build and execution process of the project.**
- **src/ : This directory contains main source files for the project, including IRC server and client source code.**
- **utils/ : This directory contains utility functions or reusable code necessary for the project.**

## Compilation and Execution
To compile the project, use the provided makefile. Ensure all dependencies are installed and your development environment is properly configured.

## Compiling the Project:
```sh
make all
```

## Running the IRC Server:
To start the IRC server, use the following command:
```sh
./server [port]
```
Replace [port] with the port number on which you want to start the server.

## Running the IRC Client:
To start the IRC client, use the following command:
```sh
./client [server_address] [port]
```

Replace `[server_address]` with the IP address or domain name of the IRC server you want to connect to, and `[port]` with the corresponding port number.

## Features
- **Server Connection: Allows a client to connect to the IRC server.**
- **Communication: Users can send messages to chat channels or privately message other users.**
- **Channel Management: Users can create, join, leave, and delete chat channels.**

## Contributors
[pschemit](https://github.com/pschemit)
[yboughan](https://github.com/YoussefBOUGHANMI)
