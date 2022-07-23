### About Me

My name is Mina Nassif and I am currently a Computer Science major at the University of Michigan.

### Stock Market Simulation

This is a stock market simulation like project, where the program receives a series of "orders," or intentions to buy or sell shares of a certain stock. As each order comes in, the program sees if the new order can be matched with any previous orders. The use of priority queues were explored in this project (MAKE THIS SOUND BETTER).

Instead of matching buyers and sellers of a stock, this program matches Jedi and Sith battalions for battle! This means buy/sell are Sith/Jedi, stocks are planets, price is force-sensitivity, etc. Check out the spec and the code [here](https://gitfront.io/r/spec-mina/zimDBG2adFKQ/Stock-Market-Simulation/)!  

### Priority Queues

In this project, 3 different priority queues (PQ) have been implemented, a sorted PQ, a binary PQ, and a pairing PQ:
- The sorted PQ implements the priority queue interface by maintaining a sorted vector.
- The binary heap PQ implements the priority queue interface by maintaining a binary tree indexed into a vector (where 
- The pairing PQ implements the priority queue interface by 
Check out the spec and the code [here](https://gitfront.io/r/spec-mina/thH1hUMBMa8q/Priority-Queues/)!  

### SQL-Like Database

This program is a simpler version of an SQL, utilizing commands such as CREATE, INSERT, JOIN, REMOVE, PRINT, and GENERATE INDEX. Through the generate index function, this program uses hash tables to speed up future commands. Check out the spec and the code [here](https://gitfront.io/r/spec-mina/t6Ld69BYYsh6/SQL-Like-Database/)!

### Gotta Catch 'em All

This program utilizes Minumum Spanning Trees and Branch and Bound algorithms to solve the Traveling Salesperson Problem. This program has three modes:
- MST mode: this mode will devise a path that visits every pokemon location while minimizing the total distance of that path using Prim's algorithm
- FASTTSP mode: this mode will produce a *close* to optimal TSP tour utilizing Nearest Neighborand 2-opt algorithms. For this reason, it will run much faster than the optimal TSP tour.
- OPTTSP mode: this mode finds an optimal solution to the TSP (the actual minimum Euclidean distance necessary) by using an efficent Branch and Bound algorithm.
Check out the spec and the code [here](https://gitfront.io/r/spec-mina/eaRK4g5JAWvg/MST-and-Branch-and-Bound-algorithms/)!  
