# Definition of the Problem 

In the year 2150, so many years after Moore's Law came to an end, you are in charge of the   
spacecraft, Galaxy Wanderer, in this post-apocalyptic scene. You are making interplanetary   
leaps and Galaxy Wanderer can hold at most three units of plutonium. Plutonium is fuel for   
the spacecraft and you need exactly one unit of plutonium to make a leap between directly   
connected planets. Some planets contain an infinite amount of plutonium and you, as the   
captain, are allowed to exploit this and refuel the Galaxy Wanderer to its maximum limit (3).    
The other planets contain no plutonium at all.  

You start your crusade with no plutonium. Knowing the locations of all the planets in the   
universe (including knowledge of which contain plutonium), you want to calculate the number   
of planets that you can reach from your starting point.   

Write a function: 
```python
def solution(T,B):
    pass
```
that given a non-empty array T consisting of N integers describing the network of planets and   
array B consisting of N booleans describing whether each planet contains plutonium, returns    
the number of planets that you can reach from your starting point.  

Array T describes a network of planets as follows:  
- if `T[P] = Q` and `P = Q`, then `P` is the starting point;  
- if `T[P] = Q` and `P != Q`, then there is a direct access between planets P and Q. 

Array B describes planets with plutonium as follows:  
- if `B[P] = True` then there is plutonium in planet P;
- if `B[P] = False` then there is no plutonium in planet P.

# Examples

## Example 1

Given the arrays:  
- `T = [9,1,4,9,0,4,8,1,0,7]` 
- `B = [False, True, False, False, False, False, False, True, False, False, False]`
the function should return 7. The network consists of ten planets and nine direct access   
connections. We start on planet number 1, and planets 1 and 7 contain plutonium resources.   
There are seven reachable planets (0,1,3,4,7,8,9).  

## Example 2

Given the arrays:  
- `T = [0,0,1,2,3]` 
- `B = [False, False, False, False, False]`
the function should return 1. The only reachable planet is the starting point (0).  

# Task

Write an efficient algorithm for the following assumptions:
- N is an integer within the range [1...100000];
- each element of array T is an integer within the range [0..N-1];
- there is exactly one (possible indirect) connection between any two distinct planets

**Source:** Codility Limited (Copyright 2009-2019) Do not distribute! 
