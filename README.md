PROBLEM STATEMENT:
The concern with radio frequency allocation is that the towers within the same cell cannot have the same frequency. 
Each cell uses frequencies only within its boundaries, the same frequencies can be reused in other cells not far away with a limited possibility of interference.
Our objective is to assign different frequencies to adjacent towers in a given network while allowing non adjacent towers to have the same frequency but the task becomes more complex with increasing number of towers in a given network area.

SOLUTION:
The solution is to treat the cell towers as a graph and to implement a k-colouring algorithm for the allocation of frequencies.
Each node represents a tower, and the colours represent different frequencies.
This problem is implemented using the NK-method of graph colouring for k colours
The idea is to assign a set of K qubits to each node. So, we define a colouring matrix C of N lines and K columns.
The solution can be implemented on any quantum system using existing technology and algorithms, as problems like graph colouring are well suited for quantum computing the solution is expected to be time efficient and effective.



