
![Imagen](../img/15wordschallenge.png)

```

repeat 8 [rt 45 repeat 6 [repeat 90 [fd 2 rt 2] rt 90]]
for [i 0 420] [seth :i repeat :i [fd 2 rt 1] pu home pd]
repeat 5000 [run list item sum 1 random 4 [fd bk rt lt] random 10]
for [l 10 80 5] [repeat 5 [repeat 8 [fd :l rt 45] rt 72]]

```