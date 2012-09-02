# ELKA55 - PRINTER
--------------------------------------------------------------------------------
Printing element description.  

This element requires *ink ribbon for typewriters (13mm)* 
and *roll of paper (57mm)*
--------------------------------------------------------------------------------

## Character placement:

*(assumptions)*  

Every roll with characters have own „blocker”. Whole setup of character rolls is 
rotating. On the side there is optical position recognized with 3 connectors. It 
it pushing signal through blue wire with when character is on its place.

### 4 rolls example:

We have 4 characters rolls. Every roll contains characters:  
a b c d

Assume that we want to write „bcda”:

1.  Rolling started
2.  TICK (signal from optical position recognizer)
3.  Status: a a a a
4.  Block 4th
5.  TICK
6.  Status: b b b a
7.  Block 1st
8.  TICK
9.  Status: b c c a
10. Block 2nd
11. TICK
12. Status: b c d a
13. Block 3rd
14. Continue rolling with no effect…
15. Press paper on the characters roll (print)


