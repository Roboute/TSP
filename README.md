TSP
===

Traveling Salesman Problem

To compile the TSP_Parallel use mpicc -lm -o execute_name TSP_Parallel
Copy a point file into the same directory and rename it points.txt
To run the program use mpiexec -n 4 ./execute_name

to compile the TSP_Sequential use gcc -lm -o execute_name TSP_Sequential
Copy a point file into the same directory and rename it points.txt
To run the program just do ./execute_name
