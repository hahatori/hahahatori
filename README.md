# Agents!

This project including [agentframework.py](https://github.com/hahatori/Agents/blob/master/agentframework.py) and [model.py](https://github.com/hahatori/Agents/blob/master/model.py).

## Contents

- [Details](#details)
- [Theoretical Result](#theoretical_result)
- [Actual Result](#actual_result)
- [Issues](#issues)

## Details

### ABM (Agent-Based Model):

[Agent]() code can build agents to interact.
[Model]() code can creat models for connecting developers and users.

### random module:

It generates a random number of characters from 0 to 1 (0 <= n < 1.0):

```sh
$ random.random()
```

It generates a random number n (12 <= n <= 20):

```sh
$ random.randint(12, 20)
```

Error:

```sh
$ random.randint(20, 12)
```

## Theoretical Results

Expect to move random coordinate points and calculate the distance between two sets of them, then show the 10 points in a scatter plot with x and y axes of 0 to 99. 

## Actual Result

![Scatter Plot](https://github.com/hahatori/Python_Assignment1/blob/master/AgentPlot.png)

## Issues

1. Indentation of 4 spaces.

2.The code is complex and long in **model.py**, without importing the statement of **agentframework.py**.



