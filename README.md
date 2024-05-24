# Best_First_Search_Algorithm-Python-



![Uploading image.png…]()

Best First Seacrh (BFS) can be applied in resource scheduling problem, such as scheduling tasks
on a distributed computing system. By prioritizing tasks based on factors like processing time and
resource requirements, BFS helps optimize resource utilization and minimize completion time.
The graph in Figure 1 is for resource scheduling using Best First Search (BFS) representing tasks
as nodes and the dependencies and resource requirements between tasks as edges.
You have the following tasks to be scheduled:
Task A requires 2 units of Resource X and 1 unit of Resource Y.
Task B requires 1 unit of Resource X and 2 units of Resource Y.
Task C requires 1 unit of Resource X and 1 unit of Resource Y.



Task D requires 2 units of Resource X and 2 units of Resource Y.
Task E requires 1 unit of Resource X and 1 unit of Resource Y.
There are some dependencies between these tasks as follows:
Task A must be completed before Task B and Task C can start.
Task B must be completed before Task D can start.
Task C must be completed before Task E can start.
Task D must be completed before Task E can start.
You can compute the heuristic value of each node from the given task dependencies (e.g., no. of
tasks remaining to be completed).
Calculate the Time complexity, Space Complexity, and Complete Path of this problem. Plot the
graph of the complete path using library network and matplotlib.
