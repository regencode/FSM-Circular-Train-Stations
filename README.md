# Circular City using Finite State Automata

Welcome to Circular City! In this city you are only allowed to walk in the counter-clockwise direction, however you can travel in clockwise through the train stations. You start at home (000) and your destination is at 101 (accept state).

## DFA Implementation:
![FSM-circularcity-diagram](https://user-images.githubusercontent.com/114067350/210193342-b67335dd-8dcb-46ec-8ce5-d7f8c01887dd.png)

## DFA Definition:
DFA is defined as a 5 tuple -> DFA = (Q, sigma, delta0, q0, F)

The definition of this DFA:

Q = {000, 001, 010, 011, 100, 101, 110, 111}

sigma = {Enter/leave Train Station, Move to next area} encoded to {0, 1}

delta0 = 

![FSMdelta](https://user-images.githubusercontent.com/114067350/210193557-b417c89b-3812-46a8-a7b8-79e98cb2f93a.png)

q0 = 000

F = {101}

## State transitions as K-maps:

![kmap-1](https://user-images.githubusercontent.com/114067350/210193682-0ea09a2b-53ca-4bde-93ba-462d5a9a064b.png)

![kmap-2](https://user-images.githubusercontent.com/114067350/210193685-e557610f-74aa-45ae-a2df-751481ec491e.png)

![kmap-3](https://user-images.githubusercontent.com/114067350/210193688-89731284-998e-4002-94ea-1a2e67c606a2.png)


# Code implementation

In the main.c file, the implementation of the DFA is through the K-maps that are obtained through the changes of s0, s1, and s2

## How to run:
With Makefile installed on your system, type "make" or "make run" to the terminal.

