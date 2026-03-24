
We want to create a moving ball that will run continuously on the screen. In this lesson we will see how to break the problem into parts and then we will combine all the parts together. So what will we have to do: 1) Create a ball. 2) a) Make the ball move b) move but not that fast. 3) We don't want it to smear. 4) Hide the turtle.

```

cs filled "blue [arc 360 20]

```

Nice, we do have a ball now so let's get it moving. One way to do so can be to use the repeat command, We can tell the ball to move 100 time each time forward 10 points. We will use the ball created in the previous step and add the moving part.

```

repeat 100[ fd 10 filled "blue [arc 360 20]]

```

The ball is now moving too fast ... How can we make him move slower? Well we can use the wait command.

```

cs repeat 100 [ fd 10 filled "blue [arc 360 20] wait 18 ]

```

We have another problem, the ball is moving nicely but keep smearing. Why is that? Because we didn't clean the screen after each movement, we can use the command 'clean' in order to clean the screen without moving the turtle to home position.

```

cs repeat 100 [ clean fd 10 filled "blue [arc 360 20] wait 18 ]

```

We do have the ball moving as expected but... we don't really need the turtle to appear so let's add ht after as the first command. You can also try yourself a nice challenge .. how will you make 2 balls moving in parallel (You might have to use xcor, ycor and setxy commands). You can check out https://turtleacademy.com/programs/69662

```

ht cs repeat 100 [ clean fd 10 filled "blue [arc 360 20] wait 18 ]

```