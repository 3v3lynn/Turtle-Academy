
```

to head :radius :color setcolor :color arc 360 :radius fill end

to part :position :size rt :position fd :size end

to person :x :y ht pu setxy :x :y pd head 30 "black part 180 150 pu setxy :x (:y - 150) pd part 30 100 pu setxy :x (:y - 150) pd part -60 100 pu setxy :x (:y - 50) pd part 60 100 pu setxy :x (:y - 50) pd part -60 100 end

to mover make "x -200 repeat 50 [cs seth 0 person :x 0 make "x :x + 5 wait 5] end

mover

```
