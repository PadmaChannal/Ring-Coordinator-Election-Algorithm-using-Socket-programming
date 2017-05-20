# Ring-Coordinator-Election-Algorithm-using-Socket-programming
This project implements an concept of Distributed Systems - Election Algorithm. There are 8 nodes that participate in the election. A token is passed around all the nodes and the process/node with highest ID is elected as coordinator. If the coordinator fails and a process in the ring doesn't receive the token in the specified time limit, it starts the election and elects a new coordinator and informs other processes. 
