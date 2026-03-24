
Many times we might want to use a Square in our program, but it can be frustrating to define it every time.

Luckily we have a way to reuse our code. We can define a program that include our functions and then include it in our program. In this case we created a program which has the id 45865 ( when creating a program you might see the Id in the URL). The include command works as follow: include ID (ID is the program id we include etc 1234).

```

TO square :size repeat 4 [ fd :size rt 90 ] END
TO triangle :size repeat 3 [fd :size rt 120] END
cs square 50 fd 50 rt 30 triangle 50
include 45865
cs square 50 fd 50 rt 30 triangle 50

```