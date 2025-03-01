# Cryptographic Lock Decryption Project

## Overview
The goal of this project is to unlock a cryptographic lock, represented by a sequence of actions generated based on a string passed in creating the lock. I implemented three search algorithms: Breadth-First Search (BFS), Depth-Limited Search (DLS), and Iterative Deepening Search (IDS) to unlock the lock. These algorithms are tested on locks ranging from length 1 to 14, recording the amount of time and space each algorithm uses. The results allow us to compare the efficiency and effectiveness of the algorithms.

The task uses a 4-ary tree structure to represent the lock and its sequence of actions. Each action (pull, poke, shake, and twist) can be represented by a node in the tree, and each node can have four children, each corresponding to one of the actions. The root node represents the lock itself. The algorithm proceeds by traversing the tree and checking the sequence of actions until the lock is unlocked. 

## Results

- BFS is most effective for shallow solutions but has high memory consumption.
- DLS is ideal for specific depths and consumes less memory than BFS.
- IDS is the best when the depth is unknown, but it may have a higher running time than DLS and BFS.

## **Skills: Java, Data Structure**
