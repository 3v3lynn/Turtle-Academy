
So far we have seen that when the drawing area for the turtle ends the turtle will appear from the other side .. so if we are going upward then the turtle will appear from the button if we are off the limit on the right we will appear from the left. Now let's do a simple program that demonstrates it

```

cs fd 450 rt 90 wait 100 fd 500

```

The turtle default border definition is wrap that means that If the turtle moves off the edge of the screen it will continue on the other side. We can also explicitily order the turtle to use this mode ( in case we change the mode and want to go back to wrap mode ).

```

cs wrap fd 450 rt 90 wait 100 fd 500

```

The turtle can move past the edges of the screen, unbounded. In this case the turtle will not come back from the other side but will continue to move out of the drawing area  
Let's observe the turtle behavior with the window mode.

```

cs window fd 450 rt 90 wait 100 fd 300 rt 90 wait 100 fd 300

```

In this step.. when the turtle is out of the window area. we will get his location and print it on the screen

```

cs window fd 450 rt 90 wait 100 fd 300 make "x xcor make "y ycor type [x is ] print :x type [y is ] print :y rt 90 wait 100 fd 300

```

If the turtle attempts to move past the edge of the screen it will stop. in this step we will go forward 30 times .. 10 point each time .. till we hit the border

```

cs fence repeat 30 [ fd 10 wait 10]

```

We have 3 different border conditions: wrap, window and fence. Each one of them behaves differently when the turtle is trying to get out of the drawing area borders.