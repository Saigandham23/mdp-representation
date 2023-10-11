# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.
## PROBLEM STATEMENT:
To develop a AI agent which controls the level of fluoride percentage in water.

### State Space
```
{A,B,C} -> {0,1,2}

where,

A->LOWER than required

B->CORRECT amount

C->HIGHER than required
```
### Sample State
```
A->0-lower than required

Action Space
{H,L} -> {0,1}

where,

H -> higher the fluoride percent

L -> higher the fluoride percent
```
### Action Space:
```
{H,L} -> {0,1}

where,

H -> higher the fluoride percent

L -> higher the fluoride percent
### Sample Action
H -> 0

which means we have to increase the fluoride percent in water

```
### Reward Function
```
R = { +1 , for correct amount of fluoride
       0 , otherwise
```
### Graphical Representation
![image](https://github.com/Ramsai1234/mdp-representation/assets/94269989/05fa159a-d069-4b98-b2ab-36f8b3d04b8d)


## PYTHON REPRESENTATION:
```
P = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 0.0, False)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 0.0, False)],
        1 : [(1.0, 1, 1.0, True)]
    }
}
```

## OUTPUT:
![image](https://github.com/Ramsai1234/mdp-representation/assets/94269989/0970b770-ad94-486c-9ad2-de130d197dca)

## RESULT:
Thus the given real world problem is successfully represented in a MDP form .
