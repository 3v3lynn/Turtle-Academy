
This lesson will be based on program Colorful my way. We will create lines of circles from a list of inputs the user chose on runtime. We will use the following commands **readlist, filled, pick and wait**

```

to circle :size :color filled :color [ arc 360 :size ] end
circle 60 'blue
to circlerow :size :color pu setx -300 setheading 90 repeat 6 [ circle :size :color fd 120 ] pd end
repeat 4 [ circlerow 50 pick :listcolors wait 200 pu sety repcount * 120 pd ]

```