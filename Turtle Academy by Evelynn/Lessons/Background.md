
Now everything ready for the fill command **setcolor COLOR fill** . While color can be any of the colors in the list ( see lesson "Colors"). setting the color can be done by specifying name or number , setcolor 4 = setcolor "red.

Filled command is as follow, **``filled COLOR [Commands]``** . Notice the filled command will fill the selected COLOR only after it's running the commands and will fill the area created by the sequence of commands

```

repeat 4 [fd 100 rt 90]
pu rt 45 fd 50 pd
setcolor "red fill
filled "blue [repeat 4 [fd 100 rt 90]]

```