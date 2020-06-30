# awww
Simple text web browser for ACME editor

## Usage:

Run 'awww URL' from command line or ACME tag.

It will open a new window in ACME and display web content rendered as plain text.

Mouse 2/3 clicked on href/link will open a new window.

## Dependencies:
- rc/acme from [plan9port](https://github.com/9fans/plan9port)
- wget
- html2text from [rust-html2text](https://github.com/jugglerchris/rust-html2text)

## Installation:
Put 'awww' rc script to anywhere in your PATH. 

NOTE: change the `#!/usr/bin/rc` according to your 'rc' path.
