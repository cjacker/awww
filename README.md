# awww
Simple text web browser for ACME editor.

It use wget to fetch the webpage and rust-html2text to render it as plain text.

href/link openning is supported by ACME mouse chording.


![screenshot](https://github.com/cjacker/awww/raw/master/screenshot.png)


## Usage:

Run 'awww URL' from command line or ACME tag.

It will open a new window in ACME and display web content rendered as plain text.

Mouse 2/3 on href/link will open a new window.

## Dependencies:
- rc/acme from [plan9port](https://github.com/9fans/plan9port)
- wget from [wget](http://www.gnu.org/software/wget)
- html2text from [rust-html2text](https://github.com/jugglerchris/rust-html2text)

## Installation:
Put 'awww' rc script to anywhere in your PATH. 

NOTE: change the `#!/usr/bin/rc` according to your 'rc' path.
