# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

Text representation, Graphical representation, Python - Dictonary representation.

## PROBLEM STATEMENT:
```
Dveloped by : M.vivek reddy
Reg No: 212221240030
```
### Problem Description
To conplete the school admisssion process , the role of the agent is to promote if the student is eligible , if not eligible , no admisssion.

### State Space
{A1,A2,A3}->{0,1,2}

  A1-> Admission Process 1
  
  A2-> Admission Process 2
  
  A3-> Final Process of Admission

### Sample State
A1 -> Admission Process 1

### Action Space

{E,NE} -> {0,1} E -> Eligible NE -> Not Eligible
### Sample Action

E-> Eligible
### Reward Function

R= {
    +1, if eligible
    +0, otherwise


### Graphical Representation

![r1](https://github.com/Vivekreddy8360/mdp-representation/assets/94525701/5a3d00ca-f782-456f-9edf-2283f1216f08)


## PYTHON REPRESENTATION:
```
T = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 1, 0.0, False)]
    }
}

T
```
## OUTPUT:

![rl1 2](https://github.com/Vivekreddy8360/mdp-representation/assets/94525701/fb5c5d02-3111-4883-8798-e654467a847e)

## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation, Graphical representation, Python - Dictonary representation.

