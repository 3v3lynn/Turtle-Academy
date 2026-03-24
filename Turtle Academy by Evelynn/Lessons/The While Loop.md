
The **do.while** command consist of 3 parts **``do.while[ COMMANDS ]condition``** the command will be executed till the condition fullfill.


```

make "x 1 do.while [ print :x make "x :x + 1 ] :x < 10
do.while [ make "x ( readword [Please enter a number] ) ] :x < 10
do.while [ print "yoyo make "answer ( readword [Would you like to stop printing yoyo? yes/no] ) ] notequalp :answer "yes

make "number sum random 99 1 do.while [ make "answer ( readword [choose a number between 1- 100] ) if :answer > :number [ print [ number too big ] ] if :answer < :number [ print [ number too small ] ] ] :answer <> :number print [ good job]

```