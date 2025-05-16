# Kruskal's ALgo (Minimun Cost Spanning Tree)
![image KruskalAlgo](/./kruskal1.jpg)
```
no. of vertices = 7
Spanning Tree Create: No. of edges(v-1)=6

```

## Round Robin Algo for Spanning Tree

![image roundRobinAlgo](/./roundRobinAlgo.jpg)

| Q | Priority Queue |
|----|----|
| {A} | 1,2  |
| {B} | 2,2,3,3 |
| {C} | 1,2,4 |
| {D} | 2,4,5 |
| {E} | 3,5  |

| Q | Priority Queue |
|----|----|
| {B} | 2,2,3,3 |
| {D} | 2,4,5 |
| {E} | 3,5  |
| {A,C} | 2,3,4 |

| Q | Priority Queue |
|----|----|
| {E} | 3,5  |
| {A,C} | 2,3,4 |
| {B,D} | 2,3,3,4,5 |

| Q | Priority Queue |
|----|----|
| {A,C} | 2,3,4 |
| {B,D,E} | 2,3,4,5,5 |

| Q | Priority Queue |
|----|----|
| {A,B,C,D,E} | 3,3,4,4,5,5 |


----

## Djikstra's Algorithm
![image DjikstraAlgo](/./djikstra.jpg)

> visiting & exploring

### pseudocode
```
for each vertex V:
  dist[v] = infinity
  prev[v] = none
  dist[source] = 0

set all values to unexplored
while destination nit explored
v =least-valued unexplored vertex
set  to explored

for each edge(v,w)
  if dist[v] + len(v,w) < dist[w]
    dist[w] = dist[v]+len(v,w)
    prev[w] = v

```

