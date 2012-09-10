assign-py
=========

A script for performing the Hungarian algorithm for solving the assignment problem in which each task may require multiple agents.

```python
assign.py <filename>
```

The script takes in a csv in the following format:

```
,     Task 1, Task 2, Task 3, Task 4, ...
,     Cnt 1,  Cnt 2,  Cnt 3,  Cnt 4,  ...
Agt1,
Agt2,
Agt3,
.
.
.
```

The values in the table have been omitted for clarity.

Cnt n refers to the number of agents required to complete Task n.

Dependencies
============

* munkres
