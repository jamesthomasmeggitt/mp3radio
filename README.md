# Mp3radio
A simple arduino build that takes a $35 standard AM/FM radio and uses its inbuilt speaker and potentiometers to trigger mp3 files on an external mp3 module.

Dev Log 20-Jan-2023
It is important to note that the current code for this project will trigger sound files based on a sum of the two potentiometer values meaning that the "coordinates" for triggering files can be found at multiple locations. For example is file 001 is triggered by the number 13 then the potentiometers at 5 and 8 OR 10 and 3 will trigger the file. 
I plan on updating the code to program specific locations for the mp3 sound files. For now it operates in a "randomly turn the dials to see what happens" kind of way.

Feel free to use this project however you like.

Parts required:
  - Arduino Nano
  - AM/FM Radio (https://www.jbhifi.com.au/products/xcd-portable-am-f-radio?store=197&gclid=Cj0KCQiAic6eBhCoARIsANlox86xEPaZHDIN-8eEci8UloX6xV4yE043OWH6r5AHC8LnDBoH3Gpgy1waAnsaEALw_wcB)
  - 220ohm resistor
  - MP3 Module
    - DFmini: https://core-electronics.com.au/dfplayer-a-mini-mp3-player.html?gclid=Cj0KCQiAic6eBhCoARIsANlox87Bd92FCiVCnNWwBmmTlUeVCBC0K5j7Ae9nditFBbew9WIo6CvAhLMaAlbJEALw_wcB
    - XC3748 Music player module: https://www.jaycar.com.au/mp3-audio-player-module-with-6-push-button-switches-for-arduino/p/XC3748?     gclid=Cj0KCQiAic6eBhCoARIsANlox85GJSi3sHHEiSQ6_c9Emni5UrXHhhsrZTuL6uLDKrXnS1SCvFLNO0gaAjuLEALw_wcB (please note that you will need to install the relevant libraries in order to use this module rather than the DFmini)
    - Connector wire
    - Solder
