This project is a C-based simulation of a tournament system using stack and queue data structures
It reads a list of team IDs from user input
Each team participates in knockout-style rounds until a champion is determined
A queue is used to manage teams in each round
A stack is used to store eliminated teams for tracking results
The winner of each match depends on the round number
In odd rounds the smaller ID wins
In even rounds the larger ID wins
Teams are dequeued in pairs to simulate matches
Winners are enqueued for the next round
Losers are pushed onto a stack for later processing
If there is an odd team it automatically advances to the next round
The process repeats until only one team remains
That final team is declared the champion
A separate function determines the runner-up team
It checks which teams lost to the champion
The stack is reversed to maintain correct elimination order
Memory allocation is used dynamically for all nodes
Input validation ensures valid number of teams and IDs
The program demonstrates practical use of stacks and queues in tournament simulation
