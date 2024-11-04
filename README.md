# Simple-graph-to-matrix-in-ComputerVision
The goal is to take the image of a handwritten simple graph and extract the adjacency matrix and incidence matrix of the same
Few things to note in the code:
1. Vertices are identified by English uppercase letters
2. Vertices are colored in Red and Edges are colored in Blue for identification

# Stages of implementation
Reading the graph
![image](https://github.com/user-attachments/assets/195323c7-129a-44ff-9543-592535ce9112)

Node Recognition
![image](https://github.com/user-attachments/assets/adb097e2-58b4-40d6-880f-35c250ec9a75)

Vertices Recognition
![image](https://github.com/user-attachments/assets/6aca4eb7-f120-4bf8-94ad-b8462aa9feef)

Edges Recognition
![image](https://github.com/user-attachments/assets/2cb5179f-8d9f-4a4c-8a2c-b95fa0abb3e2)

Checking Connectivity
![image](https://github.com/user-attachments/assets/a314bb2e-aa91-421c-920a-9b0fdd23b174)

Draw up 
Adjacency matrix 
  A	B	C	D	E	F
A	0	1	1	0	0	0
B	1	0	0	1	1	0
C	1	0	0	1	0	0
D	0	1	1	0	1	0
E	0	1	0	1	0	0
F	0	0	0	0	0	0

Incidence Matrix
	1	2	3	4	5	6
A	1	1	0	0	0	0
B	1	0	1	1	0	0
C	0	1	0	0	1	0
D	0	0	1	0	1	1
E	0	0	0	1	0	1
F	0	0	0	0	0	0
