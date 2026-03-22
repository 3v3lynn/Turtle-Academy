
A variable has the ability to remember a value that was set into it. To create a new variable we will use the following command:**make "VAR_NAME VAR_VALUE**. For example: the command **make "x 3** will set the value 3 in the variable x.

To access the variable value we should put the colon (:) sign before the variables name. To access the content of the variable y will will use - :y

We can sum 2 values together using the **sum** command The command structure is -**sum FIRST_VALUE SECOND_VALUE.** For example: **sum 2 4** will show us 6

A Difference command looks like the same as the sum command, only instead of adding up - it subtracts. It looks like this: **difference VAR_A VAR_B**

```

make "y 5
print :y
print sum 2 4
make "x sum 3 6
print sum :x :y
make "z difference :x :y

```