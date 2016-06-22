# paxos-cpp
Toy implementation of Basic Paxos, on threads.

Compiled like this:
g++ -std=c++11 -mcx16 *.cpp -o paxos

Fun demo, showing one round of Paxos, is run like this:
./paxos

The implementation doesn't have a distinguished proposer (leader).