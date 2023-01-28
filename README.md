# mp3radio
A simple arduino build that takes a $35 standard AM/FM radio and uses its inbuilt speaker and potentiometers to trigger mp3 files on an external mp3 module.

Dev Log 20-Jan-2023
It is important to note that the current code for this project will trigger sound files based on a sum of the two potentiometer values meaning that the "coordinates" for triggering files can be found at multiple locations. For example is file 001 is triggered by the number 13 then the potentiometers at 5 and 8 OR 10 and 3 will trigger the file. 
I plan on updating the code to program specific locations for the mp3 sound files. For now it operates in a "randomly turn the dials to see what happens" kind of way.

Feel free to use this project however you like.
