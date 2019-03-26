# N-Queens-Problem
Python multi-thread testbench.

Description
---------------
It solves the N-Queens Problem.

Usage
---------------
```
queenpool_multithread.py <Output.csv> <Queens> <Threads> <Repeat>
```

Example:
```
queenpool_multithread.py multithread_output.csv 12 4 100
```

This code example solves the N-queens problem with N=12 using 4 threads and repeats the process 100 times.

**Note:** The file `temperature.py` is only for the Raspberry Pi. You should only include this file if you are benchmarking a Raspberry Pi, and you want to save the temperature of the CPU/GPU too.

**Note:** It works only with Python 3.x, otherwise you get the following error:
```
cPickle.PicklingError: Can't pickle <type 'instancemethod'>: attribute lookup builtin.instancemethod failed
```
