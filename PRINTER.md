# ELKA55 - PRINTER
--------------------------------------------------------------------------------
Printing element description.  

This element requires *ink ribbon for typewriters (13mm)* and *roll of paper (57mm)*

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
2.  TICK (signl at OPTIC_POS)
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

## Printer Connector (35 pin)

### Schematic:
#### Front look (solder points):
	 1                                18
	 · · · · · · · · · · · · · · · · · ·
	O · · · · · · · · · · · · · · · · · O
	 19                               35

#### Bottom layer (the same like front):
	 1                                18
	 · · · · · · · · · · · · · · · · · ·
	O · · · · · · · · · · · · · · · · · O
	 19                               35

### Original pin description:
1. MOTOR_GND
2. ROTATE
3. RACK_UP_A (?)
4. BLOCK_1
5. BLOCK_3
6. BLOCK_5
7. BLOCK_7
8. BLOCK_9
9. BLOCK_11
10. BLOCK_24
11. BLOCK_25
12. NC
13. RACK_UP_B (?)
14. OPTIC_POWER
15. NC
16. NC
17. NC
18. NC
19. MOTOR_POWER (+16V)
20. NC
21  NC
22. BLOCK_2
23. BLOCK_4
24. BLOCK_6
25. BLOCK_8
26. BLOCK_10
27. BLOCK_12
28. NC
29. BLOCK_26
30. NC
31. OPTIC_POS
32. OPTIC_GND

NC - No Connect
