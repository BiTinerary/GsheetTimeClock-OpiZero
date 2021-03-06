# ArmbianTimeClock.py
A Google Sheet punching timeclock made from an MFRC522 module/tags, OrangePi Zero, Armbian and a modified case.  

![blinky2](https://user-images.githubusercontent.com/8212296/33339935-3d6bed48-d440-11e7-80fb-850be5dc8113.gif)
![sideby](https://user-images.githubusercontent.com/8212296/33340459-bd7858d6-d441-11e7-9e00-3e7ec3b27a79.jpg)

## Dependencies
* My Custom rollup of MFRC522 library tweaked to use OPi.GPIO: https://github.com/BiTinerary/OrangePiZeroMFRC522
  * `git clone https://github.com/BiTinerary/OrangePiZeroMFRC522.git && bash ./OrangePiZeroMFRC522/getAllTheStuff.sh`
* gspread for Google Sheet API functionality: https://github.com/burnash/gspread
  * `pip install gspread`
* oauth2client for authenticating usage of Google API with script: http://gspread.readthedocs.io/en/latest/oauth2.html
  * `pip install oauth2client`

## Installation
To be simplified and condensed at a later date.
