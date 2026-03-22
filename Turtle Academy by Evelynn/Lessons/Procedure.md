
The definition of a basic procedure with no parameters is : **to PROCNAME ACTIONS end**. When PROCNAME is the name of the procedure and ACTIONS are the commands. In the lesson 'The turtle is learning we have define a procedure called 'dashline' like this . **``to dashline repeat 5 [setwidth 1 fd 10 setwidth 3 fd 10] end``**. Here the PROCNAME part is 'dashline' and the ACTIONS part is ``repeat 5 [setwidth 1 fd 10 setwidth 3 fd 10]``.

We can also create a procedure that expect parameters. the definition will be : **to PROCNAME :INPUT1 :INPUT2 ACTIONS end**.We can use as many input parameters as we want (when we defined triangle we used 0 input parameters ). We can use the input param in the ACTION.


```

to triangle repeat 3 [fd 100 rt 120] end
triangle
to going :fdinput fd :fdinput end
going 150
to polygon :edges repeat :edges [fd 100 rt 360/:edges] end
polygon 4

```