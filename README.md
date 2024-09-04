# File Transfer using TCP Socket in C

**OS:** Ubuntu 20.04 LTS</br>
**IDE:** Vim</br>

## Commands to be followed

###Compile:
```shell
./compile.sh
```
##Execute
### Server:
```shell
./server
```
### Client:
```shell
./client [file_to_transfer]
```

Output on **Client side** console/terminal:
```shell
[+]Server socket created. 
[+]Connected to server.
[+] File data send successfully. 
[+]Disconnected from the server. 
```

Output on **Server side** console/terminal:
```shell
[+]Server socket created. 
[+]Binding Successfull.
[+]Listening...
[+]Data written in the text file
```

**Note:** </br>
**1.** The Libraries **#include<apra/inet.h>** are available only for the Linux Distros not for the windows, for windows we need to use **#include<winsock2.h>**</br>
