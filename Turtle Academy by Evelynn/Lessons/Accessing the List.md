
When we created the list we told the logo turtle, please put the string “first in the first cell, the string “second in the second cell ... , and the string “fifth in the fifth cell. The command to access the list items is: item **NUMBER_OF_CELL LIST_NAME**. For example, to print the second item in our list we will write: print item 2 :listfive.

We can use the command **pick LIST_NAME** in order to pick a random item from a list.

The command **butfirst** will output all the list items except for the first item. We will use the command shortcut **bf**.

The command **butlast** will output all the list items except for the last item. We will use the command shortcut **bl**.

```

make "listfive (list "first "second "third "fourth "five)
print :listfive
print item 3 :listfive
print sum random 5 1
print item sum random 5 1 :listfive
print pick :listfive
print bf :listfive
print bl :listfive

```