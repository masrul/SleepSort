# SleepSort
Sleep sort is an interesting sorting algorithom, though it does not have practical usages. It takes array of non-negative integers from commandline and print the arguments in asceding order. Each array element is delt with individual thread, corresponding thread sleeps for magnitude of element and print it.

```bash  
Compile: FC -fopenmp sleepsort.f90 -o sleepsort
run    : ./sleepsort 2 1 0 4
Output : 
0
1
2
4
```
