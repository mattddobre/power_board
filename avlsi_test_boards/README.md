# avlsi_test_boards

Most DRC errors fixed exepct a few due to silk screen being clipped by edge cuts

There are 38 pins that are not digital io on the opal kelly header. There are 32*7 = 224 pins from the level shifters. There are 122 connections to the opal kelly header, leaving 102 connections to the pin headers from the level shifters. After adding non io pins 140 out of 160 pins will be connected. 

The header was changed to something smaller. For now I did not remove duplicated connections but I shorted them on the board.  

The text on the header was removed for now since it was too small. 
