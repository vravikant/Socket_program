1) compile the three codes
c++ -o server server.c
c++ -o client client.c
c++ -o node node.c
2) run 
./server <serverport>
./node <serveraddress> <serverport>
./node <serveraddress> <serverport>
./node <serveraddress> <serverport>
./client <serveraddress> <serverport>
server address is localhost here
