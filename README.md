# Leonardo-Num-by-Posix_Thread
Using C with pthread to implement recursive build of Leonardo Num Tree and print each node value

Example output if ./leothread 4:

(0
(1
(2
[3]
[4]
2)
[5]
1)
(6
[7]
[8]
6)
0)


"(" means the beginning of a non-leaf node, ")" means the closing of a non-leaf node, "[]" means it is a leaf node and value in between is the value of the node


If input 0: wrong arg
If input 1: directly output [0]
If put arg N, It creates L(N) - 1 threads to print. .tr file to show an example with ./leothread 4

