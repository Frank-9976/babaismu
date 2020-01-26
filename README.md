# babaismu
This is a Baba is You demake for the CASIO fx-9750GII written entirely in BASIC.

# how to download
First get this from CASIO's website: [https://edu.casio.com/education/support_software/dl/PC_links/fa124_inst_204_2.zip](https://edu.casio.com/education/support_software/dl/PC_links/fa124_inst_204_2.zip)
Then use the program to download the distribution file to your calculator.
Then make a 7x18 matrix in Mat C's location. This will be the level. Otherwise the calculator will error on the line "Mat C -> Mat A".
Finally, run the program "B-U". (It stands for B=U, viz. Baba is You.)

# features
If you just have a blank matrix (all 0s) for Mat C then the level will be empty, devoid of any puzzle solving. To make a level, just use the built-in matrix editor to make a level with these ids:
0 - empty - " "
1 - baba - "B"
2 - flag - "F"
3 - rock - "R"
4 - wall - "W"
11 thru 14 - noun text - fancy corresponding letter
21 - IS - "="
22 - HAS - reversed set membership symbol (unimplemented because you cannot destroy objects yet)
31 - YOU - fancy u with a dot over it
32 - WIN - fancy w
33 - PUSH - fancy p
Important changes: everything is de facto STOP because there is no stacking in this demake. You can win either by having an object be both WIN and YOU or by having a YOU object try to move into a WIN object. If you do not follow these instructions, demons may fly out of your nose and give you an error.
Also note that pushing is recursive and runs out of stack space at around ten objects. The game will purposely error because I thought it would be funnier that way.

# premade levels
I have made some premade levels which I have put in the levels folder (not yet as of now, pretend this is in future tense). They are in the CSV format and can be converted to a 7x18 matrix via the program linked above. Simply copy them to Mat C to enjoy a nice laggy puzzle.
